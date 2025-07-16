---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loopstrengthreduce-cpp-/immediate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Immediate` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{LoopStrengthReduce.cpp}::Immediate { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f69a88a74a9c75266b70084a23c7715">Immediate</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7a99000ace71b0a2defdfb1133e3020">Immediate</a> (ScalarTy MinVal, bool Scalable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08f7eadd827b0c6cae9a8187569da07">Immediate</a> (const FixedOrScalableQuantity&lt; Immediate, int64_t &gt; &amp;V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09fbb09d8e3de5323f1bf48d5f6ce4d3">isLessThanZero</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af83345cd673ad0ac4c8e054676d99e20">isGreaterThanZero</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17247f3e579ad4a489daa1eec47d02fc">isCompatibleImmediate</a> (const Immediate &amp;Imm) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9e551c149ce95daab0aea2894c9e57e">isMin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a823489f1b0ab38e3bbc2e19d87e53f4d">isMax</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f015c2cf77ee4c5f81b8fef5347372">addUnsigned</a> (const Immediate &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab49fcf96665935bc0bc9d4cbd0a61a5d">subUnsigned</a> (const Immediate &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee2861110d67f49f009585108f84fe9">mulUnsigned</a> (const ScalarTy RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c730254cd6b346d9fa4588c58a7517">getSCEV</a> (ScalarEvolution &amp;SE, Type *Ty) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81bada52d17e453e10221581a1bda050">getNegativeSCEV</a> (ScalarEvolution &amp;SE, Type *Ty) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8829aacd47e6a4f3dbaf6c359d5afdfb">getUnknownSCEV</a> (ScalarEvolution &amp;SE, Type *Ty) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c40dacbda1659252704b6d78a6c9069">getFixed</a> (ScalarTy MinVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7030e0a5d4b154f205b3d85dde0644b">getScalable</a> (ScalarTy MinVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8d7bdfa32234118ad9869341fec341">get</a> (ScalarTy MinVal, bool Scalable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a393faf261b99c7234b6d7d97dbdbd5e0">getZero</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a691a45579958cfd41dd9dcff39646ca0">getFixedMin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23392dbe6d771d111f00d09560f87f0d">getFixedMax</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addbe1dedb40bb3add88146d6f912ab8d">getScalableMin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b628b6318570ab9f5c98bf6a81d0c8c">getScalableMax</a> ()</td>
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


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Immediate() {#a0f69a88a74a9c75266b70084a23c7715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopStrengthReduce.cpp}::Immediate::Immediate ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1a0afc5106fca20f0a81eac37db70ab9">ExtractImmediate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Immediate() {#ae7a99000ace71b0a2defdfb1133e3020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopStrengthReduce.cpp}::Immediate::Immediate (<a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> MinVal, bool Scalable)</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### Immediate() {#aa08f7eadd827b0c6cae9a8187569da07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopStrengthReduce.cpp}::Immediate::Immediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a57beba2321012fb9cb702573f26fefff">FixedOrScalableQuantity</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a>, int64_t &gt; &amp; V)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addUnsigned() {#a94f015c2cf77ee4c5f81b8fef5347372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Immediate anonymous{LoopStrengthReduce.cpp}::Immediate::addUnsigned (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a> &amp; RHS)</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a17247f3e579ad4a489daa1eec47d02fc">isCompatibleImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Quantity</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Scalable</a>.</p>

</div>
</div>

### getNegativeSCEV() {#a81bada52d17e453e10221581a1bda050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * anonymous{LoopStrengthReduce.cpp}::Immediate::getNegativeSCEV (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2eb94d079d8416118f4aaed865ab05d7">llvm::ScalarEvolution::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#abc6d543083aac1a4e161c0ed02b9b30a">llvm::ScalarEvolution::getVScale</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Quantity</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Scalable</a>.</p>

</div>
</div>

### getSCEV() {#a51c730254cd6b346d9fa4588c58a7517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * anonymous{LoopStrengthReduce.cpp}::Immediate::getSCEV (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2eb94d079d8416118f4aaed865ab05d7">llvm::ScalarEvolution::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#abc6d543083aac1a4e161c0ed02b9b30a">llvm::ScalarEvolution::getVScale</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Quantity</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Scalable</a>.</p>

</div>
</div>

### getUnknownSCEV() {#a8829aacd47e6a4f3dbaf6c359d5afdfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * anonymous{LoopStrengthReduce.cpp}::Immediate::getUnknownSCEV (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a9ad53d2a00a6fb861b3a048c6592b742">llvm::ConstantInt::getSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad8e4f5b2ced08ad7d138b598aefdd338">llvm::ScalarEvolution::getUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#abc6d543083aac1a4e161c0ed02b9b30a">llvm::ScalarEvolution::getVScale</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Quantity</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Scalable</a>.</p>

</div>
</div>

### isCompatibleImmediate() {#a17247f3e579ad4a489daa1eec47d02fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopStrengthReduce.cpp}::Immediate::isCompatibleImmediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a> &amp; Imm)</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Scalable</a>.</p>


<p>Referenced by <a href="#a94f015c2cf77ee4c5f81b8fef5347372">addUnsigned</a> and <a href="#ab49fcf96665935bc0bc9d4cbd0a61a5d">subUnsigned</a>.</p>

</div>
</div>

### isGreaterThanZero() {#af83345cd673ad0ac4c8e054676d99e20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopStrengthReduce.cpp}::Immediate::isGreaterThanZero ()</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Quantity</a>.</p>

</div>
</div>

### isLessThanZero() {#a09fbb09d8e3de5323f1bf48d5f6ce4d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopStrengthReduce.cpp}::Immediate::isLessThanZero ()</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Quantity</a>.</p>

</div>
</div>

### isMax() {#a823489f1b0ab38e3bbc2e19d87e53f4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopStrengthReduce.cpp}::Immediate::isMax ()</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Quantity</a>.</p>

</div>
</div>

### isMin() {#af9e551c149ce95daab0aea2894c9e57e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopStrengthReduce.cpp}::Immediate::isMin ()</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Quantity</a>.</p>

</div>
</div>

### mulUnsigned() {#aaee2861110d67f49f009585108f84fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Immediate anonymous{LoopStrengthReduce.cpp}::Immediate::mulUnsigned (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> RHS)</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Quantity</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Scalable</a>.</p>

</div>
</div>

### subUnsigned() {#ab49fcf96665935bc0bc9d4cbd0a61a5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Immediate anonymous{LoopStrengthReduce.cpp}::Immediate::subUnsigned (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a> &amp; RHS)</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a17247f3e579ad4a489daa1eec47d02fc">isCompatibleImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Quantity</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Scalable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#abf8d7bdfa32234118ad9869341fec341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr Immediate anonymous{LoopStrengthReduce.cpp}::Immediate::get (<a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> MinVal, bool Scalable)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::Scalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a111eaa1963537539371757fda03a8d07">isAMCompletelyFolded</a>.</p>

</div>
</div>

### getFixed() {#a4c40dacbda1659252704b6d78a6c9069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr Immediate anonymous{LoopStrengthReduce.cpp}::Immediate::getFixed (<a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> MinVal)</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad35b9a85ea52062375c0c870be5cd228">canFoldIVIncExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1a0afc5106fca20f0a81eac37db70ab9">ExtractImmediate</a>.</p>

</div>
</div>

### getFixedMax() {#a23392dbe6d771d111f00d09560f87f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr Immediate anonymous{LoopStrengthReduce.cpp}::Immediate::getFixedMax ()</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### getFixedMin() {#a691a45579958cfd41dd9dcff39646ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr Immediate anonymous{LoopStrengthReduce.cpp}::Immediate::getFixedMin ()</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### getScalable() {#ac7030e0a5d4b154f205b3d85dde0644b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr Immediate anonymous{LoopStrengthReduce.cpp}::Immediate::getScalable (<a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> MinVal)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad35b9a85ea52062375c0c870be5cd228">canFoldIVIncExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1a0afc5106fca20f0a81eac37db70ab9">ExtractImmediate</a>.</p>

</div>
</div>

### getScalableMax() {#a7b628b6318570ab9f5c98bf6a81d0c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr Immediate anonymous{LoopStrengthReduce.cpp}::Immediate::getScalableMax ()</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### getScalableMin() {#addbe1dedb40bb3add88146d6f912ab8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr Immediate anonymous{LoopStrengthReduce.cpp}::Immediate::getScalableMin ()</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

### getZero() {#a393faf261b99c7234b6d7d97dbdbd5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr Immediate anonymous{LoopStrengthReduce.cpp}::Immediate::getZero ()</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad35b9a85ea52062375c0c870be5cd228">canFoldIVIncExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1a0afc5106fca20f0a81eac37db70ab9">ExtractImmediate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
