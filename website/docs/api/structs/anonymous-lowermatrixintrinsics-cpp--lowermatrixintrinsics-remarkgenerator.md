---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/remarkgenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RemarkGenerator` Struct Reference

<p>Generate remarks for matrix operations in a function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73de135507c562022c3d7eecb0699894">RemarkGenerator</a> (const MapVector&lt; Value *, MatrixTy &gt; &amp;Inst2Matrix, OptimizationRemarkEmitter &amp;ORE, Function &amp;Func)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53d241b242a10e4f387b39e4497054db">getExpressionLeaves</a> (const SmallSetVector&lt; Value *, 32 &gt; &amp;ExprsInSubprogram)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return all leaves of the expressions in <span class="doxyComputerOutput">ExprsInSubprogram</span>. <a href="#a53d241b242a10e4f387b39e4497054db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aede10d0506e306b2e999635ebeeeb5f2">collectSharedInfo</a> (Value *Leaf, Value *V, const SmallSetVector&lt; Value *, 32 &gt; &amp;ExprsInSubprogram, DenseMap&lt; Value *, SmallPtrSet&lt; Value *, 2 &gt; &gt; &amp;Shared)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively traverse expression <span class="doxyComputerOutput">V</span> starting at <span class="doxyComputerOutput">Leaf</span> and add <span class="doxyComputerOutput">Leaf</span> to all visited expressions in <span class="doxyComputerOutput">Shared</span>. <a href="#aede10d0506e306b2e999635ebeeeb5f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; OpInfoTy, OpInfoTy &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec127cef6ea0cd9c8caf001e24d4abed">sumOpInfos</a> (Value *Root, SmallPtrSetImpl&lt; Value * &gt; &amp;ReusedExprs, const SmallSetVector&lt; Value *, 32 &gt; &amp;ExprsInSubprogram, DenseMap&lt; Value *, SmallPtrSet&lt; Value *, 2 &gt; &gt; &amp;Shared) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the number of exclusive and shared op counts for expression starting at <span class="doxyComputerOutput">V</span>. <a href="#aec127cef6ea0cd9c8caf001e24d4abed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa50ad465c63aba4cc83c1e37248a860">emitRemarks</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35015ea3908e8d728e49b498130c835c">linearize</a> (Value *L, const DenseMap&lt; Value *, SmallPtrSet&lt; Value *, 2 &gt; &gt; &amp;Shared, const SmallSetVector&lt; Value *, 32 &gt; &amp;ExprsInSubprogram, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, MatrixTy &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea0b15956ed54d0552ea2e189d8b19b">Inst2Matrix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cd071961c14e58b4dd2e0469e643856">ORE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45704943fab88f965bfc21f58cc25281">Func</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef49bb5322c89feceb7a78f5e01a179">DL</a></td>
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

<p>Generate remarks for matrix operations in a function.</p>


<p>To generate remarks for matrix expressions, the following approach is used:</p>


<ol class="doxyList" type="1">
<li><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the inlined-at debug information to group matrix operations to the DISubprograms they are contained in.</li>
<li>Collect leaves of matrix expressions (done in <a href="#a53d241b242a10e4f387b39e4497054db">RemarkGenerator::getExpressionLeaves</a>) for each subprogram - expression</li>
<li>For each leaf, create a remark containing a linearizied version of the matrix expression. The expression is linearized by a recursive bottom-up traversal of the matrix operands, starting at a leaf. Note that multiple leaves can share sub-expressions. Shared subexpressions are explicitly marked as shared().</li>
</ol>

<p>Definition at line 2482 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RemarkGenerator() {#a73de135507c562022c3d7eecb0699894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::RemarkGenerator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, MatrixTy &gt; &amp; Inst2Matrix, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func)</td>
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



<p>Definition at line 2488 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="#a4ef49bb5322c89feceb7a78f5e01a179">DL</a>, <a href="#a45704943fab88f965bfc21f58cc25281">Func</a>, <a href="#abea0b15956ed54d0552ea2e189d8b19b">Inst2Matrix</a> and <a href="#a7cd071961c14e58b4dd2e0469e643856">ORE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### collectSharedInfo() {#aede10d0506e306b2e999635ebeeeb5f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::collectSharedInfo (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Leaf, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 32 &gt; &amp; ExprsInSubprogram, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 2 &gt; &gt; &amp; Shared)</td>
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

<p>Recursively traverse expression <span class="doxyComputerOutput">V</span> starting at <span class="doxyComputerOutput">Leaf</span> and add <span class="doxyComputerOutput">Leaf</span> to all visited expressions in <span class="doxyComputerOutput">Shared</span>.</p>


<p>Limit the matrix operations to the ones in <span class="doxyComputerOutput">ExprsInSubprogram</span>.</p>


<p>Definition at line 2511 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aede10d0506e306b2e999635ebeeeb5f2">collectSharedInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#abb03e3b6c4fd937936a13afe4f60d291">llvm::SetVector&lt; T, Vector, Set, N &gt;::count</a>.</p>


<p>Referenced by <a href="#aede10d0506e306b2e999635ebeeeb5f2">collectSharedInfo</a> and <a href="#afa50ad465c63aba4cc83c1e37248a860">emitRemarks</a>.</p>

</div>
</div>

### emitRemarks() {#afa50ad465c63aba4cc83c1e37248a860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::emitRemarks ()</td>
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



<p>Definition at line 2556 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aede10d0506e306b2e999635ebeeeb5f2">collectSharedInfo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="#a4ef49bb5322c89feceb7a78f5e01a179">DL</a>, <a href="#a45704943fab88f965bfc21f58cc25281">Func</a>, <a href="#a53d241b242a10e4f387b39e4497054db">getExpressionLeaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a859931f9f18bb9556861a9568be49d1e">getSubprogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#abea0b15956ed54d0552ea2e189d8b19b">Inst2Matrix</a>, <a href="#a35015ea3908e8d728e49b498130c835c">linearize</a>, <a href="#a7cd071961c14e58b4dd2e0469e643856">ORE</a> and <a href="#aec127cef6ea0cd9c8caf001e24d4abed">sumOpInfos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a49a46654ca2c32ce99be52de089052f8">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Visit</a>.</p>

</div>
</div>

### getExpressionLeaves() {#a53d241b242a10e4f387b39e4497054db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Value *, 4 &gt; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::getExpressionLeaves (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 32 &gt; &amp; ExprsInSubprogram)</td>
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

<p>Return all leaves of the expressions in <span class="doxyComputerOutput">ExprsInSubprogram</span>.</p>


<p>Those are instructions in Inst2Matrix returning void or without any users in <span class="doxyComputerOutput">ExprsInSubprogram</span>. Currently that should only include stores.</p>


<p>Definition at line 2497 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#afa50ad465c63aba4cc83c1e37248a860">emitRemarks</a>.</p>

</div>
</div>

### linearize() {#a35015ea3908e8d728e49b498130c835c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::linearize (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 2 &gt; &gt; &amp; Shared, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 32 &gt; &amp; ExprsInSubprogram, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 2632 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="#a4ef49bb5322c89feceb7a78f5e01a179">DL</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/exprlinearizer/#a716be5b13b21e6b38f78bebdb6761163">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::ExprLinearizer::getResult</a>, <a href="#abea0b15956ed54d0552ea2e189d8b19b">Inst2Matrix</a> and <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/exprlinearizer/#acec0fdbf1c591a64494e4218993d40b3">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::ExprLinearizer::linearizeExpr</a>.</p>


<p>Referenced by <a href="#afa50ad465c63aba4cc83c1e37248a860">emitRemarks</a>.</p>

</div>
</div>

### sumOpInfos() {#aec127cef6ea0cd9c8caf001e24d4abed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; OpInfoTy, OpInfoTy &gt; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::sumOpInfos (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ReusedExprs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 32 &gt; &amp; ExprsInSubprogram, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 2 &gt; &gt; &amp; Shared)</td>
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

<p>Calculate the number of exclusive and shared op counts for expression starting at <span class="doxyComputerOutput">V</span>.</p>


<p>Expressions used multiple times are counted once. Limit the matrix operations to the ones in <span class="doxyComputerOutput">ExprsInSubprogram</span>.</p>


<p>Definition at line 2528 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#abb03e3b6c4fd937936a13afe4f60d291">llvm::SetVector&lt; T, Vector, Set, N &gt;::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#abea0b15956ed54d0552ea2e189d8b19b">Inst2Matrix</a> and <a href="#aec127cef6ea0cd9c8caf001e24d4abed">sumOpInfos</a>.</p>


<p>Referenced by <a href="#afa50ad465c63aba4cc83c1e37248a860">emitRemarks</a> and <a href="#aec127cef6ea0cd9c8caf001e24d4abed">sumOpInfos</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DL {#a4ef49bb5322c89feceb7a78f5e01a179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2486 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>Referenced by <a href="#afa50ad465c63aba4cc83c1e37248a860">emitRemarks</a>, <a href="#a35015ea3908e8d728e49b498130c835c">linearize</a> and <a href="#a73de135507c562022c3d7eecb0699894">RemarkGenerator</a>.</p>

</div>
</div>

### Func {#a45704943fab88f965bfc21f58cc25281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::Func</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2485 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>Referenced by <a href="#afa50ad465c63aba4cc83c1e37248a860">emitRemarks</a> and <a href="#a73de135507c562022c3d7eecb0699894">RemarkGenerator</a>.</p>

</div>
</div>

### Inst2Matrix {#abea0b15956ed54d0552ea2e189d8b19b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MapVector&lt;Value *, MatrixTy&gt;&amp; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::Inst2Matrix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2483 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>Referenced by <a href="#afa50ad465c63aba4cc83c1e37248a860">emitRemarks</a>, <a href="#a35015ea3908e8d728e49b498130c835c">linearize</a>, <a href="#a73de135507c562022c3d7eecb0699894">RemarkGenerator</a> and <a href="#aec127cef6ea0cd9c8caf001e24d4abed">sumOpInfos</a>.</p>

</div>
</div>

### ORE {#a7cd071961c14e58b4dd2e0469e643856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter&amp; anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2484 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>Referenced by <a href="#afa50ad465c63aba4cc83c1e37248a860">emitRemarks</a> and <a href="#a73de135507c562022c3d7eecb0699894">RemarkGenerator</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
