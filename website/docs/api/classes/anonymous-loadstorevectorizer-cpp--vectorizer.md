---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loadstorevectorizer-cpp-/vectorizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Vectorizer` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{LoadStoreVectorizer.cpp}::Vectorizer { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fe1ef32d92d660691a7ea8c03747fb8">Vectorizer</a> (Function &amp;F, AliasAnalysis &amp;AA, AssumptionCache &amp;AC, DominatorTree &amp;DT, ScalarEvolution &amp;SE, TargetTransformInfo &amp;TTI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdc19a1fe655b43b92647431e2e8ec8a">run</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsLoadChain&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0c2e6c32b60d80acb3a91698e4981eb">isSafeToMove</a> (Instruction *ChainElem, Instruction *ChainBegin, const DenseMap&lt; Instruction *, APInt &gt; &amp;ChainOffsets)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af85756be609cadfcf4cb5dd4fc3e6776">runOnPseudoBB</a> (BasicBlock::iterator Begin, BasicBlock::iterator End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Runs the vectorizer on a "pseudo basic block", which is a range of instructions [Begin, End) within one BB all of which have isGuaranteedToTransferExecutionToSuccessor(I) == true. <a href="#af85756be609cadfcf4cb5dd4fc3e6776">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2562e7a7070fa64c60dc0df83434c60f">runOnEquivalenceClass</a> (const EqClassKey &amp;EqClassKey, ArrayRef&lt; Instruction * &gt; EqClass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Runs the vectorizer on one equivalence class, i.e. <a href="#a2562e7a7070fa64c60dc0df83434c60f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48836ee09daa3ebaca10d64148776b08">runOnChain</a> (Chain &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Runs the vectorizer on one chain, i.e. <a href="#a48836ee09daa3ebaca10d64148776b08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#afd1adfcbfce320e6265935ce4d6299a3">Chain</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bba65a9f72ca8d5c3cb9650b787674d">splitChainByContiguity</a> (Chain &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Splits the chain into subchains of instructions which read/write a contiguous block of memory. <a href="#a5bba65a9f72ca8d5c3cb9650b787674d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#afd1adfcbfce320e6265935ce4d6299a3">Chain</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7852ee2c00ed3edbe297fb0817ad1f9">splitChainByMayAliasInstrs</a> (Chain &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Splits the chain into subchains where it's safe to hoist loads up to the beginning of the sub-chain and it's safe to sink loads up to the end of the sub-chain. <a href="#ab7852ee2c00ed3edbe297fb0817ad1f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#afd1adfcbfce320e6265935ce4d6299a3">Chain</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad91de2dfd1aa6516c5b570ef3885e9">splitChainByAlignment</a> (Chain &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Splits the chain into subchains that make legal, aligned accesses. <a href="#a3ad91de2dfd1aa6516c5b570ef3885e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce4cc970bd1d4cc77962aa0e1d2ddd8">vectorizeChain</a> (Chain &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts the instrs in the chain into a single vectorized load or store. <a href="#a3ce4cc970bd1d4cc77962aa0e1d2ddd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee97e7ba9b929a6855625ee5e692766a">getConstantOffset</a> (Value *PtrA, Value *PtrB, Instruction *ContextInst, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to compute the offset in bytes PtrB - PtrA. <a href="#aee97e7ba9b929a6855625ee5e692766a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d2b505f21aa079d8e9bd2f70f31dd11">getConstantOffsetComplexAddrs</a> (Value *PtrA, Value *PtrB, Instruction *ContextInst, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9209bae9e05ceb37771220578cae97">getConstantOffsetSelects</a> (Value *PtrA, Value *PtrB, Instruction *ContextInst, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaad3d37d85a554352bac0a965a6270b9">getChainElemTy</a> (const Chain &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the element type of the vector that the chain will load or store. <a href="#aaad3d37d85a554352bac0a965a6270b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsLoadChain&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0c2e6c32b60d80acb3a91698e4981eb">isSafeToMove</a> (Instruction *ChainElem, Instruction *ChainBegin, const DenseMap&lt; Instruction *, APInt &gt; &amp;ChainOffsets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines whether <a href="/web-llvm/docs/api/structs/anonymous-loadstorevectorizer-cpp-/chainelem">ChainElem</a> can be moved up (if IsLoad) or down (if !IsLoad) to ChainBegin – i.e. <a href="#af0c2e6c32b60d80acb3a91698e4981eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f036139bd7589dc314c910eb8f9ccac">mergeEquivalenceClasses</a> (EquivalenceClassMap &amp;EQClasses) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merges the equivalence classes if they have underlying objects that differ by one level of indirection (i.e., one is a getelementptr and the other is the base pointer in that getelementptr). <a href="#a2f036139bd7589dc314c910eb8f9ccac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#a88103682ba6de27fe6bf8d5915c3e210">EquivalenceClassMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8ab5911007fa9bfa8a5a4cab33ab396">collectEquivalenceClasses</a> (BasicBlock::iterator Begin, BasicBlock::iterator End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collects loads and stores grouped by "equivalence class", where: <a href="#af8ab5911007fa9bfa8a5a4cab33ab396">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#afd1adfcbfce320e6265935ce4d6299a3">Chain</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad16a1dc169f5a7edfcc54159ea79db81">gatherChains</a> (ArrayRef&lt; Instruction * &gt; Instrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Partitions Instrs into "chains" where every instruction has a known constant offset from the first instr in the chain. <a href="#ad16a1dc169f5a7edfcc54159ea79db81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8da6a1fe363454ad212d50c27dff333">F</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40c465dace2a71d4d481410a859024a">AA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eb6907fd589e54a63afaba2639ed169">AC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ebe188942cf5ef846312dea7ea4d68">DT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ddfb1f78060cae980c9b799dff22d7f">SE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae36e9f273c9b03c6a754ae90fabad5a2">TTI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3502fb73ab2a2da0425486e742b318">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c57aff3772ce8f0c655252afc00f27a">Builder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17eb7a243688de2afa564fdb797e759c">ToErase</a></td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dc70c1bdded1350e803a64fdf123bfa">MaxDepth</a> = 3</td>
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


<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Vectorizer() {#a2fe1ef32d92d660691a7ea8c03747fb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoadStoreVectorizer.cpp}::Vectorizer::Vectorizer (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> &amp; AA, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loadstorevectorizer-cpp-/loadstorevectorizerlegacypass/#aded951af0d41cd9dd8c76609c67ca771">anonymous{LoadStoreVectorizer.cpp}::LoadStoreVectorizerLegacyPass::runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isSafeToMove() {#af0c2e6c32b60d80acb3a91698e4981eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsLoadChain&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoadStoreVectorizer.cpp}::Vectorizer::isSafeToMove (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ChainElem, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ChainBegin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; &amp; ChainOffsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a6cf1231457e9dca2d160ee236da9dfaa">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::at</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#accd9b4c07df33541bf14a4e2a01fb35b">anonymous{LoadStoreVectorizer.cpp}::isInvariantLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a854abfc88bcd24e3878e2c9ab1f70fd3">llvm::isModOrRefSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a728f79528ca8659e15d00c1e6818b316">llvm::isModSet</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a7e8226e6453c8bcf7e5c06d28b1e207b">llvm::APInt::sle</a>.</p>

</div>
</div>

### run() {#afdc19a1fe655b43b92647431e2e8ec8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Vectorizer::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abff5a423c1f45e23958dde8ee695c9a9">llvm::isGuaranteedToTransferExecutionToSuccessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41c4916e8090ce40598db1a8dd2a5d5d">llvm::post_order</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1106b8a15061e8494873e10bb8a364e5">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collectEquivalenceClasses() {#af8ab5911007fa9bfa8a5a4cab33ab396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EquivalenceClassMap Vectorizer::collectEquivalenceClasses (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collects loads and stores grouped by "equivalence class", where:</p>


<ul class="doxyList ">
<li>all elements in an eq class are a load or all are a store,</li>
<li>they all load/store the same element size (it's OK to have e.g. i8 and &lt;4 x i8&gt; in the same class, but not i32 and &lt;4 x i8&gt;), and</li>
<li>they all have the same value for <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">getUnderlyingObject()</a>.</li>
</ul>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### gatherChains() {#ad16a1dc169f5a7edfcc54159ea79db81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; Chain &gt; Vectorizer::gatherChains (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; Instrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Partitions Instrs into "chains" where every instruction has a known constant offset from the first instr in the chain.</p>


<p>Postcondition: For all i, ret[i][0].second == 0, because the first instr in the chain is the leader, and an instr touches distance 0 from itself.</p>


<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### getChainElemTy() {#aaad3d37d85a554352bac0a965a6270b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Vectorizer::getChainElemTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#afd1adfcbfce320e6265935ce4d6299a3">Chain</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the element type of the vector that the chain will load or store.</p>


<p>This is nontrivial because the chain may contain elements of different types; e.g. it's legal to have a chain that contains both i32 and float.</p>


<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### getConstantOffset() {#aee97e7ba9b929a6855625ee5e692766a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; APInt &gt; Vectorizer::getConstantOffset (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PtrA, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PtrB, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ContextInst, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to compute the offset in bytes PtrB - PtrA.</p>

<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### getConstantOffsetComplexAddrs() {#a2d2b505f21aa079d8e9bd2f70f31dd11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; APInt &gt; Vectorizer::getConstantOffsetComplexAddrs (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PtrA, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PtrB, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ContextInst, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### getConstantOffsetSelects() {#aac9209bae9e05ceb37771220578cae97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; APInt &gt; Vectorizer::getConstantOffsetSelects (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PtrA, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PtrB, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ContextInst, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### isSafeToMove() {#af0c2e6c32b60d80acb3a91698e4981eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsLoadChain&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoadStoreVectorizer.cpp}::Vectorizer::isSafeToMove (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ChainElem, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ChainBegin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; &amp; ChainOffsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determines whether <a href="/web-llvm/docs/api/structs/anonymous-loadstorevectorizer-cpp-/chainelem">ChainElem</a> can be moved up (if IsLoad) or down (if !IsLoad) to ChainBegin – i.e.</p>


<p>there are no intervening may-alias instructions.</p>


<p>The map ChainElemOffsets must contain all of the elements in [ChainBegin, <a href="/web-llvm/docs/api/structs/anonymous-loadstorevectorizer-cpp-/chainelem">ChainElem</a>] and their offsets from some arbitrary base address. It's ok if it contains additional entries.</p>


<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### mergeEquivalenceClasses() {#a2f036139bd7589dc314c910eb8f9ccac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Vectorizer::mergeEquivalenceClasses (<a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#a88103682ba6de27fe6bf8d5915c3e210">EquivalenceClassMap</a> &amp; EQClasses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merges the equivalence classes if they have underlying objects that differ by one level of indirection (i.e., one is a getelementptr and the other is the base pointer in that getelementptr).</p>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### runOnChain() {#a48836ee09daa3ebaca10d64148776b08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Vectorizer::runOnChain (<a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#afd1adfcbfce320e6265935ce4d6299a3">Chain</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Runs the vectorizer on one chain, i.e.</p>


<p>a subset of an equivalence class where all instructions access a known, constant offset from the first instruction.</p>


<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### runOnEquivalenceClass() {#a2562e7a7070fa64c60dc0df83434c60f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Vectorizer::runOnEquivalenceClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#aaee92d4e61ec828be1e2db5a7f63f136">EqClassKey</a> &amp; EqClassKey, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; EqClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Runs the vectorizer on one equivalence class, i.e.</p>


<p>one set of loads/stores in the same BB with the same value for <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">getUnderlyingObject()</a> etc.</p>


<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### runOnPseudoBB() {#af85756be609cadfcf4cb5dd4fc3e6776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Vectorizer::runOnPseudoBB (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Runs the vectorizer on a "pseudo basic block", which is a range of instructions [Begin, End) within one BB all of which have isGuaranteedToTransferExecutionToSuccessor(I) == true.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### splitChainByAlignment() {#a3ad91de2dfd1aa6516c5b570ef3885e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; Chain &gt; Vectorizer::splitChainByAlignment (<a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#afd1adfcbfce320e6265935ce4d6299a3">Chain</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Splits the chain into subchains that make legal, aligned accesses.</p>


<p>Discards any length-1 subchains.</p>


<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### splitChainByContiguity() {#a5bba65a9f72ca8d5c3cb9650b787674d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; Chain &gt; Vectorizer::splitChainByContiguity (<a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#afd1adfcbfce320e6265935ce4d6299a3">Chain</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Splits the chain into subchains of instructions which read/write a contiguous block of memory.</p>


<p>Discards any length-1 subchains (because there's nothing to vectorize in there).</p>


<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### splitChainByMayAliasInstrs() {#ab7852ee2c00ed3edbe297fb0817ad1f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; Chain &gt; Vectorizer::splitChainByMayAliasInstrs (<a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#afd1adfcbfce320e6265935ce4d6299a3">Chain</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Splits the chain into subchains where it's safe to hoist loads up to the beginning of the sub-chain and it's safe to sink loads up to the end of the sub-chain.</p>


<p>Discards any length-1 subchains.</p>


<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### vectorizeChain() {#a3ce4cc970bd1d4cc77962aa0e1d2ddd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Vectorizer::vectorizeChain (<a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#afd1adfcbfce320e6265935ce4d6299a3">Chain</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Converts the instrs in the chain into a single vectorized load or store.</p>


<p>Adds the old scalar loads/stores to ToErase.</p>


<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#ad40c465dace2a71d4d481410a859024a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis&amp; anonymous{LoadStoreVectorizer.cpp}::Vectorizer::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### AC {#a5eb6907fd589e54a63afaba2639ed169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; anonymous{LoadStoreVectorizer.cpp}::Vectorizer::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### Builder {#a0c57aff3772ce8f0c655252afc00f27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilder anonymous{LoadStoreVectorizer.cpp}::Vectorizer::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### DL {#abc3502fb73ab2a2da0425486e742b318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{LoadStoreVectorizer.cpp}::Vectorizer::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### DT {#af6ebe188942cf5ef846312dea7ea4d68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; anonymous{LoadStoreVectorizer.cpp}::Vectorizer::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### F {#aa8da6a1fe363454ad212d50c27dff333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{LoadStoreVectorizer.cpp}::Vectorizer::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### SE {#a7ddfb1f78060cae980c9b799dff22d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; anonymous{LoadStoreVectorizer.cpp}::Vectorizer::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### ToErase {#a17eb7a243688de2afa564fdb797e759c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 128&gt; anonymous{LoadStoreVectorizer.cpp}::Vectorizer::ToErase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

### TTI {#ae36e9f273c9b03c6a754ae90fabad5a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo&amp; anonymous{LoadStoreVectorizer.cpp}::Vectorizer::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### MaxDepth {#a8dc70c1bdded1350e803a64fdf123bfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{LoadStoreVectorizer.cpp}::Vectorizer::MaxDepth = 3</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp">LoadStoreVectorizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
