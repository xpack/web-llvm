---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/binaryopintrinsic
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BinaryOpIntrinsic` Class

<p>This class represents an intrinsic that is based on a binary operation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BinaryOpIntrinsic { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper class for inspecting calls to intrinsic functions. <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/saturatinginst">SaturatingInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a saturating add/sub intrinsic. <a href="/web-llvm/docs/api/classes/llvm/saturatinginst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/withoverflowinst">WithOverflowInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an op.with.overflow intrinsic. <a href="/web-llvm/docs/api/classes/llvm/withoverflowinst/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd530ffa05240e0728bf85169dc7abcc">getLHS</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0583d2d049d59cf53ccfd2b6f4e53c87">getRHS</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa73e62aac1753cb7b3c3aaccef3df8b1">getBinaryOp</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the binary operation underlying the intrinsic. <a href="#aa73e62aac1753cb7b3c3aaccef3df8b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a814f3097eebe0236748fcc2ab5ce59d5">isSigned</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the intrinsic is signed or unsigned. <a href="#a814f3097eebe0236748fcc2ab5ce59d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8c92c02ddf72337cdd32207498e731">getNoWrapKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns one of OBO::NoSignedWrap or OBO::NoUnsignedWrap. <a href="#a3f8c92c02ddf72337cdd32207498e731">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa07c7ccb1d78ce5d4421b4eeac991462">classof</a> (const IntrinsicInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0656f24362540ee59056686d85fde324">classof</a> (const Value *V)</td>
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

<p>This class represents an intrinsic that is based on a binary operation.</p>


<p>This includes op.with.overflow and saturating add/sub intrinsics.</p>


<p>Definition at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getBinaryOp() {#aa73e62aac1753cb7b3c3aaccef3df8b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction::BinaryOps BinaryOpIntrinsic::getBinaryOp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the binary operation underlying the intrinsic.</p>

<p>Declaration at line 917 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#acb6e73547764d0338afa32e54ad785cf">getValueFromOverflowCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a25e3db50d3aa8a3fa245e3c2d3197d7a">processOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a52da671999cb61370bfe5c7e9fee966f">willNotOverflow</a>.</p>

</div>
</div>

### getLHS() {#abd530ffa05240e0728bf85169dc7abcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::BinaryOpIntrinsic::getLHS ()</td>
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



<p>Definition at line 913 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#acb6e73547764d0338afa32e54ad785cf">getValueFromOverflowCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a25e3db50d3aa8a3fa245e3c2d3197d7a">processOverflowIntrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### getNoWrapKind() {#a3f8c92c02ddf72337cdd32207498e731}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned BinaryOpIntrinsic::getNoWrapKind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns one of OBO::NoSignedWrap or OBO::NoUnsignedWrap.</p>

<p>Declaration at line 923 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="#a814f3097eebe0236748fcc2ab5ce59d5">isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a1d0f9e84fb5d277edd8530e7afbb674aac3172f238278728e355fc9a87c439dd5">llvm::OverflowingBinaryOperator::NoSignedWrap</a> and <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a1d0f9e84fb5d277edd8530e7afbb674aa7d34304df400cdb020e71e182ac06cb7">llvm::OverflowingBinaryOperator::NoUnsignedWrap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#acb6e73547764d0338afa32e54ad785cf">getValueFromOverflowCondition</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a52da671999cb61370bfe5c7e9fee966f">willNotOverflow</a>.</p>

</div>
</div>

### getRHS() {#a0583d2d049d59cf53ccfd2b6f4e53c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::BinaryOpIntrinsic::getRHS ()</td>
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



<p>Definition at line 914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#acb6e73547764d0338afa32e54ad785cf">getValueFromOverflowCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a25e3db50d3aa8a3fa245e3c2d3197d7a">processOverflowIntrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### isSigned() {#a814f3097eebe0236748fcc2ab5ce59d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BinaryOpIntrinsic::isSigned ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the intrinsic is signed or unsigned.</p>

<p>Declaration at line 920 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 822 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="#a3f8c92c02ddf72337cdd32207498e731">getNoWrapKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a25e3db50d3aa8a3fa245e3c2d3197d7a">processOverflowIntrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aa07c7ccb1d78ce5d4421b4eeac991462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BinaryOpIntrinsic::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * I)</td>
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



<p>Definition at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#afa22d4a80efeabdb45e6f1bdbbb24850">llvm::IntrinsicInst::IntrinsicInst</a>.</p>


<p>Referenced by <a href="#a0656f24362540ee59056686d85fde324">classof</a>.</p>

</div>
</div>

### classof() {#a0656f24362540ee59056686d85fde324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BinaryOpIntrinsic::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 909 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aa07c7ccb1d78ce5d4421b4eeac991462">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
