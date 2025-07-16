---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HexagonVectorCombine` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SizeKind { <a href="#abfe2870c5fd03b720adcb01775270e15">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abce174abc78cf2fe5987af1aaaa46c60">HexagonVectorCombine</a> (Function &amp;F_, AliasAnalysis &amp;AA_, AssumptionCache &amp;AC_, DominatorTree &amp;DT_, ScalarEvolution &amp;SE_, TargetLibraryInfo &amp;TLI_, const TargetMachine &amp;TM_)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdfbd9fd3f130ac0d25f12d43f34a439">run</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab176ece61e636cb3c39919d309223786">getIntTy</a> (unsigned Width=32) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a243a4cdb6c27c0c4276793b5136a01">getByteTy</a> (int ElemCount=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c38e97ad1359c63dd44a0bbe5dcf3a3">getBoolTy</a> (int ElemCount=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bfdcc832771570bdc4bc5cbedfc2d00">getConstInt</a> (int Val, unsigned Width=32) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eea334ae8cc25bd31b86b26d23b1551">getIntValue</a> (const Value *Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a841d1d83e47f42db17d4bae5f253b107">isZero</a> (const Value *Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2205524be926d967309ffcfb2767fcae">isUndef</a> (const Value *Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a0d9aecb6da964944ddf642321b12f7">isTrue</a> (const Value *Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af87e9ef5e6f1cb1da40b0e50fefeddb2">isFalse</a> (const Value *Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d1ff741add38ce427dcd488424274fe">getHvxTy</a> (Type *ElemTy, bool Pair=false) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c2fe988ef2c54fda723338f9134912">getSizeOf</a> (const Value *Val, SizeKind Kind=Store) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b643b3fc13608ab7327d16653495300">getSizeOf</a> (const Type *Ty, SizeKind Kind=Store) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69699a3423aa6b0f546c0ce860c42c53">getTypeAlignment</a> (Type *Ty) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9251ebedc3e42e6eb944b51384d4f9a4">length</a> (Value *Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a> (Type *Ty) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ada80a87f31679cc7ab3e579349b32">getNullValue</a> (Type *Ty) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a484c25c2e1d843bdf3009c7fff82607b">getFullValue</a> (Type *Ty) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e5734d2a814bfa1aea953e1685df678">getConstSplat</a> (Type *Ty, int Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e3a6fcdae78248354458328bb78cab">simplify</a> (Value *Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a0358fb6de2fdee39a22ff89eae26d1">insertb</a> (IRBuilderBase &amp;Builder, Value *Dest, Value *Src, int Start, int Length, int Where) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b6c0523efa46982b346b582dba83c5">vlalignb</a> (IRBuilderBase &amp;Builder, Value *Lo, Value *Hi, Value *Amt) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae76242f445cf64cc9dac611ba3abc9c7">vralignb</a> (IRBuilderBase &amp;Builder, Value *Lo, Value *Hi, Value *Amt) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d42f23852edcd240ef3a605fdc2bcec">concat</a> (IRBuilderBase &amp;Builder, ArrayRef&lt; Value * &gt; Vecs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb3015db092e8e97f7a585096688b6cf">vresize</a> (IRBuilderBase &amp;Builder, Value *Val, int NewSize, Value *Pad) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c8c57e973ff87b44455c5d47d41770">rescale</a> (IRBuilderBase &amp;Builder, Value *Mask, Type *FromTy, Type *ToTy) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09b9488bfc0aa55fe37ace2bb46745d5">vlsb</a> (IRBuilderBase &amp;Builder, Value *Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86163cb169435641156cbc611072c931">vbytes</a> (IRBuilderBase &amp;Builder, Value *Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df506ef0b4a6ebef7ed0c2898bc848b">subvector</a> (IRBuilderBase &amp;Builder, Value *Val, unsigned Start, unsigned Length) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07983e6bbf82e5ff3a72bd421dd80a8f">sublo</a> (IRBuilderBase &amp;Builder, Value *Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a41efcf7e4e58b9c7b48c382956b09d">subhi</a> (IRBuilderBase &amp;Builder, Value *Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abefc6503480ac4f41b201616d2500cd1">vdeal</a> (IRBuilderBase &amp;Builder, Value *Val0, Value *Val1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4972a69d360be6ee898cff7b4350afe1">vshuff</a> (IRBuilderBase &amp;Builder, Value *Val0, Value *Val1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc83c1972006a05871f65fdf15ade10f">createHvxIntrinsic</a> (IRBuilderBase &amp;Builder, Intrinsic::ID IntID, Type *RetTy, ArrayRef&lt; Value * &gt; Args, ArrayRef&lt; Type * &gt; ArgTys={}, ArrayRef&lt; Value * &gt; MDSources={}) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40bdb7ed86f1fdb139eb9fd73b05405a">splitVectorElements</a> (IRBuilderBase &amp;Builder, Value *Vec, unsigned ToWidth) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a12fa96c1212a99f965fcce98aa550a">joinVectorElements</a> (IRBuilderBase &amp;Builder, ArrayRef&lt; Value * &gt; Values, VectorType *ToType) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1aa55cef94698e03f5b38274a656b4f">calculatePointerDifference</a> (Value *Ptr0, Value *Ptr1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae250333195d50ffcc282ad8d0dd1467e">getNumSignificantBits</a> (const Value *V, const Instruction *CtxI=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab855aa79aa2889254e75caeacc90a059">getKnownBits</a> (const Value *V, const Instruction *CtxI=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a681011a64d26bc71128066fb34a43197">isSafeToClone</a> (const Instruction &amp;In) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T = std::vector&lt;Instruction *&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8671c4972dcd19da86ceff9688d19b13">isSafeToMoveBeforeInBB</a> (const Instruction &amp;In, BasicBlock::const_iterator To, const T &amp;IgnoreInsts={}) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c4e0733e0fc862056a4998ae2992e1a">isByteVecTy</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a77893cb733d0e730a7ce005b53259e09">isSafeToMoveBeforeInBB</a> (const Instruction &amp;In, BasicBlock::const_iterator To, const T &amp;IgnoreInsts) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab12207235b868553ccbc7c2eb07975aa">getElementRange</a> (IRBuilderBase &amp;Builder, Value *Lo, Value *Hi, int Start, int Length) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8209fa9fec163c7ac1c8825d19181a4e">F</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5760728518e42fc093b9181d1f7a4dc2">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3c2871e1260adb7e51997bf3a1730e3">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6ad0b2c24b7eb0d92242f1ce4ba1cb1">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f59eecd683d373e43d9e534cb7b42b">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d1c1ed1ff13c80adcd6ca92e2e6e87c">SE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c34ee2d60c777c17f7fb9cfc0cfc321">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget">HexagonSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f93e86f41abeddbd25db6bab9bcabfc">HST</a></td>
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


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### SizeKind {#abfe2870c5fd03b720adcb01775270e15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::SizeKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Store<a id="abfe2870c5fd03b720adcb01775270e15a40ca99f69e5b05ace46231dea0ee432f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Alloc<a id="abfe2870c5fd03b720adcb01775270e15a8e5ab308eba16fe1bb0f364c6c8d30c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### HexagonVectorCombine() {#abce174abc78cf2fe5987af1aaaa46c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::HexagonVectorCombine (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F_, <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> &amp; AA_, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC_, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT_, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE_, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI_, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM_)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="#ad3c2871e1260adb7e51997bf3a1730e3">AA</a>, <a href="#ac6ad0b2c24b7eb0d92242f1ce4ba1cb1">AC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="#a5760728518e42fc093b9181d1f7a4dc2">DL</a>, <a href="#a49f59eecd683d373e43d9e534cb7b42b">DT</a>, <a href="#a8209fa9fec163c7ac1c8825d19181a4e">F</a>, <a href="#a6f93e86f41abeddbd25db6bab9bcabfc">HST</a>, <a href="#a8d1c1ed1ff13c80adcd6ca92e2e6e87c">SE</a> and <a href="#a4c34ee2d60c777c17f7fb9cfc0cfc321">TLI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### calculatePointerDifference() {#ac1aa55cef94698e03f5b38274a656b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::calculatePointerDifference (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="#abfe2870c5fd03b720adcb01775270e15a8e5ab308eba16fe1bb0f364c6c8d30c1">Alloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp/#a5bb15d2bc36a123a3abaf04198d161db">CallBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ab855aa79aa2889254e75caeacc90a059">getKnownBits</a>, <a href="#a67c2fe988ef2c54fda723338f9134912">getSizeOf</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa241826e10b4a9bf77c3115e7160d3c7">llvm::IRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="#a8d1c1ed1ff13c80adcd6ca92e2e6e87c">SE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp/#aa56209f617200c772b32fea2947178a7">simplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fa4e81c184ac3ad48a389cd4454c4a05bb">Unknown</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

### concat() {#a3d42f23852edcd240ef3a605fdc2bcec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::concat (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Vecs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="#a9251ebedc3e42e6eb944b51384d4f9a4">length</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af5ab7a47bc553dfc3ee92daf969d0d7ca96b0141273eabab320119c467cdcaf17">llvm::Total</a>.</p>

</div>
</div>

### createHvxIntrinsic() {#afc83c1972006a05871f65fdf15ade10f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::createHvxIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntID, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; ArgTys={}, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; MDSources={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a513f55e474dba6d6c2507997e9920b6d">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::doesNotAccessMemory</a>, <a href="#a8209fa9fec163c7ac1c8825d19181a4e">F</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="#a6f93e86f41abeddbd25db6bab9bcabfc">HST</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a636d669d76e435e9d71cdc417c89a30c">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyAccessesInaccessibleMem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48a6deb3e714d54e75caadcf84b0ca76">llvm::propagateMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a>, <a href="#ac4b6c0523efa46982b346b582dba83c5">vlalignb</a> and <a href="#ae76242f445cf64cc9dac611ba3abc9c7">vralignb</a>.</p>

</div>
</div>

### getBoolTy() {#a2c38e97ad1359c63dd44a0bbe5dcf3a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getBoolTy (int ElemCount=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8209fa9fec163c7ac1c8825d19181a4e">F</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>.</p>


<p>Referenced by <a href="#a97c8c57e973ff87b44455c5d47d41770">rescale</a>, <a href="#a86163cb169435641156cbc611072c931">vbytes</a> and <a href="#a09b9488bfc0aa55fe37ace2bb46745d5">vlsb</a>.</p>

</div>
</div>

### getByteTy() {#a6a243a4cdb6c27c0c4276793b5136a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getByteTy (int ElemCount=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8209fa9fec163c7ac1c8825d19181a4e">F</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>.</p>


<p>Referenced by <a href="#a8a0358fb6de2fdee39a22ff89eae26d1">insertb</a>, <a href="#a6c4e0733e0fc862056a4998ae2992e1a">isByteVecTy</a> and <a href="#a86163cb169435641156cbc611072c931">vbytes</a>.</p>

</div>
</div>

### getConstInt() {#a4bfdcc832771570bdc4bc5cbedfc2d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getConstInt (int Val, unsigned Width=32)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#ac03bc20ffe7747dad3d3d4bbbd4a3ca3">getIntTy</a> and <a href="/web-llvm/docs/api/classes/llvm/constantint/#a9ad53d2a00a6fb861b3a048c6592b742">llvm::ConstantInt::getSigned</a>.</p>

</div>
</div>

### getConstSplat() {#a7e5734d2a814bfa1aea953e1685df678}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getConstSplat (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, int Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5b9bf50c6579a978e5c1104bf8787651">llvm::Splat</a>.</p>


<p>Referenced by <a href="#a6a12fa96c1212a99f965fcce98aa550a">joinVectorElements</a> and <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a>.</p>

</div>
</div>

### getFullValue() {#a484c25c2e1d843bdf3009c7fff82607b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getFullValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a>.</p>

</div>
</div>

### getHvxTy() {#a5d1ff741add38ce427dcd488424274fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getHvxTy (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElemTy, bool Pair=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="#a6f93e86f41abeddbd25db6bab9bcabfc">HST</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>.</p>

</div>
</div>

### getIntTy() {#ab176ece61e636cb3c39919d309223786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getIntTy (unsigned Width=32)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="#a8209fa9fec163c7ac1c8825d19181a4e">F</a> and <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>.</p>

</div>
</div>

### getIntValue() {#a2eea334ae8cc25bd31b86b26d23b1551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getIntValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#ac4b6c0523efa46982b346b582dba83c5">vlalignb</a> and <a href="#ae76242f445cf64cc9dac611ba3abc9c7">vralignb</a>.</p>

</div>
</div>

### getKnownBits() {#ab855aa79aa2889254e75caeacc90a059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getKnownBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="#ac6ad0b2c24b7eb0d92242f1ce4ba1cb1">AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="#a5760728518e42fc093b9181d1f7a4dc2">DL</a> and <a href="#a49f59eecd683d373e43d9e534cb7b42b">DT</a>.</p>


<p>Referenced by <a href="#ac1aa55cef94698e03f5b38274a656b4f">calculatePointerDifference</a>.</p>

</div>
</div>

### getNullValue() {#af6ada80a87f31679cc7ab3e579349b32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getNullValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a>.</p>

</div>
</div>

### getNumSignificantBits() {#ae250333195d50ffcc282ad8d0dd1467e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getNumSignificantBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="#ac6ad0b2c24b7eb0d92242f1ce4ba1cb1">AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae95177e7337984f5bc961723ecf67169">llvm::ComputeMaxSignificantBits</a>, <a href="#a5760728518e42fc093b9181d1f7a4dc2">DL</a> and <a href="#a49f59eecd683d373e43d9e534cb7b42b">DT</a>.</p>

</div>
</div>

### getSizeOf() {#a67c2fe988ef2c54fda723338f9134912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getSizeOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="#abfe2870c5fd03b720adcb01775270e15">SizeKind</a> Kind=<a href="#abfe2870c5fd03b720adcb01775270e15a40ca99f69e5b05ace46231dea0ee432f">Store</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Reference <a href="#abfe2870c5fd03b720adcb01775270e15a40ca99f69e5b05ace46231dea0ee432f">Store</a>.</p>


<p>Referenced by <a href="#ac1aa55cef94698e03f5b38274a656b4f">calculatePointerDifference</a>, <a href="#a8a0358fb6de2fdee39a22ff89eae26d1">insertb</a>, <a href="#a97c8c57e973ff87b44455c5d47d41770">rescale</a>, <a href="#a86163cb169435641156cbc611072c931">vbytes</a>, <a href="#ac4b6c0523efa46982b346b582dba83c5">vlalignb</a>, <a href="#a09b9488bfc0aa55fe37ace2bb46745d5">vlsb</a> and <a href="#ae76242f445cf64cc9dac611ba3abc9c7">vralignb</a>.</p>

</div>
</div>

### getSizeOf() {#a2b643b3fc13608ab7327d16653495300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getSizeOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="#abfe2870c5fd03b720adcb01775270e15">SizeKind</a> Kind=<a href="#abfe2870c5fd03b720adcb01775270e15a40ca99f69e5b05ace46231dea0ee432f">Store</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="#a69699a3423aa6b0f546c0ce860c42c53">getTypeAlignment</a> and <a href="#abfe2870c5fd03b720adcb01775270e15a40ca99f69e5b05ace46231dea0ee432f">Store</a>.</p>

</div>
</div>

### getTypeAlignment() {#a69699a3423aa6b0f546c0ce860c42c53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getTypeAlignment (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="#a5760728518e42fc093b9181d1f7a4dc2">DL</a> and <a href="#a6f93e86f41abeddbd25db6bab9bcabfc">HST</a>.</p>


<p>Referenced by <a href="#a2b643b3fc13608ab7327d16653495300">getSizeOf</a>.</p>

</div>
</div>

### insertb() {#a8a0358fb6de2fdee39a22ff89eae26d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::insertb (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Dest, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src, int Start, int Length, int Where)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="#a6a243a4cdb6c27c0c4276793b5136a01">getByteTy</a>, <a href="#a67c2fe988ef2c54fda723338f9134912">getSizeOf</a>, <a href="#a6c4e0733e0fc862056a4998ae2992e1a">isByteVecTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a> and <a href="#aeb3015db092e8e97f7a585096688b6cf">vresize</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a>.</p>

</div>
</div>

### isByteVecTy() {#a6c4e0733e0fc862056a4998ae2992e1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::isByteVecTy (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#a6a243a4cdb6c27c0c4276793b5136a01">getByteTy</a>.</p>


<p>Referenced by <a href="#a8a0358fb6de2fdee39a22ff89eae26d1">insertb</a>.</p>

</div>
</div>

### isFalse() {#af87e9ef5e6f1cb1da40b0e50fefeddb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::isFalse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>.</p>

</div>
</div>

### isSafeToClone() {#a681011a64d26bc71128066fb34a43197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::isSafeToClone (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; In)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### isSafeToMoveBeforeInBB() {#a8671c4972dcd19da86ceff9688d19b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T = std::vector&lt;Instruction *&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::isSafeToMoveBeforeInBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; In, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a42a7d51fdde6913db72d098356c2c019">BasicBlock::const_iterator</a> To, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; IgnoreInsts={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### isSafeToMoveBeforeInBB() {#a77893cb733d0e730a7ce005b53259e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::isSafeToMoveBeforeInBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; In, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a42a7d51fdde6913db72d098356c2c019">BasicBlock::const_iterator</a> To, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; IgnoreInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2851 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="#ad3c2871e1260adb7e51997bf3a1730e3">AA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#afc51de08aefeeaabc77fefacc869dbd4">llvm::MemoryLocation::getForArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#af61b31a99c1e58b1760492d2a7a1ba9c">llvm::MemoryLocation::getOrNone</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aea9b36512640e798bb1a7ac08dc2124d">llvm::mayHaveNonDefUseDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#a4c34ee2d60c777c17f7fb9cfc0cfc321">TLI</a>.</p>

</div>
</div>

### isTrue() {#a2a0d9aecb6da964944ddf642321b12f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::isTrue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>

</div>
</div>

### isUndef() {#a2205524be926d967309ffcfb2767fcae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::isUndef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### isZero() {#a841d1d83e47f42db17d4bae5f253b107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::isZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### joinVectorElements() {#a6a12fa96c1212a99f965fcce98aa550a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::joinVectorElements (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Values, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * ToType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#adc6a2686b807c18e4a7f7fc58e68d423">llvm::IRBuilderBase::CreateAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="#a7e5734d2a814bfa1aea953e1685df678">getConstSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#ac03bc20ffe7747dad3d3d4bbbd4a3ca3">getIntTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="#a9251ebedc3e42e6eb944b51384d4f9a4">length</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a4972a69d360be6ee898cff7b4350afe1">vshuff</a>.</p>

</div>
</div>

### length() {#a9251ebedc3e42e6eb944b51384d4f9a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::length (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Referenced by <a href="#a3d42f23852edcd240ef3a605fdc2bcec">concat</a>, <a href="#a6a12fa96c1212a99f965fcce98aa550a">joinVectorElements</a>, <a href="#a97c8c57e973ff87b44455c5d47d41770">rescale</a>, <a href="#a40bdb7ed86f1fdb139eb9fd73b05405a">splitVectorElements</a>, <a href="#a4a41efcf7e4e58b9c7b48c382956b09d">subhi</a>, <a href="#a07983e6bbf82e5ff3a72bd421dd80a8f">sublo</a>, <a href="#a7df506ef0b4a6ebef7ed0c2898bc848b">subvector</a>, <a href="#abefc6503480ac4f41b201616d2500cd1">vdeal</a>, <a href="#aeb3015db092e8e97f7a585096688b6cf">vresize</a> and <a href="#a4972a69d360be6ee898cff7b4350afe1">vshuff</a>.</p>

</div>
</div>

### length() {#a8544cb19e0b8beb0d33679af30fdef88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::length (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="#afc83c1972006a05871f65fdf15ade10f">createHvxIntrinsic</a>, <a href="#a7e5734d2a814bfa1aea953e1685df678">getConstSplat</a>, <a href="#a484c25c2e1d843bdf3009c7fff82607b">getFullValue</a>, <a href="#af6ada80a87f31679cc7ab3e579349b32">getNullValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="#a8a0358fb6de2fdee39a22ff89eae26d1">insertb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="#a97c8c57e973ff87b44455c5d47d41770">rescale</a>, <a href="#a4a41efcf7e4e58b9c7b48c382956b09d">subhi</a>, <a href="#a07983e6bbf82e5ff3a72bd421dd80a8f">sublo</a>, <a href="#a7df506ef0b4a6ebef7ed0c2898bc848b">subvector</a>, <a href="#a86163cb169435641156cbc611072c931">vbytes</a>, <a href="#abefc6503480ac4f41b201616d2500cd1">vdeal</a>, <a href="#ac4b6c0523efa46982b346b582dba83c5">vlalignb</a>, <a href="#a09b9488bfc0aa55fe37ace2bb46745d5">vlsb</a>, <a href="#ae76242f445cf64cc9dac611ba3abc9c7">vralignb</a>, <a href="#aeb3015db092e8e97f7a585096688b6cf">vresize</a> and <a href="#a4972a69d360be6ee898cff7b4350afe1">vshuff</a>.</p>

</div>
</div>

### rescale() {#a97c8c57e973ff87b44455c5d47d41770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::rescale (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Mask, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * FromTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ToTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="#a2c38e97ad1359c63dd44a0bbe5dcf3a3">getBoolTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#ac03bc20ffe7747dad3d3d4bbbd4a3ca3">getIntTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="#a67c2fe988ef2c54fda723338f9134912">getSizeOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a9251ebedc3e42e6eb944b51384d4f9a4">length</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a>.</p>

</div>
</div>

### run() {#afdfbd9fd3f130ac0d25f12d43f34a439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/alignvectors/#a048d7ea6a08f90db101b47ef7222dcbc">anonymous{HexagonVectorCombine.cpp}::AlignVectors::AlignVectors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonvectorcombine-cpp-/#a358bfa5c6863de5aaa1484cfb6e79d6f">anonymous{HexagonVectorCombine.cpp}::DumpModule</a>, <a href="#a8209fa9fec163c7ac1c8825d19181a4e">F</a>, <a href="#a6f93e86f41abeddbd25db6bab9bcabfc">HST</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hvxidioms/#ab426fcfe9807abfd8c42db93eae4734e">anonymous{HexagonVectorCombine.cpp}::HvxIdioms::run</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonvectorcombine-cpp-/#aabf46b5c10ec4238499281fc75674035">anonymous{HexagonVectorCombine.cpp}::VAEnabled</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonvectorcombine-cpp-/#acb00dd7803b8d39fa6d2c49f3a0945fc">anonymous{HexagonVectorCombine.cpp}::VIEnabled</a>.</p>

</div>
</div>

### simplify() {#af6e3a6fcdae78248354458328bb78cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::simplify (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="#ac6ad0b2c24b7eb0d92242f1ce4ba1cb1">AC</a>, <a href="#a5760728518e42fc093b9181d1f7a4dc2">DL</a>, <a href="#a49f59eecd683d373e43d9e534cb7b42b">DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a> and <a href="#a4c34ee2d60c777c17f7fb9cfc0cfc321">TLI</a>.</p>

</div>
</div>

### splitVectorElements() {#a40bdb7ed86f1fdb139eb9fd73b05405a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::splitVectorElements (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Vec, unsigned ToWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#ac03bc20ffe7747dad3d3d4bbbd4a3ca3">getIntTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="#a9251ebedc3e42e6eb944b51384d4f9a4">length</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>, <a href="#a4a41efcf7e4e58b9c7b48c382956b09d">subhi</a>, <a href="#a07983e6bbf82e5ff3a72bd421dd80a8f">sublo</a> and <a href="#abefc6503480ac4f41b201616d2500cd1">vdeal</a>.</p>

</div>
</div>

### subhi() {#a4a41efcf7e4e58b9c7b48c382956b09d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::subhi (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9251ebedc3e42e6eb944b51384d4f9a4">length</a> and <a href="#a7df506ef0b4a6ebef7ed0c2898bc848b">subvector</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a> and <a href="#a40bdb7ed86f1fdb139eb9fd73b05405a">splitVectorElements</a>.</p>

</div>
</div>

### sublo() {#a07983e6bbf82e5ff3a72bd421dd80a8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::sublo (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9251ebedc3e42e6eb944b51384d4f9a4">length</a> and <a href="#a7df506ef0b4a6ebef7ed0c2898bc848b">subvector</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a> and <a href="#a40bdb7ed86f1fdb139eb9fd73b05405a">splitVectorElements</a>.</p>

</div>
</div>

### subvector() {#a7df506ef0b4a6ebef7ed0c2898bc848b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::subvector (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, unsigned Start, unsigned Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="#a9251ebedc3e42e6eb944b51384d4f9a4">length</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a>, <a href="#a4a41efcf7e4e58b9c7b48c382956b09d">subhi</a> and <a href="#a07983e6bbf82e5ff3a72bd421dd80a8f">sublo</a>.</p>

</div>
</div>

### vbytes() {#a86163cb169435641156cbc611072c931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::vbytes (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="#a2c38e97ad1359c63dd44a0bbe5dcf3a3">getBoolTy</a>, <a href="#a6a243a4cdb6c27c0c4276793b5136a01">getByteTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="#a67c2fe988ef2c54fda723338f9134912">getSizeOf</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a> and <a href="#a09b9488bfc0aa55fe37ace2bb46745d5">vlsb</a>.</p>

</div>
</div>

### vdeal() {#abefc6503480ac4f41b201616d2500cd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::vdeal (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a> and <a href="#a9251ebedc3e42e6eb944b51384d4f9a4">length</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a> and <a href="#a40bdb7ed86f1fdb139eb9fd73b05405a">splitVectorElements</a>.</p>

</div>
</div>

### vlalignb() {#ac4b6c0523efa46982b346b582dba83c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::vlalignb (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Lo, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Hi, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Amt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52ff73f5c87e0fb78fbdca0465300c95">llvm::concat</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="#afc83c1972006a05871f65fdf15ade10f">createHvxIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="#a8209fa9fec163c7ac1c8825d19181a4e">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#a0652fb126dc7bb267410275a2a0864d4">getConstInt</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="#a2eea334ae8cc25bd31b86b26d23b1551">getIntValue</a>, <a href="#a67c2fe988ef2c54fda723338f9134912">getSizeOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="#a6f93e86f41abeddbd25db6bab9bcabfc">HST</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="#ae76242f445cf64cc9dac611ba3abc9c7">vralignb</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a>.</p>

</div>
</div>

### vlsb() {#a09b9488bfc0aa55fe37ace2bb46745d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::vlsb (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a2c38e97ad1359c63dd44a0bbe5dcf3a3">getBoolTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="#a67c2fe988ef2c54fda723338f9134912">getSizeOf</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="#a86163cb169435641156cbc611072c931">vbytes</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a>.</p>

</div>
</div>

### vralignb() {#ae76242f445cf64cc9dac611ba3abc9c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::vralignb (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Lo, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Hi, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Amt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52ff73f5c87e0fb78fbdca0465300c95">llvm::concat</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="#afc83c1972006a05871f65fdf15ade10f">createHvxIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="#a8209fa9fec163c7ac1c8825d19181a4e">F</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="#a2eea334ae8cc25bd31b86b26d23b1551">getIntValue</a>, <a href="#a67c2fe988ef2c54fda723338f9134912">getSizeOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="#a6f93e86f41abeddbd25db6bab9bcabfc">HST</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>


<p>Referenced by <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a> and <a href="#ac4b6c0523efa46982b346b582dba83c5">vlalignb</a>.</p>

</div>
</div>

### vresize() {#aeb3015db092e8e97f7a585096688b6cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::vresize (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, int NewSize, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Pad)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a40ed7274ff11f079e5b5eae34c818c51">llvm::IRBuilderBase::CreateVectorSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a9251ebedc3e42e6eb944b51384d4f9a4">length</a>.</p>


<p>Referenced by <a href="#a8a0358fb6de2fdee39a22ff89eae26d1">insertb</a> and <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a>.</p>

</div>
</div>

### vshuff() {#a4972a69d360be6ee898cff7b4350afe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::vshuff (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a> and <a href="#a9251ebedc3e42e6eb944b51384d4f9a4">length</a>.</p>


<p>Referenced by <a href="#a6a12fa96c1212a99f965fcce98aa550a">joinVectorElements</a> and <a href="#a8544cb19e0b8beb0d33679af30fdef88">length</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getElementRange() {#ab12207235b868553ccbc7c2eb07975aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto HexagonVectorCombine::getElementRange (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Lo, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Hi, int Start, int Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AA {#ad3c2871e1260adb7e51997bf3a1730e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis&amp; anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Referenced by <a href="#abce174abc78cf2fe5987af1aaaa46c60">HexagonVectorCombine</a> and <a href="#a77893cb733d0e730a7ce005b53259e09">isSafeToMoveBeforeInBB</a>.</p>

</div>
</div>

### AC {#ac6ad0b2c24b7eb0d92242f1ce4ba1cb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Referenced by <a href="#ab855aa79aa2889254e75caeacc90a059">getKnownBits</a>, <a href="#ae250333195d50ffcc282ad8d0dd1467e">getNumSignificantBits</a>, <a href="#abce174abc78cf2fe5987af1aaaa46c60">HexagonVectorCombine</a> and <a href="#af6e3a6fcdae78248354458328bb78cab">simplify</a>.</p>

</div>
</div>

### DL {#a5760728518e42fc093b9181d1f7a4dc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Referenced by <a href="#ab855aa79aa2889254e75caeacc90a059">getKnownBits</a>, <a href="#ae250333195d50ffcc282ad8d0dd1467e">getNumSignificantBits</a>, <a href="#a69699a3423aa6b0f546c0ce860c42c53">getTypeAlignment</a>, <a href="#abce174abc78cf2fe5987af1aaaa46c60">HexagonVectorCombine</a> and <a href="#af6e3a6fcdae78248354458328bb78cab">simplify</a>.</p>

</div>
</div>

### DT {#a49f59eecd683d373e43d9e534cb7b42b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Referenced by <a href="#ab855aa79aa2889254e75caeacc90a059">getKnownBits</a>, <a href="#ae250333195d50ffcc282ad8d0dd1467e">getNumSignificantBits</a>, <a href="#abce174abc78cf2fe5987af1aaaa46c60">HexagonVectorCombine</a> and <a href="#af6e3a6fcdae78248354458328bb78cab">simplify</a>.</p>

</div>
</div>

### F {#a8209fa9fec163c7ac1c8825d19181a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Referenced by <a href="#afc83c1972006a05871f65fdf15ade10f">createHvxIntrinsic</a>, <a href="#a2c38e97ad1359c63dd44a0bbe5dcf3a3">getBoolTy</a>, <a href="#a6a243a4cdb6c27c0c4276793b5136a01">getByteTy</a>, <a href="#ab176ece61e636cb3c39919d309223786">getIntTy</a>, <a href="#abce174abc78cf2fe5987af1aaaa46c60">HexagonVectorCombine</a>, <a href="#afdfbd9fd3f130ac0d25f12d43f34a439">run</a>, <a href="#ac4b6c0523efa46982b346b582dba83c5">vlalignb</a> and <a href="#ae76242f445cf64cc9dac611ba3abc9c7">vralignb</a>.</p>

</div>
</div>

### HST {#a6f93e86f41abeddbd25db6bab9bcabfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonSubtarget&amp; anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::HST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Referenced by <a href="#afc83c1972006a05871f65fdf15ade10f">createHvxIntrinsic</a>, <a href="#a5d1ff741add38ce427dcd488424274fe">getHvxTy</a>, <a href="#a69699a3423aa6b0f546c0ce860c42c53">getTypeAlignment</a>, <a href="#abce174abc78cf2fe5987af1aaaa46c60">HexagonVectorCombine</a>, <a href="#afdfbd9fd3f130ac0d25f12d43f34a439">run</a>, <a href="#ac4b6c0523efa46982b346b582dba83c5">vlalignb</a> and <a href="#ae76242f445cf64cc9dac611ba3abc9c7">vralignb</a>.</p>

</div>
</div>

### SE {#a8d1c1ed1ff13c80adcd6ca92e2e6e87c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Referenced by <a href="#ac1aa55cef94698e03f5b38274a656b4f">calculatePointerDifference</a> and <a href="#abce174abc78cf2fe5987af1aaaa46c60">HexagonVectorCombine</a>.</p>

</div>
</div>

### TLI {#a4c34ee2d60c777c17f7fb9cfc0cfc321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo&amp; anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Referenced by <a href="#abce174abc78cf2fe5987af1aaaa46c60">HexagonVectorCombine</a>, <a href="#a77893cb733d0e730a7ce005b53259e09">isSafeToMoveBeforeInBB</a> and <a href="#af6e3a6fcdae78248354458328bb78cab">simplify</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
