---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/fpmathoperator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FPMathOperator` Class Reference

<p>Utility class for floating point operations which can have information about relaxed accuracy requirements attached to them. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FPMathOperator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/operator">Operator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a utility class that provides an abstraction for the common functionality between Instructions and ConstantExprs. <a href="/web-llvm/docs/api/classes/llvm/operator/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87273cb892a8182f137567e6b631695e">Instruction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3e20e19cc93a7cf75fbe6b4b27a728">isFast</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this operation allows all non-strict floating-point transforms. <a href="#a0f3e20e19cc93a7cf75fbe6b4b27a728">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e4fac852204510c3218d42582b64e3f">hasAllowReassoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this operation may be simplified with reassociative transforms. <a href="#a0e4fac852204510c3218d42582b64e3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81877288bdf18216272d7724ecb894c8">hasNoNaNs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this operation's arguments and results are assumed not-NaN. <a href="#a81877288bdf18216272d7724ecb894c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6d93d933e7e2e0d11075507102317d7">hasNoInfs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this operation's arguments and results are assumed not-infinite. <a href="#ae6d93d933e7e2e0d11075507102317d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac25b138a0eb2441346d23183e7ee964f">hasNoSignedZeros</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this operation can ignore the sign of zero. <a href="#ac25b138a0eb2441346d23183e7ee964f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cfe8ef5bdce7cb9675d9b948424f5dc">hasAllowReciprocal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this operation can use reciprocal multiply instead of division. <a href="#a8cfe8ef5bdce7cb9675d9b948424f5dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc3e04036467d5c54b04ca43f1ae4e35">hasAllowContract</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this operation can be floating-point contracted (FMA). <a href="#adc3e04036467d5c54b04ca43f1ae4e35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af033630a6f4a852c95625648b3f893c6">hasApproxFunc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this operation allows approximations of math library functions or intrinsics. <a href="#af033630a6f4a852c95625648b3f893c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8be4fec4d0b6071fb7d7520364fd5378">getFastMathFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for getting all the fast-math flags. <a href="#a8be4fec4d0b6071fb7d7520364fd5378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af50d863c0e5a39ec42b567a9ea58e351">getFPAccuracy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the maximum error permitted by this operation in ULPs. <a href="#af50d863c0e5a39ec42b567a9ea58e351">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a006875501bddb30499b08b115083aff1">setFast</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'Fast' means all bits are set. <a href="#a006875501bddb30499b08b115083aff1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a448a863693fbeac9486dd49713b773f0">setHasAllowReassoc</a> (bool B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbb9d4b966f53a34ee17986993f4b317">setHasNoNaNs</a> (bool B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1224911d7d8eab7c68c2febaa5a98d04">setHasNoInfs</a> (bool B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17dec21db6fdceb736f7f53970992e19">setHasNoSignedZeros</a> (bool B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25cadb86a4174a7c023b304e65668609">setHasAllowReciprocal</a> (bool B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad41794b16fd677217f594c9347680ad6">setHasAllowContract</a> (bool B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6c2d92a9aacf511ff9ad1cbf3cba5b8">setHasApproxFunc</a> (bool B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1296e1f5eb531ccd4aacfb47283b877b">setFastMathFlags</a> (FastMathFlags FMF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for setting multiple fast-math flags. <a href="#a1296e1f5eb531ccd4aacfb47283b877b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dcfc55bb02a6b964b4080436fff9aa2">copyFastMathFlags</a> (FastMathFlags FMF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for copying all fast-math flags. <a href="#a3dcfc55bb02a6b964b4080436fff9aa2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4f7d12f6bda5a60f868f3ec8be99f9c">isSupportedFloatingPointType</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">Ty</span> is a supported floating-point type for phi, select, or call FPMathOperators. <a href="#ac4f7d12f6bda5a60f868f3ec8be99f9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f8f2d17037f812565b50d54625b062d">classof</a> (const Value *V)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47b566c12aa127e4fb21193170ef8714">isComposedOfHomogeneousFloatingPointTypes</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">Ty</span> is composed of a single kind of float-poing type (possibly repeated within an aggregate). <a href="#a47b566c12aa127e4fb21193170ef8714">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Utility class for floating point operations which can have information about relaxed accuracy requirements attached to them.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Instruction {#a87273cb892a8182f137567e6b631695e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFastMathFlags() {#a8be4fec4d0b6071fb7d7520364fd5378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags llvm::FPMathOperator::getFastMathFlags ()</td>
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

<p>Convenience function for getting all the fast-math flags.</p>

<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a21e38886795ed32ec28d4eb5dc92b6a4">llvm::Value::SubclassOptionalData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a9bdebe594005618b27255ea3ea2d2cdb">llvm::VPBuilder::createScalarIVSteps</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae534b46b7607eb604ddd8c66baa8d2d1">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#aa22a44bbc6646770b4bd139ca4fe2d94">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSelectInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae42afee90ff90eb3b8fa78ad91d8858b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSqrt</a>.</p>

</div>
</div>

### getFPAccuracy() {#af50d863c0e5a39ec42b567a9ea58e351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float FPMathOperator::getFPAccuracy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the maximum error permitted by this operation in ULPs.</p>


<p>An accuracy of 0.0 means that the operation should be performed with the default precision.</p>


<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>, definition at line 2682 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a8269fab998356ea27a76ad45bd6cc8fe">llvm::APFloat::convertToFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a472408c33fff86419b4ff8fb2e343a64">canContractSqrtToRsq</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a1969a1585363ca3069e708b24d19fda4">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::canOptimizeWithRsq</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae534b46b7607eb604ddd8c66baa8d2d1">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitFDiv</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae42afee90ff90eb3b8fa78ad91d8858b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSqrt</a>.</p>

</div>
</div>

### hasAllowContract() {#adc3e04036467d5c54b04ca43f1ae4e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FPMathOperator::hasAllowContract ()</td>
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

<p>Test if this operation can be floating-point contracted (FMA).</p>

<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aa39ea4202b84ac863d1758d9d09c332eb">llvm::FastMathFlags::AllowContract</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a21e38886795ed32ec28d4eb5dc92b6a4">llvm::Value::SubclassOptionalData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags/#a2235a7b644c7eb6f9f405df4ece486a2">llvm::SDNodeFlags::copyFMF</a>.</p>

</div>
</div>

### hasAllowReassoc() {#a0e4fac852204510c3218d42582b64e3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FPMathOperator::hasAllowReassoc ()</td>
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

<p>Test if this operation may be simplified with reassociative transforms.</p>

<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aa0dcb723027d8e065575a8ebbd96f390e">llvm::FastMathFlags::AllowReassoc</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a21e38886795ed32ec28d4eb5dc92b6a4">llvm::Value::SubclassOptionalData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags/#a2235a7b644c7eb6f9f405df4ece486a2">llvm::SDNodeFlags::copyFMF</a>.</p>

</div>
</div>

### hasAllowReciprocal() {#a8cfe8ef5bdce7cb9675d9b948424f5dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FPMathOperator::hasAllowReciprocal ()</td>
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

<p>Test if this operation can use reciprocal multiply instead of division.</p>

<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aacc34bbc1654fb098a8a9a550eaeabfd1">llvm::FastMathFlags::AllowReciprocal</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a21e38886795ed32ec28d4eb5dc92b6a4">llvm::Value::SubclassOptionalData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags/#a2235a7b644c7eb6f9f405df4ece486a2">llvm::SDNodeFlags::copyFMF</a>.</p>

</div>
</div>

### hasApproxFunc() {#af033630a6f4a852c95625648b3f893c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FPMathOperator::hasApproxFunc ()</td>
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

<p>Test if this operation allows approximations of math library functions or intrinsics.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aa3331f3726d22d6291aa71c17597ee43d">llvm::FastMathFlags::ApproxFunc</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a21e38886795ed32ec28d4eb5dc92b6a4">llvm::Value::SubclassOptionalData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a472408c33fff86419b4ff8fb2e343a64">canContractSqrtToRsq</a>, <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags/#a2235a7b644c7eb6f9f405df4ece486a2">llvm::SDNodeFlags::copyFMF</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a3a1b147c616566686d22c1a730f747f9">llvm::AMDGPULibCalls::isUnsafeFiniteOnlyMath</a>.</p>

</div>
</div>

### hasNoInfs() {#ae6d93d933e7e2e0d11075507102317d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FPMathOperator::hasNoInfs ()</td>
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

<p>Test if this operation's arguments and results are assumed not-infinite.</p>

<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aa94d85382e80e8c29ee348dd249e6c252">llvm::FastMathFlags::NoInfs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a21e38886795ed32ec28d4eb5dc92b6a4">llvm::Value::SubclassOptionalData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags/#a2235a7b644c7eb6f9f405df4ece486a2">llvm::SDNodeFlags::copyFMF</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a3a1b147c616566686d22c1a730f747f9">llvm::AMDGPULibCalls::isUnsafeFiniteOnlyMath</a>.</p>

</div>
</div>

### hasNoNaNs() {#a81877288bdf18216272d7724ecb894c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FPMathOperator::hasNoNaNs ()</td>
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

<p>Test if this operation's arguments and results are assumed not-NaN.</p>

<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aa7444c7e9d01093ec21714f3d0557e593">llvm::FastMathFlags::NoNaNs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a21e38886795ed32ec28d4eb5dc92b6a4">llvm::Value::SubclassOptionalData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags/#a2235a7b644c7eb6f9f405df4ece486a2">llvm::SDNodeFlags::copyFMF</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a3a1b147c616566686d22c1a730f747f9">llvm::AMDGPULibCalls::isUnsafeFiniteOnlyMath</a>.</p>

</div>
</div>

### hasNoSignedZeros() {#ac25b138a0eb2441346d23183e7ee964f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FPMathOperator::hasNoSignedZeros ()</td>
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

<p>Test if this operation can ignore the sign of zero.</p>

<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aa6bd663e923d3b794eaac9f5b29224776">llvm::FastMathFlags::NoSignedZeros</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a21e38886795ed32ec28d4eb5dc92b6a4">llvm::Value::SubclassOptionalData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags/#a2235a7b644c7eb6f9f405df4ece486a2">llvm::SDNodeFlags::copyFMF</a>.</p>

</div>
</div>

### isFast() {#a0f3e20e19cc93a7cf75fbe6b4b27a728}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FPMathOperator::isFast ()</td>
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

<p>Test if this operation allows all non-strict floating-point transforms.</p>

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aa39ea4202b84ac863d1758d9d09c332eb">llvm::FastMathFlags::AllowContract</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aa0dcb723027d8e065575a8ebbd96f390e">llvm::FastMathFlags::AllowReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aacc34bbc1654fb098a8a9a550eaeabfd1">llvm::FastMathFlags::AllowReciprocal</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aa3331f3726d22d6291aa71c17597ee43d">llvm::FastMathFlags::ApproxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aa94d85382e80e8c29ee348dd249e6c252">llvm::FastMathFlags::NoInfs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aa7444c7e9d01093ec21714f3d0557e593">llvm::FastMathFlags::NoNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#aecfe0e0af01be66fdc3e9097d14e2e5aa6bd663e923d3b794eaac9f5b29224776">llvm::FastMathFlags::NoSignedZeros</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a21e38886795ed32ec28d4eb5dc92b6a4">llvm::Value::SubclassOptionalData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#af57024f93dc2316eb9cc3751f0ae766e">llvm::AMDGPULibCalls::isUnsafeMath</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### copyFastMathFlags() {#a3dcfc55bb02a6b964b4080436fff9aa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FPMathOperator::copyFastMathFlags (<a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF)</td>
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

<p>Convenience function for copying all fast-math flags.</p>


<p>All values in FMF are transferred to this operator.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

### setFast() {#a006875501bddb30499b08b115083aff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FPMathOperator::setFast (bool B)</td>
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

<p>'Fast' means all bits are set.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

### setFastMathFlags() {#a1296e1f5eb531ccd4aacfb47283b877b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FPMathOperator::setFastMathFlags (<a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF)</td>
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

<p>Convenience function for setting multiple fast-math flags.</p>


<p>FMF is a mask of the bits to set.</p>


<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

### setHasAllowContract() {#ad41794b16fd677217f594c9347680ad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FPMathOperator::setHasAllowContract (bool B)</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

### setHasAllowReassoc() {#a448a863693fbeac9486dd49713b773f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FPMathOperator::setHasAllowReassoc (bool B)</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

### setHasAllowReciprocal() {#a25cadb86a4174a7c023b304e65668609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FPMathOperator::setHasAllowReciprocal (bool B)</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

### setHasApproxFunc() {#af6c2d92a9aacf511ff9ad1cbf3cba5b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FPMathOperator::setHasApproxFunc (bool B)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

### setHasNoInfs() {#a1224911d7d8eab7c68c2febaa5a98d04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FPMathOperator::setHasNoInfs (bool B)</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

### setHasNoNaNs() {#adbb9d4b966f53a34ee17986993f4b317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FPMathOperator::setHasNoNaNs (bool B)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

### setHasNoSignedZeros() {#a17dec21db6fdceb736f7f53970992e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FPMathOperator::setHasNoSignedZeros (bool B)</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a2f8f2d17037f812565b50d54625b062d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FPMathOperator::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ac4f7d12f6bda5a60f868f3ec8be99f9c">isSupportedFloatingPointType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator/#abfc63b4cdc54b1f13efc6767bdfb9b5b">llvm::sandboxir::FPMathOperator::classof</a>.</p>

</div>
</div>

### isSupportedFloatingPointType() {#ac4f7d12f6bda5a60f868f3ec8be99f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FPMathOperator::isSupportedFloatingPointType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">Ty</span> is a supported floating-point type for phi, select, or call FPMathOperators.</p>

<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>Referenced by <a href="#a2f8f2d17037f812565b50d54625b062d">classof</a>, <a href="/web-llvm/docs/api/namespaces/llvm/attributefuncs/#a682611c4ec5c544fb17317b40e903a52">llvm::AttributeFuncs::isNoFPClassCompatibleType</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/fpmathoperator/#a6d09b44ecfea15d968d0180b029915f9">llvm::sandboxir::FPMathOperator::isSupportedFloatingPointType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### isComposedOfHomogeneousFloatingPointTypes() {#a47b566c12aa127e4fb21193170ef8714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FPMathOperator::isComposedOfHomogeneousFloatingPointTypes (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">Ty</span> is composed of a single kind of float-poing type (possibly repeated within an aggregate).</p>

<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
