---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-constantfolding-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{ConstantFolding.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{ConstantFolding.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4fd2e3b5ba38949711abd89082fcfd6">foldConstVectorToAPInt</a> (APInt &amp;Result, Type *DestTy, Constant *C, Type *SrcEltTy, unsigned NumSrcElts, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ea18feb56580024a1693b1f98fb3f6">FoldBitCast</a> (Constant *C, Type *DestTy, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> fold bitcast, symbolically evaluating it with <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a>. <a href="#aa5ea18feb56580024a1693b1f98fb3f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd344dd26b9b6b08fcb676d1c888bc8">ReadDataFromGlobal</a> (Constant *C, uint64_t ByteOffset, unsigned char *CurPtr, unsigned BytesLeft, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursive helper to read bits out of global. <a href="#afcd344dd26b9b6b08fcb676d1c888bc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cb1fc4464f12007218608fadbe3a3f4">FoldReinterpretLoadFromConst</a> (Constant *C, Type *LoadTy, int64_t Offset, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4515378302b14f9df5b64311e4c84a80">SymbolicallyEvaluateBinop</a> (unsigned Opc, Constant *Op0, Constant *Op1, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>One of Op0/Op1 is a constant expression. <a href="#a4515378302b14f9df5b64311e4c84a80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4eef604ff06e2b83fabf52e828c709">CastGEPIndices</a> (Type *SrcElemTy, ArrayRef&lt; Constant * &gt; Ops, Type *ResultTy, GEPNoWrapFlags NW, std::optional&lt; ConstantRange &gt; InRange, const DataLayout &amp;DL, const TargetLibraryInfo *TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If array indices are not pointer-sized integers, explicitly cast them so that they aren't implicitly casted by the getelementptr. <a href="#a6f4eef604ff06e2b83fabf52e828c709">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fc5dce2b300d02414f7b8a99d93d300">SymbolicallyEvaluateGEP</a> (const GEPOperator *GEP, ArrayRef&lt; Constant * &gt; Ops, const DataLayout &amp;DL, const TargetLibraryInfo *TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we can symbolically evaluate the GEP constant expression, do so. <a href="#a4fc5dce2b300d02414f7b8a99d93d300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6e1699b7b98eaaf080f652b08792b9f">ConstantFoldInstOperandsImpl</a> (const Value *InstOrCE, unsigned Opcode, ArrayRef&lt; Constant * &gt; Ops, const DataLayout &amp;DL, const TargetLibraryInfo *TLI, bool AllowNonDeterministic)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to constant fold an instruction with the specified opcode and operands. <a href="#ae6e1699b7b98eaaf080f652b08792b9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a072e839b87b48a47db1efaad541c7dd0">ConstantFoldConstantImpl</a> (const Constant *C, const DataLayout &amp;DL, const TargetLibraryInfo *TLI, SmallDenseMap&lt; Constant *, Constant * &gt; &amp;FoldedOps)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58dab46907515eb8ebaa4a067bf5cf6a">GetConstantFoldFPValue</a> (double V, Type *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1288216e71b28bb0377fdea0d6296879">llvm_fenv_clearexcept</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the floating-point exception state. <a href="#a1288216e71b28bb0377fdea0d6296879">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcffe64ac37ed977768958335d8ef63b">llvm_fenv_testexcept</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if a floating-point exception was raised. <a href="#afcffe64ac37ed977768958335d8ef63b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc6b975e547fa1ea148c5fb2aa0b93fd">FTZPreserveSign</a> (const APFloat &amp;V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56286f3146b1caace49318992efbe3bc">ConstantFoldFP</a> (double(*NativeFP)(double), const APFloat &amp;V, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a955b3b3366fb0fd50d6bd2de30ca58ba">ConstantFoldBinaryFP</a> (double(*NativeFP)(double, double), const APFloat &amp;V, const APFloat &amp;W, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d0da22d172cf90028dcf5fdc8ff2cb8">constantFoldVectorReduce</a> (Intrinsic::ID IID, Constant *Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07d7324865c4b7d490acd0e24b361a97">ConstantFoldSSEConvertToInt</a> (const APFloat &amp;Val, bool roundTowardZero, Type *Ty, bool IsSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to fold an SSE floating point to integer conversion of a constant floating point. <a href="#a07d7324865c4b7d490acd0e24b361a97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af490926429978952543839e7a62ffeb8">getValueAsDouble</a> (ConstantFP *Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8a69c1e7424c26de541dfd0d2cd014c">getConstIntOrUndef</a> (Value *Op, const APInt *&amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada64d8133e1ab5a7c5f739f22949ce93">mayFoldConstrained</a> (ConstrainedFPIntrinsic *CI, APFloat::opStatus St)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the given intrinsic call, which evaluates to constant, is allowed to be folded. <a href="#ada64d8133e1ab5a7c5f739f22949ce93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">RoundingMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cde3eb8b8e3ef69d4a575babb071687">getEvaluationRoundingMode</a> (const ConstrainedFPIntrinsic *CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the rounding mode that should be used for constant evaluation. <a href="#a8cde3eb8b8e3ef69d4a575babb071687">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28ddcf99fafe235217356e423dcdd084">constantFoldCanonicalize</a> (const Type *Ty, const CallBase *CI, const APFloat &amp;Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to constant fold llvm.canonicalize for the given caller and value. <a href="#a28ddcf99fafe235217356e423dcdd084">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f5a312c9865602c873621adc9d8a18">ConstantFoldScalarCall1</a> (StringRef Name, Intrinsic::ID IntrinsicID, Type *Ty, ArrayRef&lt; Constant * &gt; Operands, const TargetLibraryInfo *TLI, const CallBase *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a438bfa60f8534d9b0e347dc50e46e079">evaluateCompare</a> (const APFloat &amp;Op1, const APFloat &amp;Op2, const ConstrainedFPIntrinsic *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8730ce5a51609308adda5bc1de4a859">ConstantFoldLibCall2</a> (StringRef Name, Type *Ty, ArrayRef&lt; Constant * &gt; Operands, const TargetLibraryInfo *TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72190dad796891a1a5a59d64044000dc">ConstantFoldIntrinsicCall2</a> (Intrinsic::ID IntrinsicID, Type *Ty, ArrayRef&lt; Constant * &gt; Operands, const CallBase *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeae4a07f0fe95525d21343b3139276bd">ConstantFoldAMDGCNCubeIntrinsic</a> (Intrinsic::ID IntrinsicID, const APFloat &amp;S0, const APFloat &amp;S1, const APFloat &amp;S2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ef6764a965598939c3ecf43eeb9fb0">ConstantFoldAMDGCNPermIntrinsic</a> (ArrayRef&lt; Constant * &gt; Operands, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a505a295564c761e2006b8e48647f6f7d">ConstantFoldScalarCall3</a> (StringRef Name, Intrinsic::ID IntrinsicID, Type *Ty, ArrayRef&lt; Constant * &gt; Operands, const TargetLibraryInfo *TLI, const CallBase *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c22952bdb1f70670aed956cb8afa52">ConstantFoldScalarCall</a> (StringRef Name, Intrinsic::ID IntrinsicID, Type *Ty, ArrayRef&lt; Constant * &gt; Operands, const TargetLibraryInfo *TLI, const CallBase *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad60130f0b45a3ff1e759b010afefb94d">ConstantFoldFixedVectorCall</a> (StringRef Name, Intrinsic::ID IntrinsicID, FixedVectorType *FVTy, ArrayRef&lt; Constant * &gt; Operands, const DataLayout &amp;DL, const TargetLibraryInfo *TLI, const CallBase *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0826c581880101a3069e74c70c76dad8">ConstantFoldScalableVectorCall</a> (StringRef Name, Intrinsic::ID IntrinsicID, ScalableVectorType *SVTy, ArrayRef&lt; Constant * &gt; Operands, const DataLayout &amp;DL, const TargetLibraryInfo *TLI, const CallBase *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86456cb345c788177fa0b43a40519723">ConstantFoldScalarFrexpCall</a> (Constant *Op, Type *IntTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a294b49713de411cd8aadad66d82f205b">ConstantFoldStructCall</a> (StringRef Name, Intrinsic::ID IntrinsicID, StructType *StTy, ArrayRef&lt; Constant * &gt; Operands, const DataLayout &amp;DL, const TargetLibraryInfo *TLI, const CallBase *Call)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle intrinsics that return tuples, which may be tuples of vectors. <a href="#a294b49713de411cd8aadad66d82f205b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### CastGEPIndices() {#a6f4eef604ff06e2b83fabf52e828c709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::CastGEPIndices (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcElemTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Ops, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultTy, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> NW, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt; InRange, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If array indices are not pointer-sized integers, explicitly cast them so that they aren't implicitly casted by the getelementptr.</p>

<p>Definition at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e655fd99a56d50b071fc26d8db5fd5b">llvm::ConstantFoldConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a06dc25da1f16f389f5244304e8d33127">llvm::CastInst::getCastOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae4d4490a35a575d97166684fb15f8662">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a99d4bfe49182f8d80abb1960f2c12d46">llvm::GetElementPtrInst::getIndexedType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#aaac99696c5f396905a86fa853f41614f">InRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a4fc5dce2b300d02414f7b8a99d93d300">SymbolicallyEvaluateGEP</a>.</p>

</div>
</div>

### ConstantFoldAMDGCNCubeIntrinsic() {#aeae4a07f0fe95525d21343b3139276bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat anonymous{ConstantFolding.cpp}::ConstantFoldAMDGCNCubeIntrinsic (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrinsicID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; S0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; S1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; S2)</td>
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



<p>Definition at line 3374 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2816e84a08c108d18bc4665bc1817e01">llvm::abs</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a643f8cd038a6fa41604fe8e3df11f977">llvm::APFloat::getSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a763d4ccd87f2c21d2079796c0c9cd51a">llvm::APFloat::isNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a2b901c3a0625a7d7173e9bd4864e2775">llvm::APFloat::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a67847bcacd8e684f0449be8f1ec90f29">llvm::APFloat::isNonZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>.</p>


<p>Referenced by <a href="#a505a295564c761e2006b8e48647f6f7d">ConstantFoldScalarCall3</a>.</p>

</div>
</div>

### ConstantFoldAMDGCNPermIntrinsic() {#a48ef6764a965598939c3ecf43eeb9fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldAMDGCNPermIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 3429 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a29177946d0b9d5003e7a952a9684b797">llvm::APInt::extractBitsAsZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="#ab8a69c1e7424c26de541dfd0d2cd014c">getConstIntOrUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aabe301a4f18d38478700ad44ba2245bc">llvm::APInt::insertBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="#a505a295564c761e2006b8e48647f6f7d">ConstantFoldScalarCall3</a>.</p>

</div>
</div>

### ConstantFoldBinaryFP() {#a955b3b3366fb0fd50d6bd2de30ca58ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldBinaryFP (double(*)(double, double) NativeFP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; W, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1960 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="#a58dab46907515eb8ebaa4a067bf5cf6a">GetConstantFoldFPValue</a>, <a href="#a1288216e71b28bb0377fdea0d6296879">llvm_fenv_clearexcept</a> and <a href="#afcffe64ac37ed977768958335d8ef63b">llvm_fenv_testexcept</a>.</p>


<p>Referenced by <a href="#a72190dad796891a1a5a59d64044000dc">ConstantFoldIntrinsicCall2</a>, <a href="#af8730ce5a51609308adda5bc1de4a859">ConstantFoldLibCall2</a>, <a href="#aa8f5a312c9865602c873621adc9d8a18">ConstantFoldScalarCall1</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2f579c2fbf1fda44d35d059d9799eddc">llvm::isMathLibCallNoop</a>.</p>

</div>
</div>

### constantFoldCanonicalize() {#a28ddcf99fafe235217356e423dcdd084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::constantFoldCanonicalize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Src)</td>
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

<p>Try to constant fold llvm.canonicalize for the given caller and value.</p>

<p>Definition at line 2128 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893ab6083e266013055b6c2ef85b1e47444c">llvm::DenormalMode::Dynamic</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aaf03062dde511bcc74b5d01b0a2b5736">llvm::Function::getDenormalMode</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#afc06bc91a5873ec7efe616b733f2c5c8">llvm::DenormalMode::getIEEE</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af591f8d18d0d9773192a0ffcca41796e">llvm::APFloat::getZero</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893ad6fd23eb0b98a2d4551582753191b6da">llvm::DenormalMode::IEEE</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a1b79f1995991b0a757a4d04969c3717f">llvm::DenormalMode::Input</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#aa1be940c9e7d0c7ed20dfdaf5731b082">llvm::DenormalMode::Output</a> and <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893a7de61db082dcdc6e8d34d1c5fd2e9757">llvm::DenormalMode::PositiveZero</a>.</p>


<p>Referenced by <a href="#aa8f5a312c9865602c873621adc9d8a18">ConstantFoldScalarCall1</a>.</p>

</div>
</div>

### ConstantFoldConstantImpl() {#a072e839b87b48a47db1efaad541c7dd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldConstantImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &amp; FoldedOps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1086 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a072e839b87b48a47db1efaad541c7dd0">ConstantFoldConstantImpl</a>, <a href="#ae6e1699b7b98eaaf080f652b08792b9f">ConstantFoldInstOperandsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5e655fd99a56d50b071fc26d8db5fd5b">llvm::ConstantFoldConstant</a>, <a href="#a072e839b87b48a47db1efaad541c7dd0">ConstantFoldConstantImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab6be6270337c6f7620007555247401ce">llvm::ConstantFoldInstruction</a>.</p>

</div>
</div>

### ConstantFoldFixedVectorCall() {#ad60130f0b45a3ff1e759b010afefb94d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldFixedVectorCall (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrinsicID, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * FVTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call)</td>
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



<p>Definition at line 3629 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad95650d790f6f9d252cf0cd0e0094368">llvm::ConstantFoldLoadFromConstPtr</a>, <a href="#a60c22952bdb1f70670aed956cb8afa52">ConstantFoldScalarCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#acd530d0571f320d47d37e7ae51cf70ff">llvm::Constant::getAggregateElement</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a1893caf878859959ba6a3d5442ef1439">llvm::FixedVectorType::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad6db62129ba3650d98ce56fa03ab5f1">llvm::isVectorIntrinsicWithScalarOpAtArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4e3a3843bf5e85d3d55c2a252ec235bd">llvm::ConstantFoldCall</a>.</p>

</div>
</div>

### ConstantFoldFP() {#a56286f3146b1caace49318992efbe3bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldFP (double(*)(double) NativeFP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1934 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="#a58dab46907515eb8ebaa4a067bf5cf6a">GetConstantFoldFPValue</a>, <a href="#a1288216e71b28bb0377fdea0d6296879">llvm_fenv_clearexcept</a> and <a href="#afcffe64ac37ed977768958335d8ef63b">llvm_fenv_testexcept</a>.</p>


<p>Referenced by <a href="#aa8f5a312c9865602c873621adc9d8a18">ConstantFoldScalarCall1</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2f579c2fbf1fda44d35d059d9799eddc">llvm::isMathLibCallNoop</a>.</p>

</div>
</div>

### ConstantFoldInstOperandsImpl() {#ae6e1699b7b98eaaf080f652b08792b9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldInstOperandsImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InstOrCE, unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Ops, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, bool AllowNonDeterministic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to constant fold an instruction with the specified opcode and operands.</p>


<p>If successful, the constant result is returned, if not, null is returned. Note that this function can fail when attempting to fold instructions like loads and stores, which have no constant expression form.</p>


<p>Definition at line 986 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20f356124998d05f7e605549cc2dda91">llvm::canConstantFoldCallTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a964455f36837281d37f2a44e2fcb4cca">llvm::ConstantFoldBinaryOpOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4e3a3843bf5e85d3d55c2a252ec235bd">llvm::ConstantFoldCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a557be4c1daf6eb2611b214f927dccee2">llvm::ConstantFoldExtractValueInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1934978a43ce45ca0ec7b837e31d4ebc">llvm::ConstantFoldFPInstOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad7fa9b738742521d0a684cec016ef47e">llvm::ConstantFoldInsertValueInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad95650d790f6f9d252cf0cd0e0094368">llvm::ConstantFoldLoadFromConstPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c89e0918b007ef2cf1d6b03c4b4948">llvm::ConstantFoldSelectInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6810c4cb05b49909862249d3b3afa2af">llvm::ConstantFoldUnaryOpOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a078455f9a6da73bc84f24700a81d19d7">llvm::ConstantExpr::getExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae4d4490a35a575d97166684fb15f8662">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a64d6bd55aa4447bb25f1361993223450">llvm::ConstantExpr::getInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a6f6506f0bc515fe29da3b58565300017">llvm::ConstantExpr::getShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a27997849d8982bf226891024fd68daee">llvm::Instruction::isCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8a7ef433279aabf7f30fa5504a4d4ef">llvm::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a7baf4632513de0fccabc65793c6b8dae">llvm::ConstantExpr::isSupportedGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae6249022aded13ad98775c11881bc117">llvm::Instruction::isUnaryOp</a> and <a href="#a4fc5dce2b300d02414f7b8a99d93d300">SymbolicallyEvaluateGEP</a>.</p>


<p>Referenced by <a href="#a072e839b87b48a47db1efaad541c7dd0">ConstantFoldConstantImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8bd5f9b3852cfb092d927ef2b04c7f6b">llvm::ConstantFoldInstOperands</a>.</p>

</div>
</div>

### ConstantFoldIntrinsicCall2() {#a72190dad796891a1a5a59d64044000dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2 (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrinsicID, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call)</td>
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



<p>Definition at line 2903 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2816e84a08c108d18bc4665bc1817e01">llvm::abs</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a38e964f0cadf077725453884734a6c99">llvm::APInt::abs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a44602b2ea058f08b290a8fa0185909d1">llvm::APFloat::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ae7fe7691e456e49addd866aa23896387">llvm::APFloat::changeSign</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a5769f1da829d6f6400b486d8e34e317f">llvm::ICmpInst::compare</a>, <a href="#a955b3b3366fb0fd50d6bd2de30ca58ba">ConstantFoldBinaryFP</a>, <a href="#a07d7324865c4b7d490acd0e24b361a97">ConstantFoldSSEConvertToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a37733c4c22afc6a48194783dbd25487c">llvm::APFloat::convertToDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a8269fab998356ea27a76ad45bd6cc8fe">llvm::APFloat::convertToFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a1cfd2be1063599384fd6e6172264a979">llvm::APFloat::copySign</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8bad27827f46bca6baf814cbd2b64e84">llvm::APInt::countl_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a107d394b970c9f03a486a15cdd08f0df">llvm::APFloat::divide</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a438bfa60f8534d9b0e347dc50e46e079">evaluateCompare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da3ab665df1666568d7eac3b1373106638">llvm::fcNegInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dab003a118cd0b76a814ba4dfc7077034a">llvm::fcNegNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da023ad3d9b33a1af5eb90b8b543fb3ccb">llvm::fcNegSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da1e8072411cd3959aa091c3cae8006dc0">llvm::fcNegZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dada0d259988860d7a2f882aa40b25fee1">llvm::fcPosInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da052ace75708c251359ff22dd036417a6">llvm::fcPosNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dad0940edb5f5bf512669b72928b527d0c">llvm::fcPosSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da7ace586671df3e62fa392d5144a8b3da">llvm::fcPosZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da05bb099c0a65e5b835ed8cd0b326df7c">llvm::fcQNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da9d366dced7a639841b0ced40c82ccb28">llvm::fcSNan</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvvm/#a901511239676c0c4134f51517c356f2f">llvm::nvvm::FMinFMaxIsXorSignAbs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvvm/#af5743b75c1b0cc4163e2e6d6081425dc">llvm::nvvm::FMinFMaxPropagatesNaNs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvvm/#ac2a2bfd8d0599290380d8b3c4ed823eb">llvm::nvvm::FMinFMaxShouldFTZ</a>, <a href="#acc6b975e547fa1ea148c5fb2aa0b93fd">FTZPreserveSign</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="#ab8a69c1e7424c26de541dfd0d2cd014c">getConstIntOrUndef</a>, <a href="#a8cde3eb8b8e3ef69d4a575babb071687">getEvaluationRoundingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/minmaxintrinsic/#a988ae1c84a3ad7f92b7f94ac90ba9b79">llvm::MinMaxIntrinsic::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/minmaxintrinsic/#a4b6b84b97c4ee2f0023bfd66097ca424">llvm::MinMaxIntrinsic::getSaturationPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a643f8cd038a6fa41604fe8e3df11f977">llvm::APFloat::getSemantics</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a75071440d60c24178371ca1299f4ef07">llvm::ConstantFP::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9">llvm::Type::HalfTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86415bb448a78ef1fed893f9eb0f5d06">llvm::APFloatBase::IEEEhalf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a43c6c871e61d6071a20a680aa2a08009">llvm::APFloat::isDenormal</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1f04e382556a817950fd0390aeaf9b0e">llvm::APInt::isMinSignedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a763d4ccd87f2c21d2079796c0c9cd51a">llvm::APFloat::isNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a2b901c3a0625a7d7173e9bd4864e2775">llvm::APFloat::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ad1af637e15f22d5e9b99800a0fabe12c">llvm::APFloat::isNegInfinity</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a43257671f610226d09cfb0ad8d5e7d6b">llvm::APFloat::isNormal</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a3b1180f8b5b3af0d2aa0876e590f8690">llvm::APFloat::isPosInfinity</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a833f6b183e2adebde0fb463e6a6297fe">llvm::APFloat::isSignaling</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9aaed17970b55e9e1bfa906822ea7b71">llvm::APFloat::isZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38dcdde63d81fbda1d22dffd1a27b343">llvm::maximum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a636de400e4dd2bc090b729329a99e75b">llvm::maxnum</a>, <a href="#ada64d8133e1ab5a7c5f739f22949ce93">mayFoldConstrained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae2f7e8a5325f48bbbdaec78e5d6c320c">llvm::minimum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa656aa475d13ec6a900414eadabe86b0">llvm::minnum</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ac3126d0302ebe7754bf962fdaa25e286">llvm::APFloat::mod</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a82567bb6632fa71c7c727b9464368173">llvm::APFloat::multiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a694293446a074c3d64270e7671bb5052">llvm::APInt::sadd_ov</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3c1e0381aeb551ad0ba58effe9232f97">llvm::APInt::sadd_sat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7757f52e61c8e086d79bdd166f50bb02">llvm::scalbn</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3d430216d32f4363e4df154599b98055">llvm::APInt::sgt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adafa9575780f9246d1df0b7e2a619356">llvm::APInt::slt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac155d7c568fc1aba25723e77b6888908">llvm::APInt::smul_ov</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ae324de5041feaf7eb8433221cdaca9aa">llvm::APInt::ssub_ov</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af888cb3cadd9a4e5f422c96e5674de88">llvm::APInt::ssub_sat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a27bc3a1b1f84258afe7e981fb707f646">llvm::APFloat::subtract</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8268fbc3014081004056f6466452c904">llvm::APInt::uadd_ov</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab4c04665274d4f30d732639dc055821c">llvm::APInt::uadd_sat</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a46a7cbf3724080a5f4f4c7e7a4551e26">llvm::APInt::ugt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a028f4d1eead63cc33499ce3459bd27c7">llvm::APInt::umul_ov</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d622af4cca05108d8d7eb9bfd79977">llvm::APInt::usub_ov</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a059dc64e71df065315050d2270cbfba5">llvm::APInt::usub_sat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea8fbf7fa79dc6962b4adb8550a87f">llvm::ConstantFoldBinaryIntrinsic</a> and <a href="#a60c22952bdb1f70670aed956cb8afa52">ConstantFoldScalarCall</a>.</p>

</div>
</div>

### ConstantFoldLibCall2() {#af8730ce5a51609308adda5bc1de4a859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldLibCall2 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
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



<p>Definition at line 2839 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="#a955b3b3366fb0fd50d6bd2de30ca58ba">ConstantFoldBinaryFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a97cfbbed8869e3582142012a071a9052">llvm::TargetLibraryInfo::getLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a54699e3f128acda6003afc11d3027f6c">llvm::TargetLibraryInfo::has</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9aaed17970b55e9e1bfa906822ea7b71">llvm::APFloat::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154ea2552a9aa363fba3520d8e8e1a7eca566">llvm::NotLibFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aa8092c6b52c0412d8198a63bc995761e9">llvm::APFloatBase::opOK</a>.</p>


<p>Referenced by <a href="#a60c22952bdb1f70670aed956cb8afa52">ConstantFoldScalarCall</a>.</p>

</div>
</div>

### ConstantFoldScalableVectorCall() {#a0826c581880101a3069e74c70c76dad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldScalableVectorCall (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrinsicID, <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> * SVTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call)</td>
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



<p>Definition at line 3745 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4e3a3843bf5e85d3d55c2a252ec235bd">llvm::ConstantFoldCall</a>.</p>

</div>
</div>

### ConstantFoldScalarCall() {#a60c22952bdb1f70670aed956cb8afa52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrinsicID, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call)</td>
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



<p>Definition at line 3606 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="#a72190dad796891a1a5a59d64044000dc">ConstantFoldIntrinsicCall2</a>, <a href="#af8730ce5a51609308adda5bc1de4a859">ConstantFoldLibCall2</a>, <a href="#aa8f5a312c9865602c873621adc9d8a18">ConstantFoldScalarCall1</a>, <a href="#a505a295564c761e2006b8e48647f6f7d">ConstantFoldScalarCall3</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4e3a3843bf5e85d3d55c2a252ec235bd">llvm::ConstantFoldCall</a>, <a href="#ad60130f0b45a3ff1e759b010afefb94d">ConstantFoldFixedVectorCall</a> and <a href="#a294b49713de411cd8aadad66d82f205b">ConstantFoldStructCall</a>.</p>

</div>
</div>

### ConstantFoldScalarCall1() {#aa8f5a312c9865602c873621adc9d8a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrinsicID, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call)</td>
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



<p>Definition at line 2177 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a955b3b3366fb0fd50d6bd2de30ca58ba">ConstantFoldBinaryFP</a>, <a href="#a28ddcf99fafe235217356e423dcdd084">constantFoldCanonicalize</a>, <a href="#a56286f3146b1caace49318992efbe3bc">ConstantFoldFP</a>, <a href="#a07d7324865c4b7d490acd0e24b361a97">ConstantFoldSSEConvertToInt</a>, <a href="#a7d0da22d172cf90028dcf5fdc8ff2cb8">constantFoldVectorReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca971fd8cc345d8bd9f92e9f7d88fdf20c">llvm::Dynamic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630ad8009e7c0ce2967115e856052243ac62">llvm::fp::ebIgnore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630a5dfc3e95e600e911e26874be1f27dba7">llvm::fp::ebStrict</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvvm/#a5edd8f6f58f303fd414660763719f69f">llvm::nvvm::FPToIntegerIntrinsicResultIsSigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvvm/#a7bb6e57ea323880d9d4baf779c0aa217">llvm::nvvm::FPToIntegerIntrinsicShouldFTZ</a>, <a href="#acc6b975e547fa1ea148c5fb2aa0b93fd">FTZPreserveSign</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="#a58dab46907515eb8ebaa4a067bf5cf6a">GetConstantFoldFPValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvvm/#a6aebf445d83116942f4b690d6d40a4f8">llvm::nvvm::GetFPToIntegerRoundingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a97cfbbed8869e3582142012a071a9052">llvm::TargetLibraryInfo::getLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a7f8802ce4f0a7839abb4c836cb52138a">llvm::APFloat::getOne</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21b1f2d0effa0506f01cb146823de6a2">llvm::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a010e22ea9432c4b7d5962406932ed27b">llvm::APFloat::getQNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a643f8cd038a6fa41604fe8e3df11f977">llvm::APFloat::getSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="#af490926429978952543839e7a62ffeb8">getValueAsDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a54699e3f128acda6003afc11d3027f6c">llvm::TargetLibraryInfo::has</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86415bb448a78ef1fed893f9eb0f5d06">llvm::APFloatBase::IEEEhalf</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a2b901c3a0625a7d7173e9bd4864e2775">llvm::APFloat::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9aaed17970b55e9e1bfa906822ea7b71">llvm::APFloat::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4bd88bd90f06f0e66d0b20f877cd1e">llvm::log2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae2f7e8a5325f48bbbdaec78e5d6c320c">llvm::minimum</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab0fdc79bb75e8fe845f98e2199f9d451">llvm::APFloat::next</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154ea2552a9aa363fba3520d8e8e1a7eca566">llvm::NotLibFunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b03ed78a8e299bde6d26a8793cd4e06">llvm::NullPointerIsDefined</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aaba98149aef517089f9868bde5b8c41bc">llvm::APFloatBase::opInexact</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aabb85c4ca7e984a8fc43c9276a64cff10">llvm::APFloatBase::opInvalidOp</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aa8092c6b52c0412d8198a63bc995761e9">llvm::APFloatBase::opOK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/numbers/#aeedab8a7355d9f65b7c2ba263ddc2065">llvm::numbers::pi</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1289beadf5d399fa4a2c64e18903ac90">llvm::APFloatBase::rmNearestTiesToAway</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1ba0fce5daa7f716936cabcf00373f0e">llvm::APFloatBase::rmTowardNegative</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a8777e7a3e4355e29cc0993a935225db3">llvm::APFloatBase::rmTowardPositive</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a482d9cf95b588eb05cefeaa5c05be9a3">llvm::APFloatBase::rmTowardZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ae4eca54fe8b71670e3bd3a2b18469d73">llvm::APFloat::roundToIntegral</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>


<p>Referenced by <a href="#a60c22952bdb1f70670aed956cb8afa52">ConstantFoldScalarCall</a>.</p>

</div>
</div>

### ConstantFoldScalarCall3() {#a505a295564c761e2006b8e48647f6f7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrinsicID, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call)</td>
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



<p>Definition at line 3469 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6006923d1a3139d70abc8f6552a7960">llvm::APInt::ashr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aeae4a07f0fe95525d21343b3139276bd">ConstantFoldAMDGCNCubeIntrinsic</a>, <a href="#a48ef6764a965598939c3ecf43eeb9fb0">ConstantFoldAMDGCNPermIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9180d9a8c1fc9693c4b0a50937e904e6">llvm::APFloat::fusedMultiplyAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="#ab8a69c1e7424c26de541dfd0d2cd014c">getConstIntOrUndef</a>, <a href="#a8cde3eb8b8e3ef69d4a575babb071687">getEvaluationRoundingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9aaed17970b55e9e1bfa906822ea7b71">llvm::APFloat::isZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af34549c39d6f741fbdaf9a795aa306e9">llvm::APInt::lshr</a>, <a href="#ada64d8133e1ab5a7c5f739f22949ce93">mayFoldConstrained</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a9b5fc98b47d44d1150d3610bdfab1430">llvm::APInt::sextOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acb9c55b6986369948507ca5241b4e411">llvm::APInt::shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a6d2ea807ef8eb6d40335d6f11edf942c">llvm::APIntOps::smax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a688eca8fbe6295f4b002f1e705d3e916">llvm::APIntOps::smin</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a4e3a2187cacdec76028617a403c47d89">llvm::APInt::urem</a>.</p>


<p>Referenced by <a href="#a60c22952bdb1f70670aed956cb8afa52">ConstantFoldScalarCall</a>.</p>

</div>
</div>

### ConstantFoldScalarFrexpCall() {#a86456cb345c788177fa0b43a40519723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Constant *, Constant * &gt; anonymous{ConstantFolding.cpp}::ConstantFoldScalarFrexpCall (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * IntTy)</td>
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



<p>Definition at line 3764 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a53d315bdfbe8ab3760ebbea3faebc5f8">llvm::frexp</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a9ad53d2a00a6fb861b3a048c6592b742">llvm::ConstantInt::getSigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a72c0ccd36e5b427a58262f9481c9c61c">llvm::APFloat::isFinite</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>


<p>Referenced by <a href="#a294b49713de411cd8aadad66d82f205b">ConstantFoldStructCall</a>.</p>

</div>
</div>

### ConstantFoldSSEConvertToInt() {#a07d7324865c4b7d490acd0e24b361a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldSSEConvertToInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Val, bool roundTowardZero, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to fold an SSE floating point to integer conversion of a constant floating point.</p>


<p>If roundTowardZero is false, the default IEEE rounding is used (toward nearest, ties to even). This matches the behavior of the non-truncating SSE instructions in the default rounding mode. The desired integer type Ty is used to select how many bits are available for the result. Returns null if the conversion cannot be performed, otherwise returns the <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> value resulting from the conversion.</p>


<p>Definition at line 2040 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aae1f09de4bf1aab27149a7d328715e30">llvm::APFloat::convertToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99416758c13252bef45320a6ba6aa09c">llvm::MutableArrayRef</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aaba98149aef517089f9868bde5b8c41bc">llvm::APFloatBase::opInexact</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aa8092c6b52c0412d8198a63bc995761e9">llvm::APFloatBase::opOK</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a482d9cf95b588eb05cefeaa5c05be9a3">llvm::APFloatBase::rmTowardZero</a>.</p>


<p>Referenced by <a href="#a72190dad796891a1a5a59d64044000dc">ConstantFoldIntrinsicCall2</a> and <a href="#aa8f5a312c9865602c873621adc9d8a18">ConstantFoldScalarCall1</a>.</p>

</div>
</div>

### ConstantFoldStructCall() {#a294b49713de411cd8aadad66d82f205b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::ConstantFoldStructCall (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrinsicID, <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * StTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call)</td>
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

<p>Handle intrinsics that return tuples, which may be tuples of vectors.</p>

<p>Definition at line 3787 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="#a60c22952bdb1f70670aed956cb8afa52">ConstantFoldScalarCall</a>, <a href="#a86456cb345c788177fa0b43a40519723">ConstantFoldScalarFrexpCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad1d50278883f39969187bceabe068acf">llvm::Type::getContainedType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4e3a3843bf5e85d3d55c2a252ec235bd">llvm::ConstantFoldCall</a>.</p>

</div>
</div>

### constantFoldVectorReduce() {#a7d0da22d172cf90028dcf5fdc8ff2cb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::constantFoldVectorReduce (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1972 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a1893caf878859959ba6a3d5442ef1439">llvm::FixedVectorType::getNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a6d2ea807ef8eb6d40335d6f11edf942c">llvm::APIntOps::smax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a688eca8fbe6295f4b002f1e705d3e916">llvm::APIntOps::smin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ad790c9bc3f8cce98f4d714041f2e4589">llvm::APIntOps::umax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a954b694b93f10aba174cb5d0378975b2">llvm::APIntOps::umin</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#aa8f5a312c9865602c873621adc9d8a18">ConstantFoldScalarCall1</a>.</p>

</div>
</div>

### evaluateCompare() {#a438bfa60f8534d9b0e347dc50e46e079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::evaluateCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Op2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic">ConstrainedFPIntrinsic</a> * Call)</td>
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



<p>Definition at line 2821 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#a659fef3f4c95c68c4b090e52b3a6eaeb">llvm::FCmpInst::compare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a763d4ccd87f2c21d2079796c0c9cd51a">llvm::APFloat::isNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a833f6b183e2adebde0fb463e6a6297fe">llvm::APFloat::isSignaling</a>, <a href="#ada64d8133e1ab5a7c5f739f22949ce93">mayFoldConstrained</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aabb85c4ca7e984a8fc43c9276a64cff10">llvm::APFloatBase::opInvalidOp</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aa8092c6b52c0412d8198a63bc995761e9">llvm::APFloatBase::opOK</a>.</p>


<p>Referenced by <a href="#a72190dad796891a1a5a59d64044000dc">ConstantFoldIntrinsicCall2</a>.</p>

</div>
</div>

### FoldBitCast() {#aa5ea18feb56580024a1693b1f98fb3f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::FoldBitCast (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DestTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> fold bitcast, symbolically evaluating it with <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a>.</p>


<p>This always returns a non-null constant, but it may be a <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a> if unfoldable.</p>


<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a964455f36837281d37f2a44e2fcb4cca">llvm::ConstantFoldBinaryOpOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a65bb0005c2f40b94623bae2e9a51fe48">llvm::ConstantFoldLoadFromUniformValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#aa5ea18feb56580024a1693b1f98fb3f6">FoldBitCast</a>, <a href="#ab4fd2e3b5ba38949711abd89082fcfd6">foldConstVectorToAPInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae79d05dd3d0b05e080e08f8c5c33f880">llvm::ConstantExpr::getBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#adc21598ac33ea9d50f3a939f26a28940">llvm::Type::getFltSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="#aa5ea18feb56580024a1693b1f98fb3f6">FoldBitCast</a>, <a href="#a6cb1fc4464f12007218608fadbe3a3f4">FoldReinterpretLoadFromConst</a> and <a href="#afcd344dd26b9b6b08fcb676d1c888bc8">ReadDataFromGlobal</a>.</p>

</div>
</div>

### foldConstVectorToAPInt() {#ab4fd2e3b5ba38949711abd89082fcfd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::foldConstVectorToAPInt (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DestTy, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcEltTy, unsigned NumSrcElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae79d05dd3d0b05e080e08f8c5c33f880">llvm::ConstantExpr::getBitCast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>.</p>


<p>Referenced by <a href="#aa5ea18feb56580024a1693b1f98fb3f6">FoldBitCast</a>.</p>

</div>
</div>

### FoldReinterpretLoadFromConst() {#a6cb1fc4464f12007218608fadbe3a3f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::FoldReinterpretLoadFromConst (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LoadTy, int64_t Offset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aa5ea18feb56580024a1693b1f98fb3f6">FoldBitCast</a>, <a href="#a6cb1fc4464f12007218608fadbe3a3f4">FoldReinterpretLoadFromConst</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a02560cda155aaed54314383bed827d60">llvm::ConstantExpr::getIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ab03652069eab17006c51f00c261a6a44">llvm::Type::isPtrOrPtrVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ab549082d9dfb91ec9a8dc06601d54855">llvm::Type::isX86_AMXTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#afcd344dd26b9b6b08fcb676d1c888bc8">ReadDataFromGlobal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8f2a6934eba2671f2fe2a121f2e9e4e9">llvm::ConstantFoldLoadFromConst</a> and <a href="#a6cb1fc4464f12007218608fadbe3a3f4">FoldReinterpretLoadFromConst</a>.</p>

</div>
</div>

### FTZPreserveSign() {#acc6b975e547fa1ea148c5fb2aa0b93fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APFloat anonymous{ConstantFolding.cpp}::FTZPreserveSign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; V)</td>
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



<p>Definition at line 1928 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af591f8d18d0d9773192a0ffcca41796e">llvm::APFloat::getZero</a>.</p>


<p>Referenced by <a href="#a72190dad796891a1a5a59d64044000dc">ConstantFoldIntrinsicCall2</a> and <a href="#aa8f5a312c9865602c873621adc9d8a18">ConstantFoldScalarCall1</a>.</p>

</div>
</div>

### GetConstantFoldFPValue() {#a58dab46907515eb8ebaa4a067bf5cf6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::GetConstantFoldFPValue (double V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1888 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>


<p>Referenced by <a href="#a955b3b3366fb0fd50d6bd2de30ca58ba">ConstantFoldBinaryFP</a>, <a href="#a56286f3146b1caace49318992efbe3bc">ConstantFoldFP</a> and <a href="#aa8f5a312c9865602c873621adc9d8a18">ConstantFoldScalarCall1</a>.</p>

</div>
</div>

### getConstIntOrUndef() {#ab8a69c1e7424c26de541dfd0d2cd014c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ConstantFolding.cpp}::getConstIntOrUndef (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> *&amp; C)</td>
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



<p>Definition at line 2072 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a48ef6764a965598939c3ecf43eeb9fb0">ConstantFoldAMDGCNPermIntrinsic</a>, <a href="#a72190dad796891a1a5a59d64044000dc">ConstantFoldIntrinsicCall2</a> and <a href="#a505a295564c761e2006b8e48647f6f7d">ConstantFoldScalarCall3</a>.</p>

</div>
</div>

### getEvaluationRoundingMode() {#a8cde3eb8b8e3ef69d4a575babb071687}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RoundingMode anonymous{ConstantFolding.cpp}::getEvaluationRoundingMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic">ConstrainedFPIntrinsic</a> * CI)</td>
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

<p>Returns the rounding mode that should be used for constant evaluation.</p>

<p>Definition at line 2116 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca971fd8cc345d8bd9f92e9f7d88fdf20c">llvm::Dynamic</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic/#a4fc25c0fccec261829e187a058a772a9">llvm::ConstrainedFPIntrinsic::getRoundingMode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca44467144e3b6bdac3e85ef6f90e7d832">llvm::NearestTiesToEven</a>.</p>


<p>Referenced by <a href="#a72190dad796891a1a5a59d64044000dc">ConstantFoldIntrinsicCall2</a> and <a href="#a505a295564c761e2006b8e48647f6f7d">ConstantFoldScalarCall3</a>.</p>

</div>
</div>

### getValueAsDouble() {#af490926429978952543839e7a62ffeb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double anonymous{ConstantFolding.cpp}::getValueAsDouble (<a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2060 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a37733c4c22afc6a48194783dbd25487c">llvm::APFloat::convertToDouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>


<p>Referenced by <a href="#aa8f5a312c9865602c873621adc9d8a18">ConstantFoldScalarCall1</a>.</p>

</div>
</div>

### llvm\_fenv\_clearexcept() {#a1288216e71b28bb0377fdea0d6296879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ConstantFolding.cpp}::llvm_fenv_clearexcept ()</td>
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

<p>Clear the floating-point exception state.</p>

<p>Definition at line 1909 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>Referenced by <a href="#a955b3b3366fb0fd50d6bd2de30ca58ba">ConstantFoldBinaryFP</a> and <a href="#a56286f3146b1caace49318992efbe3bc">ConstantFoldFP</a>.</p>

</div>
</div>

### llvm\_fenv\_testexcept() {#afcffe64ac37ed977768958335d8ef63b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ConstantFolding.cpp}::llvm_fenv_testexcept ()</td>
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

<p>Test if a floating-point exception was raised.</p>

<p>Definition at line 1917 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>Referenced by <a href="#a955b3b3366fb0fd50d6bd2de30ca58ba">ConstantFoldBinaryFP</a> and <a href="#a56286f3146b1caace49318992efbe3bc">ConstantFoldFP</a>.</p>

</div>
</div>

### mayFoldConstrained() {#ada64d8133e1ab5a7c5f739f22949ce93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ConstantFolding.cpp}::mayFoldConstrained (<a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic">ConstrainedFPIntrinsic</a> * CI, APFloat::opStatus St)</td>
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

<p>Checks if the given intrinsic call, which evaluates to constant, is allowed to be folded.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CI</td>
<td class="doxyParamItemDescription"><p>Constrained intrinsic call.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">St</td>
<td class="doxyParamItemDescription"><p>Exception flags raised during constant evaluation.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2089 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca971fd8cc345d8bd9f92e9f7d88fdf20c">llvm::Dynamic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630a5dfc3e95e600e911e26874be1f27dba7">llvm::fp::ebStrict</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic/#a00c4a5b0ef7928bc65dca7af9a5a2b37">llvm::ConstrainedFPIntrinsic::getExceptionBehavior</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic/#a4fc25c0fccec261829e187a058a772a9">llvm::ConstrainedFPIntrinsic::getRoundingMode</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aa8092c6b52c0412d8198a63bc995761e9">llvm::APFloatBase::opOK</a>.</p>


<p>Referenced by <a href="#a72190dad796891a1a5a59d64044000dc">ConstantFoldIntrinsicCall2</a>, <a href="#a505a295564c761e2006b8e48647f6f7d">ConstantFoldScalarCall3</a> and <a href="#a438bfa60f8534d9b0e347dc50e46e079">evaluateCompare</a>.</p>

</div>
</div>

### ReadDataFromGlobal() {#afcd344dd26b9b6b08fcb676d1c888bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ConstantFolding.cpp}::ReadDataFromGlobal (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, uint64_t ByteOffset, unsigned char * CurPtr, unsigned BytesLeft, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursive helper to read bits out of global.</p>


<p>C is the constant being copied out of. ByteOffset is an offset into C. CurPtr is the pointer to copy results into and BytesLeft is the number of bytes left in the CurPtr buffer. DL is the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a>.</p>


<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adf997f1047734d3b47b8d5a9b2163f11">llvm::APInt::extractBits</a>, <a href="#aa5ea18feb56580024a1693b1f98fb3f6">FoldBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a331caeb70809f50e71528de06fba7b66">llvm::StructLayout::getElementContainingOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a3932cc53acb297750961bfdaa86425bc">llvm::StructLayout::getElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a87f56db834c58ca630624956ecf6972f">llvm::Type::getInt16Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#afcd344dd26b9b6b08fcb676d1c888bc8">ReadDataFromGlobal</a>.</p>


<p>Referenced by <a href="#a6cb1fc4464f12007218608fadbe3a3f4">FoldReinterpretLoadFromConst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3002d96da0f9030af718fbe2961b913f">llvm::ReadByteArrayFromGlobal</a> and <a href="#afcd344dd26b9b6b08fcb676d1c888bc8">ReadDataFromGlobal</a>.</p>

</div>
</div>

### SymbolicallyEvaluateBinop() {#a4515378302b14f9df5b64311e4c84a80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateBinop (unsigned Opc, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>One of Op0/Op1 is a constant expression.</p>


<p>Attempt to symbolically evaluate the result of a binary operator merging these together. If target data info is available, it is provided as DL, otherwise DL is null.</p>


<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#afd1c330d00d17bd267450ab43d5f0eec">llvm::KnownBits::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5274c29c7da2473d342adfa98f34a025">llvm::KnownBits::isConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3103683ccd8b97050f821110b98ad2">llvm::IsConstantOffsetFromGlobal</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a2ed912a28808268e35bd58e8f11251aa">llvm::APInt::zextOrTrunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a964455f36837281d37f2a44e2fcb4cca">llvm::ConstantFoldBinaryOpOperands</a>.</p>

</div>
</div>

### SymbolicallyEvaluateGEP() {#a4fc5dce2b300d02414f7b8a99d93d300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateGEP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gepoperator">GEPOperator</a> * GEP, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Ops, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we can symbolically evaluate the GEP constant expression, do so.</p>

<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a6f4eef604ff06e2b83fabf52e828c709">CastGEPIndices</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae4d4490a35a575d97166684fb15f8662">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a02560cda155aaed54314383bed827d60">llvm::ConstantExpr::getIntToPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#a992b9efb797f896ae2cc7f1d043eb68f">llvm::GEPNoWrapFlags::hasNoUnsignedSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#a0c32878bcc6e7bc1ac1e5fbcb1707591">llvm::GEPNoWrapFlags::inBounds</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#aaac99696c5f396905a86fa853f41614f">InRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#aaba6873d157dbd7f5f02da723e6ca78f">llvm::GEPNoWrapFlags::isInBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8ad67a33bae235fe3cca1c3e5a91ed2d">llvm::Type::isSized</a>, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#a5bfde791508b16caf8509e95a8fdf7b9">llvm::GEPNoWrapFlags::noUnsignedWrap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#a20c93f80ea8da60e454d7596737b5c88">llvm::GEPNoWrapFlags::withoutNoUnsignedSignedWrap</a>.</p>


<p>Referenced by <a href="#ae6e1699b7b98eaaf080f652b08792b9f">ConstantFoldInstOperandsImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp">ConstantFolding.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
