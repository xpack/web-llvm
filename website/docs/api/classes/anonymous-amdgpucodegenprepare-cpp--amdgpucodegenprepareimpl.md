---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AMDGPUCodeGenPrepareImpl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor&lt;SubClass, RetTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for instruction visitors. <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9bb93f26a50af2dbf9faa24fa3555a">AMDGPUCodeGenPrepareImpl</a> (Function &amp;F, const AMDGPUTargetMachine &amp;TM, const TargetLibraryInfo *TLI, AssumptionCache *AC, const DominatorTree *DT, const UniformityInfo &amp;UA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20b2cf2d81b88d6e6c40a523245424ea">getSqrtF32</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45499cf71e7324771b2faa3921da99bb">getLdexpF32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a473885e550a15e1490b4de7f4ebd245f">canBreakPHINode</a> (const PHINode &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800dbbf6469dc037cd9eb5305ff554a9">getBaseElementBitWidth</a> (const Type *T) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copies exact/nsw/nuw flags (if any) from binary operation <span class="doxyComputerOutput">I</span> to binary operation <span class="doxyComputerOutput">V</span>. <a href="#a800dbbf6469dc037cd9eb5305ff554a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5de925ed31e50af1df0f4d5e26a50c6">getI32Ty</a> (IRBuilder&lt;&gt; &amp;B, const Type *T) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac434cec8bb472f27b985344dfd19b8e9">isSigned</a> (const BinaryOperator &amp;I) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d048c35e76be8217f7a9fa629bbb476">isSigned</a> (const SelectInst &amp;I) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a> (const Type *T) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeababc2d5ffb872b7ef9f71fe5613b3">isLegalFloatingTy</a> (const Type *T) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">T</span> is a legal scalar floating point type. <a href="#aaeababc2d5ffb872b7ef9f71fe5613b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownfpclass">KnownFPClass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a725665cbb013d5d85e6ed77a560a65ea">computeKnownFPClass</a> (const Value *V, FPClassTest Interested, const Instruction *CtxI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrapper to pass all the arguments to computeKnownFPClass. <a href="#a725665cbb013d5d85e6ed77a560a65ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e5cad6b96b065fe2b8f1df5fcfb82c">canIgnoreDenormalInput</a> (const Value *V, const Instruction *CtxI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5cda76a7708fa48ddc1de837c4fe5e7">promoteUniformOpToI32</a> (BinaryOperator &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Promotes uniform binary operation <span class="doxyComputerOutput">I</span> to equivalent 32 bit binary operation. <a href="#af5cda76a7708fa48ddc1de837c4fe5e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad768a9cd1293081ea1b03af6a146451a">promoteUniformOpToI32</a> (ICmpInst &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Promotes uniform 'icmp' operation <span class="doxyComputerOutput">I</span> to 32 bit 'icmp' operation. <a href="#ad768a9cd1293081ea1b03af6a146451a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af60d41958d088dadfdca762d75f23e8d">promoteUniformOpToI32</a> (SelectInst &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Promotes uniform 'select' operation <span class="doxyComputerOutput">I</span> to 32 bit 'select' operation. <a href="#af60d41958d088dadfdca762d75f23e8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f14d9907d63254543fb2375d87b623">promoteUniformBitreverseToI32</a> (IntrinsicInst &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Promotes uniform 'bitreverse' intrinsic <span class="doxyComputerOutput">I</span> to 32 bit 'bitreverse' intrinsic. <a href="#ae7f14d9907d63254543fb2375d87b623">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac08070db79359ea85bcff1e4fca790c9">numBitsUnsigned</a> (Value *Op) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c12020d1ecaa1b55d62889b342f4f09">numBitsSigned</a> (Value *Op) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b47a3cfdac6c8cc7e158e8ee75973d7">replaceMulWithMul24</a> (BinaryOperator &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace mul instructions with llvm.amdgcn.mul.u24 or llvm.amdgcn.mul.s24. <a href="#a8b47a3cfdac6c8cc7e158e8ee75973d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36b7410be1f86b52970bb1381904e282">foldBinOpIntoSelect</a> (BinaryOperator &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform same function as equivalently named function in DAGCombiner. <a href="#a36b7410be1f86b52970bb1381904e282">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b48004ee8ebb9a678049d7abc760328">divHasSpecialOptimization</a> (BinaryOperator &amp;I, Value *Num, Value *Den) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6281f602a2d61050f8e8214c34b16e">getDivNumBits</a> (BinaryOperator &amp;I, Value *Num, Value *Den, unsigned MaxDivBits, bool Signed) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Figure out how many bits are really needed for this division. <a href="#a5d6281f602a2d61050f8e8214c34b16e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a2f4914c617f05b628462576f6c969c">expandDivRem24</a> (IRBuilder&lt;&gt; &amp;Builder, BinaryOperator &amp;I, Value *Num, Value *Den, bool IsDiv, bool IsSigned) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands 24 bit div or rem. <a href="#a5a2f4914c617f05b628462576f6c969c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b0aeaa55a33109c212ca71908c51131">expandDivRem24Impl</a> (IRBuilder&lt;&gt; &amp;Builder, BinaryOperator &amp;I, Value *Num, Value *Den, unsigned NumBits, bool IsDiv, bool IsSigned) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23dda302945a17be7141fb6e3037f0e8">expandDivRem32</a> (IRBuilder&lt;&gt; &amp;Builder, BinaryOperator &amp;I, Value *Num, Value *Den) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands 32 bit div or rem. <a href="#a23dda302945a17be7141fb6e3037f0e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355c480e36ee4fa1a1a9135427005331">shrinkDivRem64</a> (IRBuilder&lt;&gt; &amp;Builder, BinaryOperator &amp;I, Value *Num, Value *Den) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe355d748502db216b2d4d0f730f59a4">expandDivRem64</a> (BinaryOperator &amp;I) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5141fae3a0d75080acb250f4152b974">canWidenScalarExtLoad</a> (LoadInst &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Widen a scalar load. <a href="#aa5141fae3a0d75080acb250f4152b974">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cacbfce1f2eaebad939051128812350">matchFractPat</a> (IntrinsicInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match non-nan fract pattern. <a href="#a8cacbfce1f2eaebad939051128812350">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe54f9c905611b1e6439acf843ea29e8">applyFractPat</a> (IRBuilder&lt;&gt; &amp;Builder, Value *FractArg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1969a1585363ca3069e708b24d19fda4">canOptimizeWithRsq</a> (const FPMathOperator *SqrtOp, FastMathFlags DivFMF, FastMathFlags SqrtFMF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae87e464933c41dbf0ad62bdf89905831">optimizeWithRsq</a> (IRBuilder&lt;&gt; &amp;Builder, Value *Num, Value *Den, FastMathFlags DivFMF, FastMathFlags SqrtFMF, const Instruction *CtxI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1f9568f6a2469baf6e85a9dc7b6c588">optimizeWithRcp</a> (IRBuilder&lt;&gt; &amp;Builder, Value *Num, Value *Den, FastMathFlags FMF, const Instruction *CtxI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03dc80eab5eb9f0f1ae05d6c3360d988">optimizeWithFDivFast</a> (IRBuilder&lt;&gt; &amp;Builder, Value *Num, Value *Den, float ReqdAccuracy) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65d4bb3128ef6767b5f1ff31742a3fa5">visitFDivElement</a> (IRBuilder&lt;&gt; &amp;Builder, Value *Num, Value *Den, FastMathFlags DivFMF, FastMathFlags SqrtFMF, Value *RsqOp, const Instruction *FDiv, float ReqdAccuracy) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0bab36c5ec58b16a657a0ec09cb641">getFrexpResults</a> (IRBuilder&lt;&gt; &amp;Builder, Value *Src) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1d678087a1611e0748d3c481e076b0c">emitRcpIEEE1ULP</a> (IRBuilder&lt;&gt; &amp;Builder, Value *Src, bool IsNegative) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an expansion of 1.0 / Src good for 1ulp that supports denormals. <a href="#ac1d678087a1611e0748d3c481e076b0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ae11456f5955d8499a96c9ba872caaf">emitFrexpDiv</a> (IRBuilder&lt;&gt; &amp;Builder, Value *LHS, Value *RHS, FastMathFlags FMF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a 2ulp expansion for fdiv by using frexp for input scaling. <a href="#a5ae11456f5955d8499a96c9ba872caaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33e5f96d603430d2b0ddffb1c06b8580">emitSqrtIEEE2ULP</a> (IRBuilder&lt;&gt; &amp;Builder, Value *Src, FastMathFlags FMF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a sqrt that handles denormals and is accurate to 2ulp. <a href="#a33e5f96d603430d2b0ddffb1c06b8580">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae534b46b7607eb604ddd8c66baa8d2d1">visitFDiv</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bccc7fd2b6c4f5ac273a8a4c448d67b">visitInstruction</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cbb1fa4211e94aed86925b13569004a">visitBinaryOperator</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3542900427118365bd67a1d1f4336a50">visitLoadInst</a> (LoadInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45241973f8fd0983638fd7f0282feacd">visitICmpInst</a> (ICmpInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22a44bbc6646770b4bd139ca4fe2d94">visitSelectInst</a> (SelectInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef67bcdb0247f9b4b984725fa065e1ce">visitPHINode</a> (PHINode &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6161a1346cfae6c3855e6cc1be059407">visitAddrSpaceCastInst</a> (AddrSpaceCastInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d0e144aac6116637cf1ddbb6363c003">visitIntrinsicInst</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24f24b2f8fe671156c06c68760737c5">visitBitreverseIntrinsicInst</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06396b4dd155b05f3faeb9dc674c3787">visitMinNum</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae42afee90ff90eb3b8fa78ad91d8858b">visitSqrt</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5bbbb258757741d38a876e5e203aa63">run</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5312450a2b03b7d9dba3cf35eff647fb">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine">AMDGPUTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada66ff87dc61a7e208f10f0c207e4ca5">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed504e065c1c2acd05e7b4e45b9ea7f">TLI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2afde5f3a04ce2c576e01f9a8396ba9">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84a4f902719b4c907463d2183865709f">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a00a2f5a62b5d5d5b6b0e143c4d30041f">UniformityInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab63a07cd0a25baf6900fe7aeaa6fbdeb">UA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0818c291787fd5e8356a06e6cd2b25c3">HasUnsafeFPMath</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a163079aa347cf24c87658740f923e7a0">HasFP32DenormalFlush</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba05020d4f1378fd8d9949483c4126b">FlowChanged</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667c16a40cbcd97a5f346c4275d3725e">SqrtF32</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d6fbefdc6099e2c3d250237898938f7">LdexpF32</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e35c50e56716a12652b406bb7364b68">BreakPhiNodesCache</a></td>
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


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUCodeGenPrepareImpl() {#a9a9bb93f26a50af2dbf9faa24fa3555a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::AMDGPUCodeGenPrepareImpl (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine">AMDGPUTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a00a2f5a62b5d5d5b6b0e143c4d30041f">UniformityInfo</a> &amp; UA)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#af2afde5f3a04ce2c576e01f9a8396ba9">AC</a>, <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>, <a href="#a84a4f902719b4c907463d2183865709f">DT</a>, <a href="#a5312450a2b03b7d9dba3cf35eff647fb">F</a>, <a href="#a163079aa347cf24c87658740f923e7a0">HasFP32DenormalFlush</a>, <a href="#a0818c291787fd5e8356a06e6cd2b25c3">HasUnsafeFPMath</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucodegenprepare-cpp-/#a51fadc2842e7b87f209324afcbd95119">anonymous{AMDGPUCodeGenPrepare.cpp}::hasUnsafeFPMath</a>, <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a>, <a href="#a9ed504e065c1c2acd05e7b4e45b9ea7f">TLI</a>, <a href="#ada66ff87dc61a7e208f10f0c207e4ca5">TM</a> and <a href="#ab63a07cd0a25baf6900fe7aeaa6fbdeb">UA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepare/#af6170254ef76a5d14783363b7862d85b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepare::runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyFractPat() {#abe54f9c905611b1e6439acf843ea29e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::applyFractPat (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FractArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a725f0b87c254902624322397fb9301ef">extractValues</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a33b84baa49efc1f81ba74a43da0119b5">insertValues</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a06396b4dd155b05f3faeb9dc674c3787">visitMinNum</a> and <a href="#aa22a44bbc6646770b4bd139ca4fe2d94">visitSelectInst</a>.</p>

</div>
</div>

### canBreakPHINode() {#a473885e550a15e1490b4de7f4ebd245f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::canBreakPHINode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0e35c50e56716a12652b406bb7364b68">BreakPhiNodesCache</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#af65e37f8e20df039d3dbbb10977b9bc5">collectPHINodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a77de311a4aa9ca492ad4fd8e6a363186">isInterestingPHIIncomingValue</a> and <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>.</p>


<p>Referenced by <a href="#aef67bcdb0247f9b4b984725fa065e1ce">visitPHINode</a>.</p>

</div>
</div>

### canIgnoreDenormalInput() {#a84e5cad6b96b065fe2b8f1df5fcfb82c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::canIgnoreDenormalInput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae24d4b778b2ebb07dee151d37e2ffdf3">llvm::computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da449c8fca7f540cc314102a67944fcd6e">llvm::fcSubnormal</a>, <a href="#a163079aa347cf24c87658740f923e7a0">HasFP32DenormalFlush</a> and <a href="/web-llvm/docs/api/structs/llvm/knownfpclass/#a2c951d72721a5640003806474c07f73d">llvm::KnownFPClass::isKnownNeverSubnormal</a>.</p>


<p>Referenced by <a href="#ae87e464933c41dbf0ad62bdf89905831">optimizeWithRsq</a> and <a href="#ae42afee90ff90eb3b8fa78ad91d8858b">visitSqrt</a>.</p>

</div>
</div>

### canOptimizeWithRsq() {#a1969a1585363ca3069e708b24d19fda4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::canOptimizeWithRsq (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a> * SqrtOp, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> DivFMF, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> SqrtFMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ad8c80fc37943fda4be56cf1e0b6cb145">llvm::FastMathFlags::allowContract</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ab09348cff01cf13d237779776c4fb887">llvm::FastMathFlags::approxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#af50d863c0e5a39ec42b567a9ea58e351">llvm::FPMathOperator::getFPAccuracy</a> and <a href="#a0818c291787fd5e8356a06e6cd2b25c3">HasUnsafeFPMath</a>.</p>


<p>Referenced by <a href="#ae534b46b7607eb604ddd8c66baa8d2d1">visitFDiv</a> and <a href="#ae42afee90ff90eb3b8fa78ad91d8858b">visitSqrt</a>.</p>

</div>
</div>

### canWidenScalarExtLoad() {#aa5141fae3a0d75080acb250f4152b974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::canWidenScalarExtLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Widen a scalar load.</p>


<p><span class="doxyComputerOutput">Widen</span> scalar load for uniform, small type loads from constant</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True.</p></dd>
</dl>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ab63a07cd0a25baf6900fe7aeaa6fbdeb">UA</a>.</p>


<p>Referenced by <a href="#a3542900427118365bd67a1d1f4336a50">visitLoadInst</a>.</p>

</div>
</div>

### computeKnownFPClass() {#a725665cbb013d5d85e6ed77a560a65ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownFPClass anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::computeKnownFPClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> Interested, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI)</td>
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

<p>Wrapper to pass all the arguments to computeKnownFPClass.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#af2afde5f3a04ce2c576e01f9a8396ba9">AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae24d4b778b2ebb07dee151d37e2ffdf3">llvm::computeKnownFPClass</a>, <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>, <a href="#a84a4f902719b4c907463d2183865709f">DT</a> and <a href="#a9ed504e065c1c2acd05e7b4e45b9ea7f">TLI</a>.</p>

</div>
</div>

### divHasSpecialOptimization() {#a9b48004ee8ebb9a678049d7abc760328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::divHasSpecialOptimization (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Num, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Den)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#af2afde5f3a04ce2c576e01f9a8396ba9">AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>, <a href="#a84a4f902719b4c907463d2183865709f">DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4036c3c75bcee1206cd199548b87f9ae">llvm::isKnownToBeAPowerOfTwo</a>.</p>


<p>Referenced by <a href="#a23dda302945a17be7141fb6e3037f0e8">expandDivRem32</a> and <a href="#a355c480e36ee4fa1a1a9135427005331">shrinkDivRem64</a>.</p>

</div>
</div>

### emitFrexpDiv() {#a5ae11456f5955d8499a96c9ba872caaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::emitFrexpDiv (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a 2ulp expansion for fdiv by using frexp for input scaling.</p>

<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae33cfb24f8bc0f6aa80c3a49e3769f6d">llvm::IRBuilderBase::CreateFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9ac45fd1485e6735d83544e54fb52d4b">llvm::IRBuilderBase::CreateUnaryIntrinsic</a>, <a href="#ada0bab36c5ec58b16a657a0ec09cb641">getFrexpResults</a>, <a href="#a45499cf71e7324771b2faa3921da99bb">getLdexpF32</a>, <a href="#a163079aa347cf24c87658740f923e7a0">HasFP32DenormalFlush</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#ae0f503db91504a3f3440ab81260e4134">Mul</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a39b529fcda9ee90b17a3e1fed732a22a">llvm::FastMathFlags::noInfs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ac1d140361490d7847edf0c7503e3188a">llvm::FastMathFlags::noNaNs</a> and <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a>.</p>


<p>Referenced by <a href="#a65d4bb3128ef6767b5f1ff31742a3fa5">visitFDivElement</a>.</p>

</div>
</div>

### emitRcpIEEE1ULP() {#ac1d678087a1611e0748d3c481e076b0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::emitRcpIEEE1ULP (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src, bool IsNegative)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an expansion of 1.0 / Src good for 1ulp that supports denormals.</p>

<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae44006b91094939f6ea72655e8312504">llvm::IRBuilderBase::CreateFNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7704bf68951054ffeb3efe605750e2d9">llvm::IRBuilderBase::CreateNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9ac45fd1485e6735d83544e54fb52d4b">llvm::IRBuilderBase::CreateUnaryIntrinsic</a>, <a href="#ada0bab36c5ec58b16a657a0ec09cb641">getFrexpResults</a> and <a href="#a45499cf71e7324771b2faa3921da99bb">getLdexpF32</a>.</p>


<p>Referenced by <a href="#af1f9568f6a2469baf6e85a9dc7b6c588">optimizeWithRcp</a>.</p>

</div>
</div>

### emitSqrtIEEE2ULP() {#a33e5f96d603430d2b0ddffb1c06b8580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::emitSqrtIEEE2ULP (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a sqrt that handles denormals and is accurate to 2ulp.</p>

<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63c8cf2d681e30f3677e67b31c1937a0">llvm::IRBuilderBase::CreateFCmpOLT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="#a45499cf71e7324771b2faa3921da99bb">getLdexpF32</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c568ab8748aba5d37006d52618bbcfd">llvm::APFloat::getSmallestNormalized</a>, <a href="#a20b2cf2d81b88d6e6c40a523245424ea">getSqrtF32</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a5d6e37f3d036496321824378223ad718a8009351707fa969013ab5d9126bab03e">Scaled</a>.</p>


<p>Referenced by <a href="#ae42afee90ff90eb3b8fa78ad91d8858b">visitSqrt</a>.</p>

</div>
</div>

### expandDivRem24() {#a5a2f4914c617f05b628462576f6c969c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::expandDivRem24 (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Num, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Den, bool IsDiv, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expands 24 bit div or rem.</p>

<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#a9b0aeaa55a33109c212ca71908c51131">expandDivRem24Impl</a>, <a href="#a5d6281f602a2d61050f8e8214c34b16e">getDivNumBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a23dda302945a17be7141fb6e3037f0e8">expandDivRem32</a>.</p>

</div>
</div>

### expandDivRem24Impl() {#a9b0aeaa55a33109c212ca71908c51131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::expandDivRem24Impl (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Num, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Den, unsigned NumBits, bool IsDiv, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#a24a7664d83746bcda035bddeb773eaae">llvm::Instruction::copyFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#adc6a2686b807c18e4a7f7fc58e68d423">llvm::IRBuilderBase::CreateAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#af71b207a835b6809fe4cd8bdb9fcf31b">llvm::IRBuilderBase::CreateFCmpOGE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae33cfb24f8bc0f6aa80c3a49e3769f6d">llvm::IRBuilderBase::CreateFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae44006b91094939f6ea72655e8312504">llvm::IRBuilderBase::CreateFNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#afd0b5a07710757874fa84076969537b0">llvm::IRBuilderBase::CreateFPToSI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4cac1c8f9a62a9d1079e4d0499bbb848">llvm::IRBuilderBase::CreateFPToUI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a2e19b7738daed96724457c786521e5e1">llvm::IRBuilderBase::CreateSIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5d0b7f11d28f823b8323344d84d63f03">llvm::IRBuilderBase::CreateUIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9ac45fd1485e6735d83544e54fb52d4b">llvm::IRBuilderBase::CreateUnaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9bf8dc8e2767724bf8e6839992633954">llvm::IRBuilderBase::getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aafb3bab3be2f6daaa1178de24492df05">llvm::IRBuilderBase::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a>.</p>


<p>Referenced by <a href="#a5a2f4914c617f05b628462576f6c969c">expandDivRem24</a> and <a href="#a355c480e36ee4fa1a1a9135427005331">shrinkDivRem64</a>.</p>

</div>
</div>

### expandDivRem32() {#a23dda302945a17be7141fb6e3037f0e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::expandDivRem32 (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Num, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Den)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expands 32 bit div or rem.</p>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae33cfb24f8bc0f6aa80c3a49e3769f6d">llvm::IRBuilderBase::CreateFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4cac1c8f9a62a9d1079e4d0499bbb848">llvm::IRBuilderBase::CreateFPToUI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac613fa8e66fca464885c3f274fbeb834">llvm::IRBuilderBase::CreateICmpUGE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aeb11a01107c6be1f52ba01902a165d71">llvm::IRBuilderBase::CreateSExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5d0b7f11d28f823b8323344d84d63f03">llvm::IRBuilderBase::CreateUIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a36742c35a8fff5f74bb3d76c9c19dd47">llvm::IRBuilderBase::CreateZExtOrTrunc</a>, <a href="#a9b48004ee8ebb9a678049d7abc760328">divHasSpecialOptimization</a>, <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>, <a href="#a5a2f4914c617f05b628462576f6c969c">expandDivRem24</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aafb3bab3be2f6daaa1178de24492df05">llvm::IRBuilderBase::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a7359be3b94f25d09f84ce7d6dbad5c34">getMulHu</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#abe36fa76137ff4c78ce9f558258e1e80">getSign32</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a04a94a2848616d79534531d56bb82bfb">llvm::FastMathFlags::setFast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6370e29617c71c8081bbbc68d6058403">llvm::IRBuilderBase::setFastMathFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#a355c480e36ee4fa1a1a9135427005331">shrinkDivRem64</a> and <a href="#a1cbb1fa4211e94aed86925b13569004a">visitBinaryOperator</a>.</p>

</div>
</div>

### expandDivRem64() {#afe355d748502db216b2d4d0f730f59a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUCodeGenPrepareImpl::expandDivRem64 (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6c6db1ba2b3654c01ec2363b2bc34ce4">llvm::expandDivisionUpTo64Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27da54a97fcba955457048148b1fef99">llvm::expandRemainderUpTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a1cbb1fa4211e94aed86925b13569004a">visitBinaryOperator</a>.</p>

</div>
</div>

### foldBinOpIntoSelect() {#a36b7410be1f86b52970bb1381904e282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::foldBinOpIntoSelect (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform same function as equivalently named function in DAGCombiner.</p>


<p>Since we expand some divisions here, we need to perform this before obscuring.</p>


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a964455f36837281d37f2a44e2fcb4cca">llvm::ConstantFoldBinaryOpOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a9f80c73009332bada61d1493b0a34e6b">findSelectThroughCast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#a706a961e17ec4354d2174aac3ea3ecb5">llvm::SelectInst::getCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#a1b39b0c7ce6162c1f4754a2862957185">llvm::SelectInst::getFalseValue</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a3685b2128d8e6917000e4adc3b266ff6">llvm::CastInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#ae95a0fb83a1c98ce1aed74147c026db0">llvm::SelectInst::getTrueValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6370e29617c71c8081bbbc68d6058403">llvm::IRBuilderBase::setFastMathFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a>.</p>


<p>Referenced by <a href="#a1cbb1fa4211e94aed86925b13569004a">visitBinaryOperator</a>.</p>

</div>
</div>

### getBaseElementBitWidth() {#a800dbbf6469dc037cd9eb5305ff554a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUCodeGenPrepareImpl::getBaseElementBitWidth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copies exact/nsw/nuw flags (if any) from binary operation <span class="doxyComputerOutput">I</span> to binary operation <span class="doxyComputerOutput">V</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Binary operation <span class="doxyComputerOutput">V</span>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">T's</span> base element bit width.</p></dd>
</dl>


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a>.</p>


<p>Referenced by <a href="#ae7f14d9907d63254543fb2375d87b623">promoteUniformBitreverseToI32</a>.</p>

</div>
</div>

### getDivNumBits() {#a5d6281f602a2d61050f8e8214c34b16e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUCodeGenPrepareImpl::getDivNumBits (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Num, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Den, unsigned MaxDivBits, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Figure out how many bits are really needed for this division.</p>


<p><span class="doxyComputerOutput">MaxDivBits</span> is an optimization hint to bypass the second ComputeNumSignBits/computeKnownBits call if the first one is insufficient.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#af2afde5f3a04ce2c576e01f9a8396ba9">AC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad46ed333b920b20e78d948610366254c">llvm::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a7f47812e8e75b0616a97d7004e5fb909">llvm::KnownBits::countMinLeadingZeros</a>, <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aabc0af41b4437080b27002ed7a1ed656">llvm::KnownBits::isNegative</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a157efd68e8b4b838829cad165b1583f8">llvm::KnownBits::isNonNegative</a>.</p>


<p>Referenced by <a href="#a5a2f4914c617f05b628462576f6c969c">expandDivRem24</a> and <a href="#a355c480e36ee4fa1a1a9135427005331">shrinkDivRem64</a>.</p>

</div>
</div>

### getFrexpResults() {#ada0bab36c5ec58b16a657a0ec09cb641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; AMDGPUCodeGenPrepareImpl::getFrexpResults (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a> and <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a>.</p>


<p>Referenced by <a href="#a5ae11456f5955d8499a96c9ba872caaf">emitFrexpDiv</a> and <a href="#ac1d678087a1611e0748d3c481e076b0c">emitRcpIEEE1ULP</a>.</p>

</div>
</div>

### getI32Ty() {#af5de925ed31e50af1df0f4d5e26a50c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AMDGPUCodeGenPrepareImpl::getI32Ty (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Equivalent 32 bit integer type for given type <span class="doxyComputerOutput">T</span>. For example, if <span class="doxyComputerOutput">T</span> is i7, then i32 is returned; if <span class="doxyComputerOutput">T</span> is &lt;3 x i12&gt;, then &lt;3 x i32&gt; is returned.</p></dd>
</dl>


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a> and <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a>.</p>


<p>Referenced by <a href="#ae7f14d9907d63254543fb2375d87b623">promoteUniformBitreverseToI32</a>, <a href="#af5cda76a7708fa48ddc1de837c4fe5e7">promoteUniformOpToI32</a>, <a href="#ad768a9cd1293081ea1b03af6a146451a">promoteUniformOpToI32</a> and <a href="#af60d41958d088dadfdca762d75f23e8d">promoteUniformOpToI32</a>.</p>

</div>
</div>

### getLdexpF32() {#a45499cf71e7324771b2faa3921da99bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::getLdexpF32 ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#a5312450a2b03b7d9dba3cf35eff647fb">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a> and <a href="#a3d6fbefdc6099e2c3d250237898938f7">LdexpF32</a>.</p>


<p>Referenced by <a href="#a5ae11456f5955d8499a96c9ba872caaf">emitFrexpDiv</a>, <a href="#ac1d678087a1611e0748d3c481e076b0c">emitRcpIEEE1ULP</a> and <a href="#a33e5f96d603430d2b0ddffb1c06b8580">emitSqrtIEEE2ULP</a>.</p>

</div>
</div>

### getSqrtF32() {#a20b2cf2d81b88d6e6c40a523245424ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::getSqrtF32 ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#a5312450a2b03b7d9dba3cf35eff647fb">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a> and <a href="#a667c16a40cbcd97a5f346c4275d3725e">SqrtF32</a>.</p>


<p>Referenced by <a href="#a33e5f96d603430d2b0ddffb1c06b8580">emitSqrtIEEE2ULP</a> and <a href="#ae42afee90ff90eb3b8fa78ad91d8858b">visitSqrt</a>.</p>

</div>
</div>

### isLegalFloatingTy() {#aaeababc2d5ffb872b7ef9f71fe5613b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::isLegalFloatingTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">T</span> is a legal scalar floating point type.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Reference <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a>.</p>


<p>Referenced by <a href="#a8cacbfce1f2eaebad939051128812350">matchFractPat</a>.</p>

</div>
</div>

### isSigned() {#ac434cec8bb472f27b985344dfd19b8e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::isSigned (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if binary operation <span class="doxyComputerOutput">I</span> is a signed binary operation, false otherwise.</p></dd>
</dl>


<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#af5cda76a7708fa48ddc1de837c4fe5e7">promoteUniformOpToI32</a> and <a href="#af60d41958d088dadfdca762d75f23e8d">promoteUniformOpToI32</a>.</p>

</div>
</div>

### isSigned() {#a1d048c35e76be8217f7a9fa629bbb476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::isSigned (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the condition of 'select' operation <span class="doxyComputerOutput">I</span> comes from a signed 'icmp' operation, false otherwise.</p></dd>
</dl>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### matchFractPat() {#a8cacbfce1f2eaebad939051128812350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::matchFractPat (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match non-nan fract pattern.</p>


<p>minnum(fsub(x, floor(x)), nextafter(1.0, -1.0)</p>


<p>If fract is a useful instruction for the subtarget. Does not account for the nan handling; the instruction has a nan check on the input value.</p>


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aaeababc2d5ffb872b7ef9f71fe5613b3">isLegalFloatingTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acd794d7b3653822f61ba126e1678e03f">llvm::PatternMatch::m_APFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a53fc7d443cf6412add6dfddd11652e5d">llvm::PatternMatch::m_Deferred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0fa2fe47478bcc6676ec49dd76544e3a">llvm::PatternMatch::m_FSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab0fdc79bb75e8fe845f98e2199f9d451">llvm::APFloat::next</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a> and <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a>.</p>


<p>Referenced by <a href="#a06396b4dd155b05f3faeb9dc674c3787">visitMinNum</a> and <a href="#aa22a44bbc6646770b4bd139ca4fe2d94">visitSelectInst</a>.</p>

</div>
</div>

### needsPromotionToI32() {#a35bf25a29df704bcdf8e829ed50361db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::needsPromotionToI32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if type <span class="doxyComputerOutput">T</span> needs to be promoted to 32 bit integer type, false otherwise.</p></dd>
</dl>


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a>, <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucodegenprepare-cpp-/#aac33fe1fe029ad7a8b2fd1d684d21ac0">anonymous{AMDGPUCodeGenPrepare.cpp}::Widen16BitOps</a>.</p>


<p>Referenced by <a href="#a800dbbf6469dc037cd9eb5305ff554a9">getBaseElementBitWidth</a>, <a href="#af5de925ed31e50af1df0f4d5e26a50c6">getI32Ty</a>, <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a>, <a href="#ae7f14d9907d63254543fb2375d87b623">promoteUniformBitreverseToI32</a>, <a href="#af5cda76a7708fa48ddc1de837c4fe5e7">promoteUniformOpToI32</a>, <a href="#ad768a9cd1293081ea1b03af6a146451a">promoteUniformOpToI32</a>, <a href="#af60d41958d088dadfdca762d75f23e8d">promoteUniformOpToI32</a>, <a href="#a1cbb1fa4211e94aed86925b13569004a">visitBinaryOperator</a>, <a href="#af24f24b2f8fe671156c06c68760737c5">visitBitreverseIntrinsicInst</a>, <a href="#a45241973f8fd0983638fd7f0282feacd">visitICmpInst</a> and <a href="#aa22a44bbc6646770b4bd139ca4fe2d94">visitSelectInst</a>.</p>

</div>
</div>

### numBitsSigned() {#a2c12020d1ecaa1b55d62889b342f4f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUCodeGenPrepareImpl::numBitsSigned (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The minimum number of bits needed to store the value of \Op as a signed integer. Truncating to this size and then sign-extending to the original size will not change the value.</p></dd>
</dl>


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#af2afde5f3a04ce2c576e01f9a8396ba9">AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae95177e7337984f5bc961723ecf67169">llvm::ComputeMaxSignificantBits</a> and <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>.</p>


<p>Referenced by <a href="#a8b47a3cfdac6c8cc7e158e8ee75973d7">replaceMulWithMul24</a>.</p>

</div>
</div>

### numBitsUnsigned() {#ac08070db79359ea85bcff1e4fca790c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUCodeGenPrepareImpl::numBitsUnsigned (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The minimum number of bits needed to store the value of \Op as an unsigned integer. Truncating to this size and then zero-extending to the original will not change the value.</p></dd>
</dl>


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#af2afde5f3a04ce2c576e01f9a8396ba9">AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a> and <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>.</p>


<p>Referenced by <a href="#a8b47a3cfdac6c8cc7e158e8ee75973d7">replaceMulWithMul24</a>.</p>

</div>
</div>

### optimizeWithFDivFast() {#a03dc80eab5eb9f0f1ae05d6c3360d988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::optimizeWithFDivFast (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Num, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Den, float ReqdAccuracy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a163079aa347cf24c87658740f923e7a0">HasFP32DenormalFlush</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a3ffc75c3a4cb82ba307a3334483eb4ac">llvm::Type::isFloatTy</a>.</p>


<p>Referenced by <a href="#a65d4bb3128ef6767b5f1ff31742a3fa5">visitFDivElement</a>.</p>

</div>
</div>

### optimizeWithRcp() {#af1f9568f6a2469baf6e85a9dc7b6c588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::optimizeWithRcp (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Num, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Den, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a5c66c6bd0bb552d9e58e20617dc83e5d">llvm::FastMathFlags::allowReciprocal</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ab09348cff01cf13d237779776c4fb887">llvm::FastMathFlags::approxFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae33cfb24f8bc0f6aa80c3a49e3769f6d">llvm::IRBuilderBase::CreateFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae44006b91094939f6ea72655e8312504">llvm::IRBuilderBase::CreateFNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9ac45fd1485e6735d83544e54fb52d4b">llvm::IRBuilderBase::CreateUnaryIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ac1d678087a1611e0748d3c481e076b0c">emitRcpIEEE1ULP</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a163079aa347cf24c87658740f923e7a0">HasFP32DenormalFlush</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a3ffc75c3a4cb82ba307a3334483eb4ac">llvm::Type::isFloatTy</a>.</p>


<p>Referenced by <a href="#a65d4bb3128ef6767b5f1ff31742a3fa5">visitFDivElement</a>.</p>

</div>
</div>

### optimizeWithRsq() {#ae87e464933c41dbf0ad62bdf89905831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::optimizeWithRsq (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Num, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Den, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> DivFMF, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> SqrtFMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ad8c80fc37943fda4be56cf1e0b6cb145">llvm::FastMathFlags::allowContract</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ab09348cff01cf13d237779776c4fb887">llvm::FastMathFlags::approxFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a84e5cad6b96b065fe2b8f1df5fcfb82c">canIgnoreDenormalInput</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae44006b91094939f6ea72655e8312504">llvm::IRBuilderBase::CreateFNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9ac45fd1485e6735d83544e54fb52d4b">llvm::IRBuilderBase::CreateUnaryIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#ab8a7b154668a6d94ab02f1bac73e99e9">emitRsqIEEE1ULP</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a0818c291787fd5e8356a06e6cd2b25c3">HasUnsafeFPMath</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#abc0558cd7175718747da9d910ef1c19a">llvm::ConstantFP::isExactlyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3ffc75c3a4cb82ba307a3334483eb4ac">llvm::Type::isFloatTy</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6370e29617c71c8081bbbc68d6058403">llvm::IRBuilderBase::setFastMathFlags</a>.</p>


<p>Referenced by <a href="#a65d4bb3128ef6767b5f1ff31742a3fa5">visitFDivElement</a>.</p>

</div>
</div>

### promoteUniformBitreverseToI32() {#ae7f14d9907d63254543fb2375d87b623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::promoteUniformBitreverseToI32 (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Promotes uniform 'bitreverse' intrinsic <span class="doxyComputerOutput">I</span> to 32 bit 'bitreverse' intrinsic.</p>


<p><span class="doxyComputerOutput">I's</span> base element bit width must be greater than 1 and less than or equal 16. Promotion is done by zero extending the operand to 32 bits, replacing <span class="doxyComputerOutput">I</span> with 32 bit 'bitreverse' intrinsic, shifting the result of 32 bit 'bitreverse' intrinsic to the right with zero fill (the shift amount is 32 minus <span class="doxyComputerOutput">I's</span> base element bit width), and truncating the result of the shift operation back to <span class="doxyComputerOutput">I's</span> original type.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True.</p></dd>
</dl>


<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="#a800dbbf6469dc037cd9eb5305ff554a9">getBaseElementBitWidth</a>, <a href="#af5de925ed31e50af1df0f4d5e26a50c6">getI32Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>.</p>


<p>Referenced by <a href="#af24f24b2f8fe671156c06c68760737c5">visitBitreverseIntrinsicInst</a>.</p>

</div>
</div>

### promoteUniformOpToI32() {#af5cda76a7708fa48ddc1de837c4fe5e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::promoteUniformOpToI32 (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Promotes uniform binary operation <span class="doxyComputerOutput">I</span> to equivalent 32 bit binary operation.</p>


<p><span class="doxyComputerOutput">I's</span> base element bit width must be greater than 1 and less than or equal 16. Promotion is done by sign or zero extending operands to 32 bits, replacing <span class="doxyComputerOutput">I</span> with equivalent 32 bit binary operation, and truncating the result of 32 bit binary operation back to <span class="doxyComputerOutput">I's</span> original type. Division operation is not promoted.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if <span class="doxyComputerOutput">I</span> is promoted to equivalent 32 bit binary operation, false otherwise.</p></dd>
</dl>


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#af5de925ed31e50af1df0f4d5e26a50c6">getI32Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac434cec8bb472f27b985344dfd19b8e9">isSigned</a>, <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a130ed3634325d5bd55fc68eee4f6a44d">promotedOpIsNSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a52615c4f2a193b11f52f1f2aa86ebab8">promotedOpIsNUW</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>.</p>


<p>Referenced by <a href="#a1cbb1fa4211e94aed86925b13569004a">visitBinaryOperator</a>, <a href="#a45241973f8fd0983638fd7f0282feacd">visitICmpInst</a> and <a href="#aa22a44bbc6646770b4bd139ca4fe2d94">visitSelectInst</a>.</p>

</div>
</div>

### promoteUniformOpToI32() {#ad768a9cd1293081ea1b03af6a146451a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::promoteUniformOpToI32 (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Promotes uniform 'icmp' operation <span class="doxyComputerOutput">I</span> to 32 bit 'icmp' operation.</p>


<p><span class="doxyComputerOutput">I's</span> base element bit width must be greater than 1 and less than or equal 16. Promotion is done by sign or zero extending operands to 32 bits, and replacing <span class="doxyComputerOutput">I</span> with 32 bit 'icmp' operation.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True.</p></dd>
</dl>


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="#af5de925ed31e50af1df0f4d5e26a50c6">getI32Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>.</p>

</div>
</div>

### promoteUniformOpToI32() {#af60d41958d088dadfdca762d75f23e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::promoteUniformOpToI32 (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Promotes uniform 'select' operation <span class="doxyComputerOutput">I</span> to 32 bit 'select' operation.</p>


<p><span class="doxyComputerOutput">I's</span> base element bit width must be greater than 1 and less than or equal 16. Promotion is done by sign or zero extending operands to 32 bits, replacing <span class="doxyComputerOutput">I</span> with 32 bit 'select' operation, and truncating the result of 32 bit 'select' operation back to <span class="doxyComputerOutput">I's</span> original type.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True.</p></dd>
</dl>


<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="#af5de925ed31e50af1df0f4d5e26a50c6">getI32Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac434cec8bb472f27b985344dfd19b8e9">isSigned</a>, <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>.</p>

</div>
</div>

### replaceMulWithMul24() {#a8b47a3cfdac6c8cc7e158e8ee75973d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::replaceMulWithMul24 (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace mul instructions with llvm.amdgcn.mul.u24 or llvm.amdgcn.mul.s24.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> has an issue where an and asserting the bits are known</p>


<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aeb11a01107c6be1f52ba01902a165d71">llvm::IRBuilderBase::CreateSExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a36742c35a8fff5f74bb3d76c9c19dd47">llvm::IRBuilderBase::CreateZExtOrTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a725f0b87c254902624322397fb9301ef">extractValues</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a33b84baa49efc1f81ba74a43da0119b5">insertValues</a>, <a href="#a2c12020d1ecaa1b55d62889b342f4f09">numBitsSigned</a>, <a href="#ac08070db79359ea85bcff1e4fca790c9">numBitsUnsigned</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a> and <a href="#ab63a07cd0a25baf6900fe7aeaa6fbdeb">UA</a>.</p>


<p>Referenced by <a href="#a1cbb1fa4211e94aed86925b13569004a">visitBinaryOperator</a>.</p>

</div>
</div>

### run() {#aa5bbbb258757741d38a876e5e203aa63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#a0e35c50e56716a12652b406bb7364b68">BreakPhiNodesCache</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="#a5312450a2b03b7d9dba3cf35eff647fb">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#a090736355958192cac4db32336c48bbd">visit</a>.</p>

</div>
</div>

### shrinkDivRem64() {#a355c480e36ee4fa1a1a9135427005331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::shrinkDivRem64 (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Num, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Den)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="#a9b48004ee8ebb9a678049d7abc760328">divHasSpecialOptimization</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucodegenprepare-cpp-/#a7898546510677e1eb8ebf7d2a21c12bf">anonymous{AMDGPUCodeGenPrepare.cpp}::ExpandDiv64InIR</a>, <a href="#a9b0aeaa55a33109c212ca71908c51131">expandDivRem24Impl</a>, <a href="#a23dda302945a17be7141fb6e3037f0e8">expandDivRem32</a>, <a href="#a5d6281f602a2d61050f8e8214c34b16e">getDivNumBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a1cbb1fa4211e94aed86925b13569004a">visitBinaryOperator</a>.</p>

</div>
</div>

### visitAddrSpaceCastInst() {#a6161a1346cfae6c3855e6cc1be059407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::visitAddrSpaceCastInst (<a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst">AddrSpaceCastInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aaa1e27e4fc68e5706a4b7bbaed447c14">llvm::AMDGPUAS::FLAT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc66c148bcd950ffcc3ab83989eb70bd">llvm::getUnderlyingObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#af897cc9cadd4ddd140100754cd3fca4d">isPtrKnownNeverNull</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a> and <a href="#ada66ff87dc61a7e208f10f0c207e4ca5">TM</a>.</p>

</div>
</div>

### visitBinaryOperator() {#a1cbb1fa4211e94aed86925b13569004a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::visitBinaryOperator (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucodegenprepare-cpp-/#a68fd0a23e281eac760945bc97e2f4cef">anonymous{AMDGPUCodeGenPrepare.cpp}::DisableIDivExpand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucodegenprepare-cpp-/#a7898546510677e1eb8ebf7d2a21c12bf">anonymous{AMDGPUCodeGenPrepare.cpp}::ExpandDiv64InIR</a>, <a href="#a23dda302945a17be7141fb6e3037f0e8">expandDivRem32</a>, <a href="#afe355d748502db216b2d4d0f730f59a4">expandDivRem64</a>, <a href="#a1ba05020d4f1378fd8d9949483c4126b">FlowChanged</a>, <a href="#a36b7410be1f86b52970bb1381904e282">foldBinOpIntoSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a>, <a href="#af5cda76a7708fa48ddc1de837c4fe5e7">promoteUniformOpToI32</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a8b47a3cfdac6c8cc7e158e8ee75973d7">replaceMulWithMul24</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>, <a href="#a355c480e36ee4fa1a1a9135427005331">shrinkDivRem64</a>, <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a>, <a href="#ab63a07cd0a25baf6900fe7aeaa6fbdeb">UA</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucodegenprepare-cpp-/#a4f60a8be026de5607c9511bd772e8e25">anonymous{AMDGPUCodeGenPrepare.cpp}::UseMul24Intrin</a>.</p>

</div>
</div>

### visitBitreverseIntrinsicInst() {#af24f24b2f8fe671156c06c68760737c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::visitBitreverseIntrinsicInst (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a>, <a href="#ae7f14d9907d63254543fb2375d87b623">promoteUniformBitreverseToI32</a>, <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a> and <a href="#ab63a07cd0a25baf6900fe7aeaa6fbdeb">UA</a>.</p>


<p>Referenced by <a href="#a7d0e144aac6116637cf1ddbb6363c003">visitIntrinsicInst</a>.</p>

</div>
</div>

### visitFDiv() {#ae534b46b7607eb604ddd8c66baa8d2d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::visitFDiv (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ab09348cff01cf13d237779776c4fb887">llvm::FastMathFlags::approxFunc</a>, <a href="#a1969a1585363ca3069e708b24d19fda4">canOptimizeWithRsq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a281abd69fe346ad2c5749c2e1af250d1">llvm::IRBuilderBase::CreateFDiv</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucodegenprepare-cpp-/#a4beafd25e9bfe504239256d87f4e5aad">anonymous{AMDGPUCodeGenPrepare.cpp}::DisableFDivExpand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a725f0b87c254902624322397fb9301ef">extractValues</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#a8be4fec4d0b6071fb7d7520364fd5378">llvm::FPMathOperator::getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#af50d863c0e5a39ec42b567a9ea58e351">llvm::FPMathOperator::getFPAccuracy</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a0818c291787fd5e8356a06e6cd2b25c3">HasUnsafeFPMath</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a33b84baa49efc1f81ba74a43da0119b5">insertValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1106b8a15061e8494873e10bb8a364e5">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6370e29617c71c8081bbbc68d6058403">llvm::IRBuilderBase::setFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a>, <a href="#a9ed504e065c1c2acd05e7b4e45b9ea7f">TLI</a> and <a href="#a65d4bb3128ef6767b5f1ff31742a3fa5">visitFDivElement</a>.</p>

</div>
</div>

### visitFDivElement() {#a65d4bb3128ef6767b5f1ff31742a3fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AMDGPUCodeGenPrepareImpl::visitFDivElement (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Num, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Den, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> DivFMF, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> SqrtFMF, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RsqOp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * FDiv, float ReqdAccuracy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#a5ae11456f5955d8499a96c9ba872caaf">emitFrexpDiv</a>, <a href="#a03dc80eab5eb9f0f1ae05d6c3360d988">optimizeWithFDivFast</a>, <a href="#af1f9568f6a2469baf6e85a9dc7b6c588">optimizeWithRcp</a> and <a href="#ae87e464933c41dbf0ad62bdf89905831">optimizeWithRsq</a>.</p>


<p>Referenced by <a href="#ae534b46b7607eb604ddd8c66baa8d2d1">visitFDiv</a>.</p>

</div>
</div>

### visitICmpInst() {#a45241973f8fd0983638fd7f0282feacd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::visitICmpInst (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a>, <a href="#af5cda76a7708fa48ddc1de837c4fe5e7">promoteUniformOpToI32</a>, <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a> and <a href="#ab63a07cd0a25baf6900fe7aeaa6fbdeb">UA</a>.</p>

</div>
</div>

### visitInstruction() {#a5bccc7fd2b6c4f5ac273a8a4c448d67b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitIntrinsicInst() {#a7d0e144aac6116637cf1ddbb6363c003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::visitIntrinsicInst (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af24f24b2f8fe671156c06c68760737c5">visitBitreverseIntrinsicInst</a>, <a href="#a06396b4dd155b05f3faeb9dc674c3787">visitMinNum</a> and <a href="#ae42afee90ff90eb3b8fa78ad91d8858b">visitSqrt</a>.</p>

</div>
</div>

### visitLoadInst() {#a3542900427118365bd67a1d1f4336a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::visitLoadInst (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#aa5141fae3a0d75080acb250f4152b974">canWidenScalarExtLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aa6d3112da64eecbdbb50aacb5f8251e8">llvm::AMDGPUAS::CONSTANT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a1caf1e287a5fe7250388d66ed72aa0c1">llvm::AMDGPUAS::CONSTANT_ADDRESS_32BIT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="#a5312450a2b03b7d9dba3cf35eff647fb">F</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a31e2db8d1b315202d2c19e711b5365fd">llvm::IRBuilderBase::getIntNTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucodegenprepare-cpp-/#a2d3ae3e746bb9043b2975f1bf5431a18">anonymous{AMDGPUCodeGenPrepare.cpp}::WidenLoads</a>.</p>

</div>
</div>

### visitMinNum() {#a06396b4dd155b05f3faeb9dc674c3787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::visitMinNum (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#abe54f9c905611b1e6439acf843ea29e8">applyFractPat</a>, <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb004c066abda7e0738004a08bc1827f">llvm::isKnownNeverNaN</a>, <a href="#a8cacbfce1f2eaebad939051128812350">matchFractPat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1106b8a15061e8494873e10bb8a364e5">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6370e29617c71c8081bbbc68d6058403">llvm::IRBuilderBase::setFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#abbceb1c6e5c4b49f53b381a8fad9e12a">llvm::FastMathFlags::setNoNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a> and <a href="#a9ed504e065c1c2acd05e7b4e45b9ea7f">TLI</a>.</p>


<p>Referenced by <a href="#a7d0e144aac6116637cf1ddbb6363c003">visitIntrinsicInst</a>.</p>

</div>
</div>

### visitPHINode() {#aef67bcdb0247f9b4b984725fa065e1ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::visitPHINode (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucodegenprepare-cpp-/#a1dff2a9feda65e02c09974c544c8c4ff">anonymous{AMDGPUCodeGenPrepare.cpp}::BreakLargePHIs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucodegenprepare-cpp-/#a6ccf25014466f5d87fe3971cc9f060aa">anonymous{AMDGPUCodeGenPrepare.cpp}::BreakLargePHIsThreshold</a>, <a href="#a473885e550a15e1490b4de7f4ebd245f">canBreakPHINode</a>, <a href="#ad6fa8252711b6da609826cdf5f7076b2">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a96ee83741efbaafdb0df1eb8eff27d1b">EnableGlobalISelOption</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucodegenprepare-cpp-/#acd5e4cd8d0b926539e5d784be7234af4">anonymous{AMDGPUCodeGenPrepare.cpp}::ForceBreakLargePHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff30786f1ea13c3ea475acce504571e4">llvm::getCGPassBuilderOption</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a1893caf878859959ba6a3d5442ef1439">llvm::FixedVectorType::getNumElements</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitSelectInst() {#aa22a44bbc6646770b4bd139ca4fe2d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::visitSelectInst (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#abe54f9c905611b1e6439acf843ea29e8">applyFractPat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#a8be4fec4d0b6071fb7d7520364fd5378">llvm::FPMathOperator::getFastMathFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a08d5220c6f77428fcfd5bd1de5af2bbc">llvm::PatternMatch::m_FCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a687b01673bf40f0ee674373609201b71">llvm::PatternMatch::m_NonNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a8cacbfce1f2eaebad939051128812350">matchFractPat</a>, <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a>, <a href="#af5cda76a7708fa48ddc1de837c4fe5e7">promoteUniformOpToI32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1106b8a15061e8494873e10bb8a364e5">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6370e29617c71c8081bbbc68d6058403">llvm::IRBuilderBase::setFastMathFlags</a>, <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a>, <a href="#a9ed504e065c1c2acd05e7b4e45b9ea7f">TLI</a> and <a href="#ab63a07cd0a25baf6900fe7aeaa6fbdeb">UA</a>.</p>

</div>
</div>

### visitSqrt() {#ae42afee90ff90eb3b8fa78ad91d8858b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCodeGenPrepareImpl::visitSqrt (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ab09348cff01cf13d237779776c4fb887">llvm::FastMathFlags::approxFunc</a>, <a href="#a84e5cad6b96b065fe2b8f1df5fcfb82c">canIgnoreDenormalInput</a>, <a href="#a1969a1585363ca3069e708b24d19fda4">canOptimizeWithRsq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a33e5f96d603430d2b0ddffb1c06b8580">emitSqrtIEEE2ULP</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a725f0b87c254902624322397fb9301ef">extractValues</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#a8be4fec4d0b6071fb7d7520364fd5378">llvm::FPMathOperator::getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#af50d863c0e5a39ec42b567a9ea58e351">llvm::FPMathOperator::getFPAccuracy</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="#a20b2cf2d81b88d6e6c40a523245424ea">getSqrtF32</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a93270009c3358fba0a61654a9376ab4c">llvm::Value::getUniqueUndroppableUser</a>, <a href="#a0818c291787fd5e8356a06e6cd2b25c3">HasUnsafeFPMath</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a33b84baa49efc1f81ba74a43da0119b5">insertValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a5a5157875fd7fe1af1365889c39bb627">isOneOrNegOne</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#a688bf753f9ca1656480f468df09e6f2b">ST</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a>.</p>


<p>Referenced by <a href="#a7d0e144aac6116637cf1ddbb6363c003">visitIntrinsicInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AC {#af2afde5f3a04ce2c576e01f9a8396ba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a9a9bb93f26a50af2dbf9faa24fa3555a">AMDGPUCodeGenPrepareImpl</a>, <a href="#a725665cbb013d5d85e6ed77a560a65ea">computeKnownFPClass</a>, <a href="#a9b48004ee8ebb9a678049d7abc760328">divHasSpecialOptimization</a>, <a href="#a5d6281f602a2d61050f8e8214c34b16e">getDivNumBits</a>, <a href="#a2c12020d1ecaa1b55d62889b342f4f09">numBitsSigned</a> and <a href="#ac08070db79359ea85bcff1e4fca790c9">numBitsUnsigned</a>.</p>

</div>
</div>

### BreakPhiNodesCache {#a0e35c50e56716a12652b406bb7364b68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const PHINode *, bool&gt; anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::BreakPhiNodesCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a473885e550a15e1490b4de7f4ebd245f">canBreakPHINode</a> and <a href="#aa5bbbb258757741d38a876e5e203aa63">run</a>.</p>

</div>
</div>

### DL {#ad6fa8252711b6da609826cdf5f7076b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a9a9bb93f26a50af2dbf9faa24fa3555a">AMDGPUCodeGenPrepareImpl</a>, <a href="#aa5141fae3a0d75080acb250f4152b974">canWidenScalarExtLoad</a>, <a href="#a725665cbb013d5d85e6ed77a560a65ea">computeKnownFPClass</a>, <a href="#a9b48004ee8ebb9a678049d7abc760328">divHasSpecialOptimization</a>, <a href="#a23dda302945a17be7141fb6e3037f0e8">expandDivRem32</a>, <a href="#a36b7410be1f86b52970bb1381904e282">foldBinOpIntoSelect</a>, <a href="#a5d6281f602a2d61050f8e8214c34b16e">getDivNumBits</a>, <a href="#a2c12020d1ecaa1b55d62889b342f4f09">numBitsSigned</a>, <a href="#ac08070db79359ea85bcff1e4fca790c9">numBitsUnsigned</a>, <a href="#a6161a1346cfae6c3855e6cc1be059407">visitAddrSpaceCastInst</a>, <a href="#a3542900427118365bd67a1d1f4336a50">visitLoadInst</a>, <a href="#a06396b4dd155b05f3faeb9dc674c3787">visitMinNum</a> and <a href="#aef67bcdb0247f9b4b984725fa065e1ce">visitPHINode</a>.</p>

</div>
</div>

### DT {#a84a4f902719b4c907463d2183865709f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DominatorTree* anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a9a9bb93f26a50af2dbf9faa24fa3555a">AMDGPUCodeGenPrepareImpl</a>, <a href="#a725665cbb013d5d85e6ed77a560a65ea">computeKnownFPClass</a> and <a href="#a9b48004ee8ebb9a678049d7abc760328">divHasSpecialOptimization</a>.</p>

</div>
</div>

### F {#a5312450a2b03b7d9dba3cf35eff647fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a9a9bb93f26a50af2dbf9faa24fa3555a">AMDGPUCodeGenPrepareImpl</a>, <a href="#a45499cf71e7324771b2faa3921da99bb">getLdexpF32</a>, <a href="#a20b2cf2d81b88d6e6c40a523245424ea">getSqrtF32</a>, <a href="#aa5bbbb258757741d38a876e5e203aa63">run</a> and <a href="#a3542900427118365bd67a1d1f4336a50">visitLoadInst</a>.</p>

</div>
</div>

### FlowChanged {#a1ba05020d4f1378fd8d9949483c4126b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::FlowChanged = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a1cbb1fa4211e94aed86925b13569004a">visitBinaryOperator</a>.</p>

</div>
</div>

### HasFP32DenormalFlush {#a163079aa347cf24c87658740f923e7a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::HasFP32DenormalFlush</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a9a9bb93f26a50af2dbf9faa24fa3555a">AMDGPUCodeGenPrepareImpl</a>, <a href="#a84e5cad6b96b065fe2b8f1df5fcfb82c">canIgnoreDenormalInput</a>, <a href="#a5ae11456f5955d8499a96c9ba872caaf">emitFrexpDiv</a>, <a href="#a03dc80eab5eb9f0f1ae05d6c3360d988">optimizeWithFDivFast</a> and <a href="#af1f9568f6a2469baf6e85a9dc7b6c588">optimizeWithRcp</a>.</p>

</div>
</div>

### HasUnsafeFPMath {#a0818c291787fd5e8356a06e6cd2b25c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::HasUnsafeFPMath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a9a9bb93f26a50af2dbf9faa24fa3555a">AMDGPUCodeGenPrepareImpl</a>, <a href="#a1969a1585363ca3069e708b24d19fda4">canOptimizeWithRsq</a>, <a href="#ae87e464933c41dbf0ad62bdf89905831">optimizeWithRsq</a>, <a href="#ae534b46b7607eb604ddd8c66baa8d2d1">visitFDiv</a> and <a href="#ae42afee90ff90eb3b8fa78ad91d8858b">visitSqrt</a>.</p>

</div>
</div>

### LdexpF32 {#a3d6fbefdc6099e2c3d250237898938f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::LdexpF32 = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a45499cf71e7324771b2faa3921da99bb">getLdexpF32</a>.</p>

</div>
</div>

### SqrtF32 {#a667c16a40cbcd97a5f346c4275d3725e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::SqrtF32 = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a20b2cf2d81b88d6e6c40a523245424ea">getSqrtF32</a>.</p>

</div>
</div>

### ST {#a688bf753f9ca1656480f468df09e6f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget&amp; anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a9a9bb93f26a50af2dbf9faa24fa3555a">AMDGPUCodeGenPrepareImpl</a>, <a href="#a5ae11456f5955d8499a96c9ba872caaf">emitFrexpDiv</a>, <a href="#a9b0aeaa55a33109c212ca71908c51131">expandDivRem24Impl</a>, <a href="#ada0bab36c5ec58b16a657a0ec09cb641">getFrexpResults</a>, <a href="#aaeababc2d5ffb872b7ef9f71fe5613b3">isLegalFloatingTy</a>, <a href="#a8cacbfce1f2eaebad939051128812350">matchFractPat</a>, <a href="#a35bf25a29df704bcdf8e829ed50361db">needsPromotionToI32</a>, <a href="#a8b47a3cfdac6c8cc7e158e8ee75973d7">replaceMulWithMul24</a>, <a href="#a1cbb1fa4211e94aed86925b13569004a">visitBinaryOperator</a>, <a href="#af24f24b2f8fe671156c06c68760737c5">visitBitreverseIntrinsicInst</a>, <a href="#a45241973f8fd0983638fd7f0282feacd">visitICmpInst</a>, <a href="#aa22a44bbc6646770b4bd139ca4fe2d94">visitSelectInst</a> and <a href="#ae42afee90ff90eb3b8fa78ad91d8858b">visitSqrt</a>.</p>

</div>
</div>

### TLI {#a9ed504e065c1c2acd05e7b4e45b9ea7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a9a9bb93f26a50af2dbf9faa24fa3555a">AMDGPUCodeGenPrepareImpl</a>, <a href="#a725665cbb013d5d85e6ed77a560a65ea">computeKnownFPClass</a>, <a href="#ae534b46b7607eb604ddd8c66baa8d2d1">visitFDiv</a>, <a href="#a06396b4dd155b05f3faeb9dc674c3787">visitMinNum</a> and <a href="#aa22a44bbc6646770b4bd139ca4fe2d94">visitSelectInst</a>.</p>

</div>
</div>

### TM {#ada66ff87dc61a7e208f10f0c207e4ca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUTargetMachine&amp; anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a9a9bb93f26a50af2dbf9faa24fa3555a">AMDGPUCodeGenPrepareImpl</a> and <a href="#a6161a1346cfae6c3855e6cc1be059407">visitAddrSpaceCastInst</a>.</p>

</div>
</div>

### UA {#ab63a07cd0a25baf6900fe7aeaa6fbdeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const UniformityInfo&amp; anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::UA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a9a9bb93f26a50af2dbf9faa24fa3555a">AMDGPUCodeGenPrepareImpl</a>, <a href="#aa5141fae3a0d75080acb250f4152b974">canWidenScalarExtLoad</a>, <a href="#a8b47a3cfdac6c8cc7e158e8ee75973d7">replaceMulWithMul24</a>, <a href="#a1cbb1fa4211e94aed86925b13569004a">visitBinaryOperator</a>, <a href="#af24f24b2f8fe671156c06c68760737c5">visitBitreverseIntrinsicInst</a>, <a href="#a45241973f8fd0983638fd7f0282feacd">visitICmpInst</a> and <a href="#aa22a44bbc6646770b4bd139ca4fe2d94">visitSelectInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
