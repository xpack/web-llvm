---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-expandvectorpredication-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{ExpandVectorPredication.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{ExpandVectorPredication.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander">CachingVPExpander</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59db4883933b9a437c397b1db4d32c91">getNeutralReductionElement</a> (const VPReductionIntrinsic &amp;VPI, Type *EltTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedba47828740c9315142ae92e6e901ae">sanitizeStrategy</a> (VPIntrinsic &amp;VPI, VPLegalization &amp;LegalizeStrat)</td>
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

## Functions

### getNeutralReductionElement() {#a59db4883933b9a437c397b1db4d32c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{ExpandVectorPredication.cpp}::getNeutralReductionElement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpreductionintrinsic">VPReductionIntrinsic</a> &amp; VPI, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * EltTy)</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9a167f91db810097d281b1ed627f4575">llvm::Instruction::getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a0041f4dfa269c9da654f0e1d020da6ef">llvm::VPIntrinsic::getFunctionalIntrinsicID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a31bf36444fc26b97b06effa1d8536efb">llvm::getReductionIdentity</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a2153c46ea6d560ce96b6ad7e822d2c70">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInReduction</a>.</p>

</div>
</div>

### sanitizeStrategy() {#aedba47828740c9315142ae92e6e901ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ExpandVectorPredication.cpp}::sanitizeStrategy (<a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPI, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a8bbe0bdae41c88a50d5776a8b6bd9d5c">VPLegalization</a> &amp; LegalizeStrat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/vplegalization/#abf988827c40fdf90a1e08a8e2cddea0da2a58508bab01c3fba0c3c912ed82e89d">llvm::TargetTransformInfo::VPLegalization::Convert</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/vplegalization/#abf988827c40fdf90a1e08a8e2cddea0dad89a9e5c9cb303fe1dedf3a40d899015">llvm::TargetTransformInfo::VPLegalization::Discard</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/vplegalization/#a94e1d5306640457b340c5d5045fc3532">llvm::TargetTransformInfo::VPLegalization::EVLParamStrategy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#aabd8a84d1694dda293cbdce6bde5fc11">maySpeculateLanes</a> and <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/vplegalization/#a077db45fab76ac717888ddd702b6f9bf">llvm::TargetTransformInfo::VPLegalization::OpStrategy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a26419bc539a673ab5e42ce01e5c694ec">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandVectorPredication</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
