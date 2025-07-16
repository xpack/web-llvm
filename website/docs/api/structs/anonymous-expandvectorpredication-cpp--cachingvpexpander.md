---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CachingVPExpander` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{ExpandVectorPredication.cpp}::CachingVPExpander { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf7c6eba52a5555ce4c8695015bb4d8a">CachingVPExpander</a> (const TargetTransformInfo &amp;TTI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787f048d94a8f173da27cb792cff4758">convertEVLToMask</a> (IRBuilder&lt;&gt; &amp;Builder, Value *EVLParam, ElementCount ElemCount)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac965f2137199995cb31f57f71cc3b568">foldEVLIntoMask</a> (VPIntrinsic &amp;VPI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If needed, folds the EVL in the mask operand and discards the EVL parameter. <a href="#ac965f2137199995cb31f57f71cc3b568">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad46652b66427679d9c221df6915019ca">discardEVLParameter</a> (VPIntrinsic &amp;PI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>"Remove" the evl parameter of <span class="doxyComputerOutput">PI</span> by setting it to the static vector length of the operation. <a href="#ad46652b66427679d9c221df6915019ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eba8b3e2e38c997d14bc2ee850be29a">expandPredicationInBinaryOperator</a> (IRBuilder&lt;&gt; &amp;Builder, VPIntrinsic &amp;PI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower this VP binary operator to a unpredicated binary operator. <a href="#a3eba8b3e2e38c997d14bc2ee850be29a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2529fdcdfd78c5eccd6079fc3c74ad3">expandPredicationToIntCall</a> (IRBuilder&lt;&gt; &amp;Builder, VPIntrinsic &amp;PI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower this VP int call to a unpredicated int call. <a href="#ad2529fdcdfd78c5eccd6079fc3c74ad3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f9944dba24143c8954964d7dff45b8">expandPredicationToFPCall</a> (IRBuilder&lt;&gt; &amp;Builder, VPIntrinsic &amp;PI, unsigned UnpredicatedIntrinsicID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower this VP fp call to a unpredicated fp call. <a href="#a62f9944dba24143c8954964d7dff45b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2153c46ea6d560ce96b6ad7e822d2c70">expandPredicationInReduction</a> (IRBuilder&lt;&gt; &amp;Builder, VPReductionIntrinsic &amp;PI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower this VP reduction to a call to an unpredicated reduction intrinsic. <a href="#a2153c46ea6d560ce96b6ad7e822d2c70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd88dbe6fb8f2ddbd621296ca4ebd5f">expandPredicationToCastIntrinsic</a> (IRBuilder&lt;&gt; &amp;Builder, VPIntrinsic &amp;VPI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower this VP cast operation to a non-VP intrinsic. <a href="#a5cd88dbe6fb8f2ddbd621296ca4ebd5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f1f1359a986d8e4d1b107ae4c524a32">expandPredicationInMemoryIntrinsic</a> (IRBuilder&lt;&gt; &amp;Builder, VPIntrinsic &amp;VPI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower this VP memory operation to a non-VP intrinsic. <a href="#a1f1f1359a986d8e4d1b107ae4c524a32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5afd2ab39f4d739286d175f8babb8e6b">expandPredicationInComparison</a> (IRBuilder&lt;&gt; &amp;Builder, VPCmpIntrinsic &amp;PI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower this VP comparison to a call to an unpredicated comparison. <a href="#a5afd2ab39f4d739286d175f8babb8e6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee759d5807e7eb77e631717da4461426">expandPredication</a> (VPIntrinsic &amp;PI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query TTI and expand the vector predication in <span class="doxyComputerOutput">P</span> accordingly. <a href="#aee759d5807e7eb77e631717da4461426">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a8bbe0bdae41c88a50d5776a8b6bd9d5c">VPLegalization</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c2dd03c3f7b301cda6ac1ba9b31f113">getVPLegalizationStrategy</a> (const VPIntrinsic &amp;VPI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine how and whether the <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> <span class="doxyComputerOutput">VPI</span> shall be expanded. <a href="#a8c2dd03c3f7b301cda6ac1ba9b31f113">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae53f11eb819a6e1a1249ef582fb25010">VPExpansionDetails</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26419bc539a673ab5e42ce01e5c694ec">expandVectorPredication</a> (VPIntrinsic &amp;VPI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand llvm.vp. <a href="#a26419bc539a673ab5e42ce01e5c694ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9028bfa65760666da97c9effe3faa267">TTI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1af892ff2a9a41536c1544a17fc9c983">UsingTTIOverrides</a></td>
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


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CachingVPExpander() {#aaf7c6eba52a5555ce4c8695015bb4d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::CachingVPExpander (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a9f30d8251c1524af5380925febc3529c">anyExpandVPOverridesSet</a>, <a href="#a9028bfa65760666da97c9effe3faa267">TTI</a> and <a href="#a1af892ff2a9a41536c1544a17fc9c983">UsingTTIOverrides</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a98ae6eba06bb737a1dd3e3c4e1662e29">llvm::expandVectorPredicationIntrinsic</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertEVLToMask() {#a787f048d94a8f173da27cb792cff4758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::convertEVLToMask (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * EVLParam, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> ElemCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A bitmask that is true where the lane position is less-than <span class="doxyComputerOutput">EVLParam</span></p></dd>
</dl>


<p><span class="doxyComputerOutput">Builder</span> Used for instruction creation. <span class="doxyComputerOutput">VLParam</span> The explicit vector length parameter to test against the lane positions. <span class="doxyComputerOutput">ElemCount</span> Static (potentially scalable) number of vector elements.</p>


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae934d6e99e0516d606ae8e65ff6aed63">llvm::IRBuilderBase::CreateStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a40ed7274ff11f079e5b5eae34c818c51">llvm::IRBuilderBase::CreateVectorSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1fb6e8365dbf4ef3a7426ff3d531ff87">llvm::IRBuilderBase::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>.</p>


<p>Referenced by <a href="#ac965f2137199995cb31f57f71cc3b568">foldEVLIntoMask</a>.</p>

</div>
</div>

### discardEVLParameter() {#ad46652b66427679d9c221df6915019ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::discardEVLParameter (<a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; PI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>"Remove" the evl parameter of <span class="doxyComputerOutput">PI</span> by setting it to the static vector length of the operation.</p>


<p>Returns true if the evl (if any) was effectively changed.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a30ce03e0610ee1bd4741a602bca4aa49">llvm::VPIntrinsic::canIgnoreVectorLengthParam</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#aec5273476a8a080ea53c3a94ad70ed0b">llvm::VPIntrinsic::getStaticVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a5297bb63c49e91e5959ec20b638a8a45">llvm::VPIntrinsic::getVectorLengthParam</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a7d6e3b2cad50a3bd88b4d298a17cef24">llvm::VPIntrinsic::setVectorLengthParam</a>.</p>


<p>Referenced by <a href="#a26419bc539a673ab5e42ce01e5c694ec">expandVectorPredication</a> and <a href="#ac965f2137199995cb31f57f71cc3b568">foldEVLIntoMask</a>.</p>

</div>
</div>

### expandPredication() {#aee759d5807e7eb77e631717da4461426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredication (<a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; PI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Query TTI and expand the vector predication in <span class="doxyComputerOutput">P</span> accordingly.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae44006b91094939f6ea72655e8312504">llvm::IRBuilderBase::CreateFNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a3eba8b3e2e38c997d14bc2ee850be29a">expandPredicationInBinaryOperator</a>, <a href="#a5afd2ab39f4d739286d175f8babb8e6b">expandPredicationInComparison</a>, <a href="#a1f1f1359a986d8e4d1b107ae4c524a32">expandPredicationInMemoryIntrinsic</a>, <a href="#a2153c46ea6d560ce96b6ad7e822d2c70">expandPredicationInReduction</a>, <a href="#a5cd88dbe6fb8f2ddbd621296ca4ebd5f">expandPredicationToCastIntrinsic</a>, <a href="#a62f9944dba24143c8954964d7dff45b8">expandPredicationToFPCall</a>, <a href="#ad2529fdcdfd78c5eccd6079fc3c74ad3">expandPredicationToIntCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#ade68b66f49b863f50323b3e2e8a60fdf">llvm::VPIntrinsic::getConstrainedIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a0041f4dfa269c9da654f0e1d020da6ef">llvm::VPIntrinsic::getFunctionalIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#afdf77acc5c4eeed0da64226ffeb5389f">llvm::VPIntrinsic::getFunctionalOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcastintrinsic/#aa2c13077e5a0bbf474c5ba56fdd4bd36">llvm::VPCastIntrinsic::isVPCast</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a56afeeb4fb49342e6cbde202cacabdfc">replaceOperation</a>.</p>


<p>Referenced by <a href="#a26419bc539a673ab5e42ce01e5c694ec">expandVectorPredication</a>.</p>

</div>
</div>

### expandPredicationInBinaryOperator() {#a3eba8b3e2e38c997d14bc2ee850be29a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInBinaryOperator (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; PI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower this VP binary operator to a unpredicated binary operator.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a30ce03e0610ee1bd4741a602bca4aa49">llvm::VPIntrinsic::canIgnoreVectorLengthParam</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#afdf77acc5c4eeed0da64226ffeb5389f">llvm::VPIntrinsic::getFunctionalOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#ae3a6cf3016819a83fe114e42db5df7f7">llvm::VPIntrinsic::getMaskParam</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#ac926076ad2d59de82321e2924a4186bd">getSafeDivisor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a5c4f186bcff949009f515aaf53c681c9">isAllTrueMask</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#aabd8a84d1694dda293cbdce6bde5fc11">maySpeculateLanes</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a56afeeb4fb49342e6cbde202cacabdfc">replaceOperation</a>.</p>


<p>Referenced by <a href="#aee759d5807e7eb77e631717da4461426">expandPredication</a>.</p>

</div>
</div>

### expandPredicationInComparison() {#a5afd2ab39f4d739286d175f8babb8e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInComparison (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/vpcmpintrinsic">VPCmpIntrinsic</a> &amp; PI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower this VP comparison to a call to an unpredicated comparison.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a30ce03e0610ee1bd4741a602bca4aa49">llvm::VPIntrinsic::canIgnoreVectorLengthParam</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a843d43d070f0b1c6a133403edce488ef">llvm::IRBuilderBase::CreateCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#afdf77acc5c4eeed0da64226ffeb5389f">llvm::VPIntrinsic::getFunctionalOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcmpintrinsic/#abd4835d4ce4a46f73cc1a219b7b410b4">llvm::VPCmpIntrinsic::getPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#aabd8a84d1694dda293cbdce6bde5fc11">maySpeculateLanes</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a56afeeb4fb49342e6cbde202cacabdfc">replaceOperation</a>.</p>


<p>Referenced by <a href="#aee759d5807e7eb77e631717da4461426">expandPredication</a>.</p>

</div>
</div>

### expandPredicationInMemoryIntrinsic() {#a1f1f1359a986d8e4d1b107ae4c524a32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInMemoryIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower this VP memory operation to a non-VP intrinsic.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a30ce03e0610ee1bd4741a602bca4aa49">llvm::VPIntrinsic::canIgnoreVectorLengthParam</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#afa922043d31aa2d3410fe0be8791b795">llvm::IRBuilderBase::CreateMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a483f68557374e8fc58f8a294e7f1268e">llvm::IRBuilderBase::CreateMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aee07a8623893cdad858a3b5f77354375">llvm::IRBuilderBase::CreateMaskedScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aad07e3e0fa03f6c780e13d924325d8d0">llvm::IRBuilderBase::CreateMaskedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#ae3a6cf3016819a83fe114e42db5df7f7">llvm::VPIntrinsic::getMaskParam</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#acc801d404cca596b586df87ab8f19897">llvm::VPIntrinsic::getMemoryDataParam</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#ad2dbe79feecaee785999f4958f39fbb0">llvm::VPIntrinsic::getMemoryPointerParam</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#ae3a0c2dd2caff6d81180f9724a6d369e">llvm::VPIntrinsic::getPointerAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a5c4f186bcff949009f515aaf53c681c9">isAllTrueMask</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a56afeeb4fb49342e6cbde202cacabdfc">replaceOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2b1268b642e9bf4373b6fb31c482c9ca">llvm::LoadInst::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a55195fa18cf783fe74de0cced1ca6eb3">llvm::StoreInst::setAlignment</a> and <a href="/web-llvm/docs/api/structs/llvm/maybealign/#a06846474be3ab85f8d30c388faf3b116">llvm::MaybeAlign::valueOrOne</a>.</p>


<p>Referenced by <a href="#aee759d5807e7eb77e631717da4461426">expandPredication</a>.</p>

</div>
</div>

### expandPredicationInReduction() {#a2153c46ea6d560ce96b6ad7e822d2c70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInReduction (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/vpreductionintrinsic">VPReductionIntrinsic</a> &amp; PI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower this VP reduction to a call to an unpredicated reduction intrinsic.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a30ce03e0610ee1bd4741a602bca4aa49">llvm::VPIntrinsic::canIgnoreVectorLengthParam</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7e0a0c76340ba1fc52863f538f3e703d">llvm::IRBuilderBase::CreateBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a09180737dfe9015739f3dedfe7da2883">llvm::IRBuilderBase::CreateFAddReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ade4097032aebcd4971b74b06364f6f88">llvm::IRBuilderBase::CreateFMulReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9ac45fd1485e6735d83544e54fb52d4b">llvm::IRBuilderBase::CreateUnaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a40ed7274ff11f079e5b5eae34c818c51">llvm::IRBuilderBase::CreateVectorSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a393cf3541b511ac08c71fc9cca0920f7">llvm::getArithmeticReductionInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a0041f4dfa269c9da654f0e1d020da6ef">llvm::VPIntrinsic::getFunctionalIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#ae3a6cf3016819a83fe114e42db5df7f7">llvm::VPIntrinsic::getMaskParam</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e4b6546560e7fb6d37f6318d3236bb9">llvm::getMinMaxReductionIntrinsicOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandvectorpredication-cpp-/#a59db4883933b9a437c397b1db4d32c91">anonymous{ExpandVectorPredication.cpp}::getNeutralReductionElement</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionintrinsic/#acb13ac87c2c73eafc6644b50c5211898">llvm::VPReductionIntrinsic::getStartParamPos</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionintrinsic/#ae49c998aefe5952abfc297015275af17">llvm::VPReductionIntrinsic::getVectorParamPos</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a5c4f186bcff949009f515aaf53c681c9">isAllTrueMask</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#aabd8a84d1694dda293cbdce6bde5fc11">maySpeculateLanes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a175f1f53cc9c3619505ffbd13aca087f">Reduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a56afeeb4fb49342e6cbde202cacabdfc">replaceOperation</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a6be7df7547021dc38ef1d55fc8fb540f">transferDecorations</a>.</p>


<p>Referenced by <a href="#aee759d5807e7eb77e631717da4461426">expandPredication</a>.</p>

</div>
</div>

### expandPredicationToCastIntrinsic() {#a5cd88dbe6fb8f2ddbd621296ca4ebd5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToCastIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower this VP cast operation to a non-VP intrinsic.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5b7f6dddc76bf7954b8df6abbd974436">llvm::IRBuilderBase::CreateCast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a434d6eb9c691ae0cc5f59b5538927594">llvm::VPIntrinsic::getFunctionalOpcodeForVP</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a27997849d8982bf226891024fd68daee">llvm::Instruction::isCast</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a56afeeb4fb49342e6cbde202cacabdfc">replaceOperation</a>.</p>


<p>Referenced by <a href="#aee759d5807e7eb77e631717da4461426">expandPredication</a>.</p>

</div>
</div>

### expandPredicationToFPCall() {#a62f9944dba24143c8954964d7dff45b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToFPCall (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; PI, unsigned UnpredicatedIntrinsicID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower this VP fp call to a unpredicated fp call.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a30ce03e0610ee1bd4741a602bca4aa49">llvm::VPIntrinsic::canIgnoreVectorLengthParam</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a48ebbc1e9c11c52c99229d706238ea8a">llvm::IRBuilderBase::CreateConstrainedFPCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a7ff2d64dca44822331bda0a0975ebd6d">llvm::Intrinsic::isConstrainedFPIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#aabd8a84d1694dda293cbdce6bde5fc11">maySpeculateLanes</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a56afeeb4fb49342e6cbde202cacabdfc">replaceOperation</a>.</p>


<p>Referenced by <a href="#aee759d5807e7eb77e631717da4461426">expandPredication</a>.</p>

</div>
</div>

### expandPredicationToIntCall() {#ad2529fdcdfd78c5eccd6079fc3c74ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToIntCall (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; PI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower this VP int call to a unpredicated int call.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a0041f4dfa269c9da654f0e1d020da6ef">llvm::VPIntrinsic::getFunctionalIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a56afeeb4fb49342e6cbde202cacabdfc">replaceOperation</a>.</p>


<p>Referenced by <a href="#aee759d5807e7eb77e631717da4461426">expandPredication</a>.</p>

</div>
</div>

### expandVectorPredication() {#a26419bc539a673ab5e42ce01e5c694ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPExpansionDetails anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandVectorPredication (<a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand llvm.vp.</p>


<ul class="doxyList ">
<li>intrinsics as requested by <span class="doxyComputerOutput">TTI</span>. Returns the details of the expansion.</li>
</ul>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/vplegalization/#abf988827c40fdf90a1e08a8e2cddea0da2a58508bab01c3fba0c3c912ed82e89d">llvm::TargetTransformInfo::VPLegalization::Convert</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/vplegalization/#abf988827c40fdf90a1e08a8e2cddea0dad89a9e5c9cb303fe1dedf3a40d899015">llvm::TargetTransformInfo::VPLegalization::Discard</a>, <a href="#ad46652b66427679d9c221df6915019ca">discardEVLParameter</a>, <a href="#aee759d5807e7eb77e631717da4461426">expandPredication</a>, <a href="#ac965f2137199995cb31f57f71cc3b568">foldEVLIntoMask</a>, <a href="#a8c2dd03c3f7b301cda6ac1ba9b31f113">getVPLegalizationStrategy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae53f11eb819a6e1a1249ef582fb25010a5adbe9a4214c6ce7438a7afa6c8544ed">llvm::IntrinsicReplaced</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae53f11eb819a6e1a1249ef582fb25010a237d5181e52c3a0d77bd78abe497ba20">llvm::IntrinsicUnchanged</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae53f11eb819a6e1a1249ef582fb25010a351b040c4d91b15ed79bdc24968a9283">llvm::IntrinsicUpdated</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/vplegalization/#abf988827c40fdf90a1e08a8e2cddea0da9e7fcc009995c1a76735da3700665aaa">llvm::TargetTransformInfo::VPLegalization::Legal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-expandvectorpredication-cpp-/#aedba47828740c9315142ae92e6e901ae">anonymous{ExpandVectorPredication.cpp}::sanitizeStrategy</a>.</p>

</div>
</div>

### foldEVLIntoMask() {#ac965f2137199995cb31f57f71cc3b568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, bool &gt; anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::foldEVLIntoMask (<a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If needed, folds the EVL in the mask operand and discards the EVL parameter.</p>


<p>Returns a pair of the value of the intrinsic after the change (if any) and whether the mask was actually folded.</p>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a30ce03e0610ee1bd4741a602bca4aa49">llvm::VPIntrinsic::canIgnoreVectorLengthParam</a>, <a href="#a787f048d94a8f173da27cb792cff4758">convertEVLToMask</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ad46652b66427679d9c221df6915019ca">discardEVLParameter</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#ae3a6cf3016819a83fe114e42db5df7f7">llvm::VPIntrinsic::getMaskParam</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#aec5273476a8a080ea53c3a94ad70ed0b">llvm::VPIntrinsic::getStaticVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a5297bb63c49e91e5959ec20b638a8a45">llvm::VPIntrinsic::getVectorLengthParam</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a36ec592acc6de041c35f8f192d5d572d">llvm::VPIntrinsic::setMaskParam</a>.</p>


<p>Referenced by <a href="#a26419bc539a673ab5e42ce01e5c694ec">expandVectorPredication</a>.</p>

</div>
</div>

### getVPLegalizationStrategy() {#a8c2dd03c3f7b301cda6ac1ba9b31f113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPLegalization anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::getVPLegalizationStrategy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine how and whether the <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> <span class="doxyComputerOutput">VPI</span> shall be expanded.</p>


<p>This overrides TTI with the cl::opts listed at the top of this file.</p>


<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a44e0de2bb6a2154f5c6dbe2f8c47243c">EVLTransformOverride</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a268e4e732c0e3eb76cc3b297bbe1e98a">MaskTransformOverride</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a1811ad3ea8f5c8a6db679268f78b8d48">parseOverrideOption</a>, <a href="#a9028bfa65760666da97c9effe3faa267">TTI</a> and <a href="#a1af892ff2a9a41536c1544a17fc9c983">UsingTTIOverrides</a>.</p>


<p>Referenced by <a href="#a26419bc539a673ab5e42ce01e5c694ec">expandVectorPredication</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### TTI {#a9028bfa65760666da97c9effe3faa267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo&amp; anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>Referenced by <a href="#aaf7c6eba52a5555ce4c8695015bb4d8a">CachingVPExpander</a> and <a href="#a8c2dd03c3f7b301cda6ac1ba9b31f113">getVPLegalizationStrategy</a>.</p>

</div>
</div>

### UsingTTIOverrides {#a1af892ff2a9a41536c1544a17fc9c983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::UsingTTIOverrides</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>Referenced by <a href="#aaf7c6eba52a5555ce4c8695015bb4d8a">CachingVPExpander</a> and <a href="#a8c2dd03c3f7b301cda6ac1ba9b31f113">getVPLegalizationStrategy</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
