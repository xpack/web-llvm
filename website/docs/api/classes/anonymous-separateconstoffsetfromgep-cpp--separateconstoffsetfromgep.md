---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-separateconstoffsetfromgep-cpp-/separateconstoffsetfromgep
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SeparateConstOffsetFromGEP` Class

<p>A pass that tries to split every GEP in the function into a variadic base and a constant offset. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac09a70a66b41950d4c757509f59973d">ExprKey</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track the operands of an add or sub. <a href="#aac09a70a66b41950d4c757509f59973d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c5223afb0dcd4237e14d95265b1782f">SeparateConstOffsetFromGEP</a> (DominatorTree *DT, LoopInfo *LI, TargetLibraryInfo *TLI, function_ref&lt; TargetTransformInfo &amp;(Function &amp;)&gt; GetTTI, bool LowerGEP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad12e0825707a4d103c8475716b10ecf5">run</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44ec30956d40ad57d6a413beaab27606">splitGEP</a> (GetElementPtrInst *GEP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to split the given GEP into a variadic base and a constant offset, and returns true if the splitting succeeds. <a href="#a44ec30956d40ad57d6a413beaab27606">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc30cede4afac8f6d78b0d9d11bae4f">reorderGEP</a> (GetElementPtrInst *GEP, TargetTransformInfo &amp;TTI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to reorder the given GEP with the GEP that produces the base if doing so results in producing a constant offset as the outermost index. <a href="#a9bc30cede4afac8f6d78b0d9d11bae4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cfe73904889cd0583c0e2335ea3e686">lowerToSingleIndexGEPs</a> (GetElementPtrInst *Variadic, int64_t AccumulativeByteOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower a GEP with multiple indices into multiple GEPs with a single index. <a href="#a5cfe73904889cd0583c0e2335ea3e686">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a4c1632ae616c5661f48e1a88fcb0a3">lowerToArithmetics</a> (GetElementPtrInst *Variadic, int64_t AccumulativeByteOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower a GEP with multiple indices into ptrtoint+arithmetics+inttoptr form. <a href="#a9a4c1632ae616c5661f48e1a88fcb0a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34c6254b2375360c3b8d15636a4122a6">accumulateByteOffset</a> (GetElementPtrInst *GEP, bool &amp;NeedsExtraction)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the constant offset within each index and accumulates them. <a href="#a34c6254b2375360c3b8d15636a4122a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d03720ef3271aff9370aeabc7c192e">canonicalizeArrayIndicesToIndexSize</a> (GetElementPtrInst *GEP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Canonicalize array indices to pointer-size integers. <a href="#a36d03720ef3271aff9370aeabc7c192e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53735bc3a671b8f2ac94c51febad895a">reuniteExts</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize sext(a)+sext(b) to sext(a+b) when a+b can't sign overflow. <a href="#a53735bc3a671b8f2ac94c51febad895a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a022fcd18edbe361b7e0241ea0e26c86a">reuniteExts</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper that reunites sexts in an instruction. <a href="#a022fcd18edbe361b7e0241ea0e26c86a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c74732b3806025e607b45ceac017beb">findClosestMatchingDominator</a> (ExprKey Key, Instruction *Dominatee, DenseMap&lt; ExprKey, SmallVector&lt; Instruction *, 2 &gt; &gt; &amp;DominatingExprs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the closest dominator of &lt;Dominatee&gt; that is equivalent to &lt;Key&gt;. <a href="#a4c74732b3806025e607b45ceac017beb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad92acf5afe24d6290f4ac7e6b83781c7">verifyNoDeadCode</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify F is free of dead code. <a href="#ad92acf5afe24d6290f4ac7e6b83781c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa074ed5f239d0e83099fb6e9c246ea73">hasMoreThanOneUseInLoop</a> (Value *v, Loop *L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62be42a08180b1a446292d08680c439c">swapGEPOperand</a> (GetElementPtrInst *First, GetElementPtrInst *Second)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a017b70bb2619d7ab56f55e45622b53af">isLegalToSwapOperand</a> (GetElementPtrInst *First, GetElementPtrInst *Second, Loop *CurLoop)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbed8a7cd71bd64a86baf6913ff56caa">DL</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93ac02168925c4403a834f89b14f4785">DT</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa668c036e831a226455cf97c82308ccd">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca62991b7d6e9fe1f1081a3f728774f">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a261ebd62802eacbb7800f6925e227dfb">GetTTI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ad64be741477fbbc51135cac9a472be">LowerGEP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to lower a GEP with multiple indices into arithmetic operations or multiple GEPs with a single index. <a href="#a8ad64be741477fbbc51135cac9a472be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; ExprKey, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 2 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab85bf25987f9ea6d421b57448f042df7">DominatingAdds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; ExprKey, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 2 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5acf28a6070431f27c81508e376c010">DominatingSubs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static ExprKey</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc8df1b85e0cc9fed1683d48a6b4f653">createNormalizedCommutablePair</a> (Value *A, Value *B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a pair for use as a map key for a commutable operation. <a href="#adc8df1b85e0cc9fed1683d48a6b4f653">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A pass that tries to split every GEP in the function into a variadic base and a constant offset.</p>


<p>It is a <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> because searching for the constant offset may inspect other basic blocks.</p>


<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ExprKey {#aac09a70a66b41950d4c757509f59973d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP::ExprKey =  std::pair&lt;Value *, Value *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Track the operands of an add or sub.</p>

<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SeparateConstOffsetFromGEP() {#a5c5223afb0dcd4237e14d95265b1782f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP::SeparateConstOffsetFromGEP (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetTTI, bool LowerGEP)</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#ad12e0825707a4d103c8475716b10ecf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SeparateConstOffsetFromGEP::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp/#a04420dee76eeabc142fb4cc165cdbaa1">DisableSeparateConstOffsetFromGEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp/#a3182e2578057e714c3414337fbb50e8f">VerifyNoDeadCode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### accumulateByteOffset() {#a34c6254b2375360c3b8d15636a4122a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t SeparateConstOffsetFromGEP::accumulateByteOffset (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEP, bool &amp; NeedsExtraction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finds the constant offset within each index and accumulates them.</p>


<p>If LowerGEP is true, it finds in indices of both sequential and structure types, otherwise it only finds in sequential indices. The output NeedsExtraction indicates whether we successfully find a non-zero constant offset.</p>


<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### canonicalizeArrayIndicesToIndexSize() {#a36d03720ef3271aff9370aeabc7c192e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SeparateConstOffsetFromGEP::canonicalizeArrayIndicesToIndexSize (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Canonicalize array indices to pointer-size integers.</p>


<p>This helps to simplify the logic of splitting a GEP. For example, if a + b is a pointer-size integer, we have gep base, a + b = gep (gep base, a), b However, this equality may not hold if the size of a + b is smaller than the pointer size, because LLVM conceptually sign-extends GEP indices to pointer size before computing the address (<a href="http://llvm.org/docs/LangRef.html#id181">http://llvm.org/docs/LangRef.html#id181</a>).</p>


<p>This canonicalization is very likely already done in clang and instcombine. Therefore, the program will probably remain the same.</p>


<p>Returns true if the module changes.</p>


<p>Verified in @i32_add in split-gep.ll</p>


<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### findClosestMatchingDominator() {#a4c74732b3806025e607b45ceac017beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * SeparateConstOffsetFromGEP::findClosestMatchingDominator (ExprKey Key, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Dominatee, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; ExprKey, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 2 &gt; &gt; &amp; DominatingExprs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the closest dominator of &lt;Dominatee&gt; that is equivalent to &lt;Key&gt;.</p>

<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### hasMoreThanOneUseInLoop() {#aa074ed5f239d0e83099fb6e9c246ea73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SeparateConstOffsetFromGEP::hasMoreThanOneUseInLoop (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * v, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### isLegalToSwapOperand() {#a017b70bb2619d7ab56f55e45622b53af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SeparateConstOffsetFromGEP::isLegalToSwapOperand (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * First, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * Second, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### lowerToArithmetics() {#a9a4c1632ae616c5661f48e1a88fcb0a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SeparateConstOffsetFromGEP::lowerToArithmetics (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * Variadic, int64_t AccumulativeByteOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower a GEP with multiple indices into ptrtoint+arithmetics+inttoptr form.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> splitGEP already split the original GEP into a variadic part and a constant offset (i.e., AccumulativeByteOffset). This function lowers the variadic part into a set of arithmetic operations and applies AccumulativeByteOffset to it. <span class="doxyComputerOutput">Variadic</span> The variadic part of the original GEP. <span class="doxyComputerOutput">AccumulativeByteOffset</span> The constant offset.</p>


<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### lowerToSingleIndexGEPs() {#a5cfe73904889cd0583c0e2335ea3e686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SeparateConstOffsetFromGEP::lowerToSingleIndexGEPs (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * Variadic, int64_t AccumulativeByteOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower a GEP with multiple indices into multiple GEPs with a single index.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> splitGEP already split the original GEP into a variadic part and a constant offset (i.e., AccumulativeByteOffset). This function lowers the variadic part into a set of GEPs with a single index and applies AccumulativeByteOffset to it. <span class="doxyComputerOutput">Variadic</span> The variadic part of the original GEP. <span class="doxyComputerOutput">AccumulativeByteOffset</span> The constant offset.</p>


<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### reorderGEP() {#a9bc30cede4afac8f6d78b0d9d11bae4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SeparateConstOffsetFromGEP::reorderGEP (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEP, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to reorder the given GEP with the GEP that produces the base if doing so results in producing a constant offset as the outermost index.</p>

<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### reuniteExts() {#a53735bc3a671b8f2ac94c51febad895a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SeparateConstOffsetFromGEP::reuniteExts (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimize sext(a)+sext(b) to sext(a+b) when a+b can't sign overflow.</p>


<p><a href="/web-llvm/docs/api/classes/anonymous-separateconstoffsetfromgep-cpp-/separateconstoffsetfromgep">SeparateConstOffsetFromGEP</a> distributes a sext to leaves before extracting the constant offset. After extraction, it becomes desirable to reunion the distributed sexts. For example,</p>



<pre><code>                         &amp;a[sext(i +nsw (j +nsw 5)]
</code></pre>


<p>=&gt; distribute &amp;a[sext(i) +nsw (sext(j) +nsw 5)] =&gt; constant extraction &amp;a[sext(i) + sext(j)] + 5 =&gt; reunion &amp;a[sext(i +nsw j)] + 5</p>


<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### reuniteExts() {#a022fcd18edbe361b7e0241ea0e26c86a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SeparateConstOffsetFromGEP::reuniteExts (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper that reunites sexts in an instruction.</p>

<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### splitGEP() {#a44ec30956d40ad57d6a413beaab27606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SeparateConstOffsetFromGEP::splitGEP (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to split the given GEP into a variadic base and a constant offset, and returns true if the splitting succeeds.</p>

<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### swapGEPOperand() {#a62be42a08180b1a446292d08680c439c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SeparateConstOffsetFromGEP::swapGEPOperand (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * First, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * Second)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### verifyNoDeadCode() {#ad92acf5afe24d6290f4ac7e6b83781c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SeparateConstOffsetFromGEP::verifyNoDeadCode (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify F is free of dead code.</p>

<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DL {#abbed8a7cd71bd64a86baf6913ff56caa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout* anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP::DL = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### DominatingAdds {#ab85bf25987f9ea6d421b57448f042df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ExprKey, SmallVector&lt;Instruction *, 2&gt; &gt; anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP::DominatingAdds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### DominatingSubs {#ae5acf28a6070431f27c81508e376c010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ExprKey, SmallVector&lt;Instruction *, 2&gt; &gt; anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP::DominatingSubs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### DT {#a93ac02168925c4403a834f89b14f4785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP::DT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### GetTTI {#a261ebd62802eacbb7800f6925e227dfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;TargetTransformInfo &amp;(Function &amp;)&gt; anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP::GetTTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### LI {#aa668c036e831a226455cf97c82308ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### LowerGEP {#a8ad64be741477fbbc51135cac9a472be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP::LowerGEP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to lower a GEP with multiple indices into arithmetic operations or multiple GEPs with a single index.</p>

<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### TLI {#a6ca62991b7d6e9fe1f1081a3f728774f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo* anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### createNormalizedCommutablePair() {#adc8df1b85e0cc9fed1683d48a6b4f653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExprKey anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP::createNormalizedCommutablePair (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B)</td>
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

<p>Create a pair for use as a map key for a commutable operation.</p>

<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
