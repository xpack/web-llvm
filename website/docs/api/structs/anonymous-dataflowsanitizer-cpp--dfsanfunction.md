---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DFSanFunction` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{DataFlowSanitizer.cpp}::DFSanFunction { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8c5c5b0f17f72c5cb46a534a46f80e7">DFSanFunction</a> (DataFlowSanitizer &amp;DFS, Function *F, bool IsNativeABI, bool IsForceZeroLabels, TargetLibraryInfo &amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5759fab5ef52a7e3ee96af7eb5e42c64">getArgTLS</a> (Type *T, unsigned ArgOffset, IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the shadow address for a given function argument. <a href="#a5759fab5ef52a7e3ee96af7eb5e42c64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1eff2ac03032a7ba69baaaa62904ca0">getRetvalTLS</a> (Type *T, IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the shadow address for a return value. <a href="#ae1eff2ac03032a7ba69baaaa62904ca0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ea2f1d59ceaa0deb10ae51f8e1d71d9">getArgOriginTLS</a> (unsigned ArgNo, IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the origin address for a given function argument. <a href="#a1ea2f1d59ceaa0deb10ae51f8e1d71d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba279a3c1456d5e86e5ba8d509807fd">getRetvalOriginTLS</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the origin address for a return value. <a href="#a6ba279a3c1456d5e86e5ba8d509807fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e596bf4044aed2cf004290fe49a1a03">getOrigin</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae548511913b150465cebb7956571da83">setOrigin</a> (Instruction *I, Value *Origin)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a609c78a9c329baf4d3aa095a80784a4c">combineOperandOrigins</a> (Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates IR to compute the origin of the last operand with a taint label. <a href="#a609c78a9c329baf4d3aa095a80784a4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92dd8bdf6470ea49d360683ec825dd4a">combineOrigins</a> (const std::vector&lt; Value * &gt; &amp;Shadows, const std::vector&lt; Value * &gt; &amp;Origins, BasicBlock::iterator Pos, ConstantInt *Zero=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Before the instruction Pos, generates IR to compute the last origin with a taint label. <a href="#a92dd8bdf6470ea49d360683ec825dd4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b7b17b8c343bd803b7381e95331701c">getShadow</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a853ce539733c2eaa910c92d9cad6062a">setShadow</a> (Instruction *I, Value *Shadow)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52fb7e69634a02e492f7285741b43f84">combineShadows</a> (Value *V1, Value *V2, BasicBlock::iterator Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates IR to compute the union of the two given shadows, inserting it before Pos. <a href="#a52fb7e69634a02e492f7285741b43f84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4a2cdec5e0ca4bb9bbdb2f8a4310fd6">combineShadowsThenConvert</a> (Type *T, Value *V1, Value *V2, BasicBlock::iterator Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combines the shadow values of V1 and V2, then converts the combined value with primitive type into a shadow value with the original type T. <a href="#ac4a2cdec5e0ca4bb9bbdb2f8a4310fd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d79bd0b027705195d79619a1d0450a">combineOperandShadows</a> (Instruction *Inst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca49f1e83822401c87d4984bf57694a6">loadShadowOrigin</a> (Value *Addr, uint64_t Size, Align InstAlignment, BasicBlock::iterator Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates IR to load shadow and origin corresponding to bytes [<span class="doxyComputerOutput">Addr</span>, <span class="doxyComputerOutput">Addr</span> + <span class="doxyComputerOutput">Size</span>), where addr has alignment <span class="doxyComputerOutput">InstAlignment</span>, and take the union of each of those shadows. <a href="#aca49f1e83822401c87d4984bf57694a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1616baf1b22efae9f17bb3d499ac8931">storePrimitiveShadowOrigin</a> (Value *Addr, uint64_t Size, Align InstAlignment, Value *PrimitiveShadow, Value *Origin, BasicBlock::iterator Pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af512bce8ac0099600eaf443bde3d975f">expandFromPrimitiveShadow</a> (Type *T, Value *PrimitiveShadow, BasicBlock::iterator Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Applies PrimitiveShadow to all primitive subtypes of T, returning the expanded shadow value. <a href="#af512bce8ac0099600eaf443bde3d975f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b65c40648346b8d99dd58a2d3d318e9">collapseToPrimitiveShadow</a> (Value *Shadow, BasicBlock::iterator Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collapses Shadow into a single primitive shadow value, unioning all primitive shadow values in the process. <a href="#a4b65c40648346b8d99dd58a2d3d318e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabfea0675d601df03f2b2bda2bceb157">storeZeroPrimitiveShadow</a> (Value *Addr, uint64_t Size, Align ShadowAlign, BasicBlock::iterator Pos)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bdefa4c8e1d99d585232cf526147891">getShadowAlign</a> (Align InstAlignment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb18e068cfa4ee49c6cc19a2ea5278d9">addConditionalCallbacksIfEnabled</a> (Instruction &amp;I, Value *Condition)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac04b6d4e5d3715d33fee0cf6c80a15c8">addReachesFunctionCallbacksIfEnabled</a> (IRBuilder&lt;&gt; &amp;IRB, Instruction &amp;I, Value *Data)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc28d73804bc12a7a70c2e323ccb45fd">isLookupTableConstant</a> (Value *P)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class AggregateType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a08920d8002e237eb7a2b55b8134aaad6">collapseAggregateShadow</a> (AggregateType *AT, Value *Shadow, IRBuilder&lt;&gt; &amp;IRB)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class AggregateType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a08920d8002e237eb7a2b55b8134aaad6">collapseAggregateShadow</a> (AggregateType *AT, Value *Shadow, IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collapses the shadow with aggregate type into a single primitive shadow value. <a href="#a08920d8002e237eb7a2b55b8134aaad6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91ab02b8c74269ddde83303fa4514df5">collapseToPrimitiveShadow</a> (Value *Shadow, IRBuilder&lt;&gt; &amp;IRB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43045cbf2529a8a24b8e01c9dc5963fa">getShadowForTLSArgument</a> (Argument *A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the shadow value of an argument A. <a href="#a43045cbf2529a8a24b8e01c9dc5963fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318a54739deed47cd3bb219a7e95a65b">loadShadowFast</a> (Value *ShadowAddr, Value *OriginAddr, uint64_t Size, Align ShadowAlign, Align OriginAlign, Value *FirstOrigin, BasicBlock::iterator Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The fast path of loading shadows. <a href="#a318a54739deed47cd3bb219a7e95a65b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b094311af3fb65b6a4b9e3c6ef0258e">getOriginAlign</a> (Align InstAlignment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bbd8d4c945b5d02f562d6567e5c9a5e">useCallbackLoadLabelAndOrigin</a> (uint64_t Size, Align InstAlignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Because 4 contiguous bytes share one 4-byte origin, the most accurate load is __dfsan_load_label_and_origin. <a href="#a8bbd8d4c945b5d02f562d6567e5c9a5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be13ba9d35bcef8bc7eb00a858dbf47">updateOrigin</a> (Value *V, IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a chain at the current stack with previous origin V. <a href="#a6be13ba9d35bcef8bc7eb00a858dbf47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf49498f1f50715b6ed34d12d9d72dc3">updateOriginIfTainted</a> (Value *Shadow, Value *Origin, IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a chain at the current stack with previous origin V if Shadow is tainted. <a href="#abf49498f1f50715b6ed34d12d9d72dc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6703435154fcac958e856758d9166f09">originToIntptr</a> (IRBuilder&lt;&gt; &amp;IRB, Value *Origin)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an Intptr = Origin | Origin &lt;&lt; 32 if Intptr's size is 64. <a href="#a6703435154fcac958e856758d9166f09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089eaa5b94881cf92a59f74bee02f92b">paintOrigin</a> (IRBuilder&lt;&gt; &amp;IRB, Value *Origin, Value *StoreOriginAddr, uint64_t StoreOriginSize, Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores Origin into the address range [StoreOriginAddr, StoreOriginAddr + Size). <a href="#a089eaa5b94881cf92a59f74bee02f92b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67f31096683389ae32883513c0b32f07">storeOrigin</a> (BasicBlock::iterator Pos, Value *Addr, uint64_t Size, Value *Shadow, Value *Origin, Value *StoreOriginAddr, Align InstAlignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores Origin in terms of its Shadow value. <a href="#a67f31096683389ae32883513c0b32f07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d6a258f4d4ba2a638e878ab85d1b48">convertToBool</a> (Value *V, IRBuilder&lt;&gt; &amp;IRB, const Twine &amp;Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a scalar value to an i1 by comparing with 0. <a href="#ab0d6a258f4d4ba2a638e878ab85d1b48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20e91ee0f05eafb079eb896a23b60e43">shouldInstrumentWithCall</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c1bc93430ac199974bb787017743376">loadShadowOriginSansLoadTracking</a> (Value *Addr, uint64_t Size, Align InstAlignment, BasicBlock::iterator Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates IR to load shadow and origin corresponding to bytes [<span class="doxyComputerOutput">Addr</span>, <span class="doxyComputerOutput">Addr</span> + <span class="doxyComputerOutput">Size</span>), where addr has alignment <span class="doxyComputerOutput">InstAlignment</span>, and take the union of each of those shadows. <a href="#a8c1bc93430ac199974bb787017743376">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer">DataFlowSanitizer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95173e429ac64ad7584ff95a36d39b98">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e6c855198ed4beffa4af56bcfe5f4fa">DT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe0381e7237b33d93121d98e68d58d43">IsNativeABI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c9aa49e5cfc560471f72b0a0b72e368">IsForceZeroLabels</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27316d777114a9ce32af8834d7ee206f">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3624367c2faa9620fe2fba48078f011">LabelReturnAlloca</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac005470c874f6ef4a6e3cf96ba739e3c">OriginReturnAlloca</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18f1fe1eec7040abc10fffdf41a2f96">ValShadowMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae13923e40e5bb88596e16e20d44c3a05">ValOriginMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa54fc6dfeba0265b130001781f606010">AllocaShadowMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da03bf9c3f0c03c9b628b7eda42db1e">AllocaOriginMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/phifixupelement">PHIFixupElement</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefe636103263c2f6bb2f30b56cc339d0">PHIFixups</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae661edba632a774dfa41217e00b02300">SkipInsts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b93b5c0d047eba65daf2d3afcf31b9">NonZeroChecks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/cachedshadow">CachedShadow</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef62266aa7ddab4b91e67bde55fa5ec3">CachedShadows</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a value to its latest shadow value in terms of domination tree. <a href="#aef62266aa7ddab4b91e67bde55fa5ec3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeccdffea142ea41bba8c5ebc9718a5de">CachedCollapsedShadows</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a value to its latest collapsed shadow value it was converted to in terms of domination tree. <a href="#aeccdffea142ea41bba8c5ebc9718a5de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7f730268a549f710f28795d3524ce2e">ShadowElements</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7d024c791916c39183f5c9c980f44d">NumOriginStores</a> = 0</td>
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


<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DFSanFunction() {#ab8c5c5b0f17f72c5cb46a534a46f80e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::DFSanFunction (<a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer">DataFlowSanitizer</a> &amp; DFS, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, bool IsNativeABI, bool IsForceZeroLabels, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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



<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="#a9e6c855198ed4beffa4af56bcfe5f4fa">DT</a>, <a href="#a95173e429ac64ad7584ff95a36d39b98">F</a>, <a href="#a7c9aa49e5cfc560471f72b0a0b72e368">IsForceZeroLabels</a>, <a href="#abe0381e7237b33d93121d98e68d58d43">IsNativeABI</a> and <a href="#a27316d777114a9ce32af8834d7ee206f">TLI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addConditionalCallbacksIfEnabled() {#abb18e068cfa4ee49c6cc19a2ea5278d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DFSanFunction::addConditionalCallbacksIfEnabled (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Condition)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a950f5f9cffc7bdd184f8e6a3f8317483">ClConditionalCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="#a9e596bf4044aed2cf004290fe49a1a03">getOrigin</a>, <a href="#a7b7b17b8c343bd803b7381e95331701c">getShadow</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### addReachesFunctionCallbacksIfEnabled() {#ac04b6d4e5d3715d33fee0cf6c80a15c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DFSanFunction::addReachesFunctionCallbacksIfEnabled (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a5780a333f75f22ac7d0c24e0a8e29b3a">ClReachesFunctionCallbacks</a>, <a href="#a4b65c40648346b8d99dd58a2d3d318e9">collapseToPrimitiveShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#af377188a476a2d71184b0498a136fd1d">llvm::IRBuilderBase::CreateGlobalString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#a4ff1bb484be62f8dac94fc087f72f524">llvm::DebugLoc::get</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#a427c256af834975c7869ad28fac00563">llvm::DebugLoc::getLine</a>, <a href="#a9e596bf4044aed2cf004290fe49a1a03">getOrigin</a>, <a href="#a7b7b17b8c343bd803b7381e95331701c">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>.</p>

</div>
</div>

### collapseAggregateShadow() {#a08920d8002e237eb7a2b55b8134aaad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class AggregateType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{DataFlowSanitizer.cpp}::DFSanFunction::collapseAggregateShadow (AggregateType * AT, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shadow, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1003 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="#a4b65c40648346b8d99dd58a2d3d318e9">collapseToPrimitiveShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a> and <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>.</p>

</div>
</div>

### collapseToPrimitiveShadow() {#a4b65c40648346b8d99dd58a2d3d318e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::collapseToPrimitiveShadow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shadow, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collapses Shadow into a single primitive shadow value, unioning all primitive shadow values in the process.</p>


<p>Returns the final primitive shadow value.</p>


<p>CTP({V1,V2, ...}) = UNION(CFP(V1,PS),CFP(V2,PS),...) CTP([V1,V2,...]) = UNION(CFP(V1,PS),CFP(V2,PS),...) CTP(other types, PS) = PS</p>


<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="#aeccdffea142ea41bba8c5ebc9718a5de">CachedCollapsedShadows</a>, <a href="#a4b65c40648346b8d99dd58a2d3d318e9">collapseToPrimitiveShadow</a>, <a href="#a9e6c855198ed4beffa4af56bcfe5f4fa">DT</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#ac04b6d4e5d3715d33fee0cf6c80a15c8">addReachesFunctionCallbacksIfEnabled</a>, <a href="#a08920d8002e237eb7a2b55b8134aaad6">collapseAggregateShadow</a>, <a href="#a4b65c40648346b8d99dd58a2d3d318e9">collapseToPrimitiveShadow</a>, <a href="#a92dd8bdf6470ea49d360683ec825dd4a">combineOrigins</a>, <a href="#a52fb7e69634a02e492f7285741b43f84">combineShadows</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>.</p>

</div>
</div>

### combineOperandOrigins() {#a609c78a9c329baf4d3aa095a80784a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::combineOperandOrigins (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates IR to compute the origin of the last operand with a taint label.</p>

<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="#a92dd8bdf6470ea49d360683ec825dd4a">combineOrigins</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#a9e596bf4044aed2cf004290fe49a1a03">getOrigin</a>, <a href="#a7b7b17b8c343bd803b7381e95331701c">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### combineOperandShadows() {#ad7d79bd0b027705195d79619a1d0450a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::combineOperandShadows (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="#a52fb7e69634a02e492f7285741b43f84">combineShadows</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="#af512bce8ac0099600eaf443bde3d975f">expandFromPrimitiveShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#a7b7b17b8c343bd803b7381e95331701c">getShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### combineOrigins() {#a92dd8bdf6470ea49d360683ec825dd4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::combineOrigins (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Shadows, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Origins, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * Zero=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Before the instruction Pos, generates IR to compute the last origin with a taint label.</p>


<p>Labels and origins are from vectors Shadows and Origins correspondingly. The generated IR is like Sn-1 != Zero ? On-1: ... S2 != Zero ? O2: S1 != Zero ? O1: O0 When Zero is nullptr, it uses ZeroPrimitiveShadow. Otherwise it can be zeros with other bitwidths.</p>


<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b65c40648346b8d99dd58a2d3d318e9">collapseToPrimitiveShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ae4b6abe77abf42fb02081a6cc41a0132">llvm::Constant::isNullValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a609c78a9c329baf4d3aa095a80784a4c">combineOperandOrigins</a>.</p>

</div>
</div>

### combineShadows() {#a52fb7e69634a02e492f7285741b43f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::combineShadows (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates IR to compute the union of the two given shadows, inserting it before Pos.</p>


<p>The combined value is with primitive type.</p>


<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/cachedshadow/#a3302fa22452f19838e2c22229997414b">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::CachedShadow::Block</a>, <a href="#aef62266aa7ddab4b91e67bde55fa5ec3">CachedShadows</a>, <a href="#a4b65c40648346b8d99dd58a2d3d318e9">collapseToPrimitiveShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="#a9e6c855198ed4beffa4af56bcfe5f4fa">DT</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/cachedshadow/#a4d3d150e04f7a3bc563f80cb5708b4c5">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::CachedShadow::Shadow</a>, <a href="#ad7f730268a549f710f28795d3524ce2e">ShadowElements</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#ad7d79bd0b027705195d79619a1d0450a">combineOperandShadows</a> and <a href="#ac4a2cdec5e0ca4bb9bbdb2f8a4310fd6">combineShadowsThenConvert</a>.</p>

</div>
</div>

### combineShadowsThenConvert() {#ac4a2cdec5e0ca4bb9bbdb2f8a4310fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::combineShadowsThenConvert (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combines the shadow values of V1 and V2, then converts the combined value with primitive type into a shadow value with the original type T.</p>

<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="#a52fb7e69634a02e492f7285741b43f84">combineShadows</a> and <a href="#af512bce8ac0099600eaf443bde3d975f">expandFromPrimitiveShadow</a>.</p>

</div>
</div>

### expandFromPrimitiveShadow() {#af512bce8ac0099600eaf443bde3d975f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::expandFromPrimitiveShadow (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PrimitiveShadow, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Applies PrimitiveShadow to all primitive subtypes of T, returning the expanded shadow value.</p>


<p>EFP({T1,T2, ...}, PS) = {EFP(T1,PS),EFP(T2,PS),...} EFP([n x T], PS) = [n x EFP(T,PS)] EFP(other types, PS) = PS</p>


<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="#aeccdffea142ea41bba8c5ebc9718a5de">CachedCollapsedShadows</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a587c4289ae52d2bea98482248fac1749">expandFromPrimitiveShadowRecursive</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#ad7d79bd0b027705195d79619a1d0450a">combineOperandShadows</a> and <a href="#ac4a2cdec5e0ca4bb9bbdb2f8a4310fd6">combineShadowsThenConvert</a>.</p>

</div>
</div>

### getArgOriginTLS() {#a1ea2f1d59ceaa0deb10ae51f8e1d71d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::getArgOriginTLS (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes the origin address for a given function argument.</p>


<p>Origin = ArgOriginTLS[ArgNo].</p>


<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa8ee5dc4e4a1b26c4bdf1a574eefe2fc">llvm::IRBuilderBase::CreateConstInBoundsGEP2_64</a> and <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>.</p>


<p>Referenced by <a href="#a9e596bf4044aed2cf004290fe49a1a03">getOrigin</a>.</p>

</div>
</div>

### getArgTLS() {#a5759fab5ef52a7e3ee96af7eb5e42c64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::getArgTLS (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T, unsigned ArgOffset, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes the shadow address for a given function argument.</p>


<p>Shadow = ArgTLS+ArgOffset.</p>


<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a> and <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>.</p>

</div>
</div>

### getOrigin() {#a9e596bf4044aed2cf004290fe49a1a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::getOrigin (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a95173e429ac64ad7584ff95a36d39b98">F</a>, <a href="#a1ea2f1d59ceaa0deb10ae51f8e1d71d9">getArgOriginTLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#abe0381e7237b33d93121d98e68d58d43">IsNativeABI</a> and <a href="#ae13923e40e5bb88596e16e20d44c3a05">ValOriginMap</a>.</p>


<p>Referenced by <a href="#abb18e068cfa4ee49c6cc19a2ea5278d9">addConditionalCallbacksIfEnabled</a>, <a href="#ac04b6d4e5d3715d33fee0cf6c80a15c8">addReachesFunctionCallbacksIfEnabled</a>, <a href="#a609c78a9c329baf4d3aa095a80784a4c">combineOperandOrigins</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>.</p>

</div>
</div>

### getRetvalOriginTLS() {#a6ba279a3c1456d5e86e5ba8d509807fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::getRetvalOriginTLS ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes the origin address for a return value.</p>

<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Reference <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>.</p>

</div>
</div>

### getRetvalTLS() {#ae1eff2ac03032a7ba69baaaa62904ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::getRetvalTLS (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes the shadow address for a return value.</p>

<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a> and <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>.</p>

</div>
</div>

### getShadow() {#a7b7b17b8c343bd803b7381e95331701c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::getShadow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a7c9aa49e5cfc560471f72b0a0b72e368">IsForceZeroLabels</a>, <a href="#abe0381e7237b33d93121d98e68d58d43">IsNativeABI</a>, <a href="#a76b93b5c0d047eba65daf2d3afcf31b9">NonZeroChecks</a> and <a href="#af18f1fe1eec7040abc10fffdf41a2f96">ValShadowMap</a>.</p>


<p>Referenced by <a href="#abb18e068cfa4ee49c6cc19a2ea5278d9">addConditionalCallbacksIfEnabled</a>, <a href="#ac04b6d4e5d3715d33fee0cf6c80a15c8">addReachesFunctionCallbacksIfEnabled</a>, <a href="#a609c78a9c329baf4d3aa095a80784a4c">combineOperandOrigins</a>, <a href="#ad7d79bd0b027705195d79619a1d0450a">combineOperandShadows</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>.</p>

</div>
</div>

### getShadowAlign() {#a2bdefa4c8e1d99d585232cf526147891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align DFSanFunction::getShadowAlign (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> InstAlignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a5f58d18a4fdfd2fda2d3f931f869e2a1">ClPreserveAlignment</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a1616baf1b22efae9f17bb3d499ac8931">storePrimitiveShadowOrigin</a>.</p>

</div>
</div>

### isLookupTableConstant() {#acc28d73804bc12a7a70c2e323ccb45fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DFSanFunction::isLookupTableConstant (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### loadShadowOrigin() {#aca49f1e83822401c87d4984bf57694a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; DFSanFunction::loadShadowOrigin (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> InstAlignment, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates IR to load shadow and origin corresponding to bytes [<span class="doxyComputerOutput">Addr</span>, <span class="doxyComputerOutput">Addr</span> + <span class="doxyComputerOutput">Size</span>), where addr has alignment <span class="doxyComputerOutput">InstAlignment</span>, and take the union of each of those shadows.</p>


<p>The returned shadow always has primitive type.</p>


<p>When tracking loads is enabled, the returned origin is a chain at the current stack if the returned shadow is tainted.</p>


<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a4957fe1638b12eace3ecfaeaaa3c5b85">ClTrackOrigins</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### setOrigin() {#ae548511913b150465cebb7956571da83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DFSanFunction::setOrigin (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ae13923e40e5bb88596e16e20d44c3a05">ValOriginMap</a>.</p>

</div>
</div>

### setShadow() {#a853ce539733c2eaa910c92d9cad6062a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DFSanFunction::setShadow (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shadow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#af18f1fe1eec7040abc10fffdf41a2f96">ValShadowMap</a>.</p>

</div>
</div>

### storePrimitiveShadowOrigin() {#a1616baf1b22efae9f17bb3d499ac8931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DFSanFunction::storePrimitiveShadowOrigin (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> InstAlignment, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PrimitiveShadow, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="#a5da03bf9c3f0c03c9b628b7eda42db1e">AllocaOriginMap</a>, <a href="#aa54fc6dfeba0265b130001781f606010">AllocaShadowMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1ac3f0b68c9c78c4f9e1eb09cd415db8">llvm::IRBuilderBase::CreateConstGEP1_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="#a2bdefa4c8e1d99d585232cf526147891">getShadowAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#aabfea0675d601df03f2b2bda2bceb157">storeZeroPrimitiveShadow</a>.</p>

</div>
</div>

### storeZeroPrimitiveShadow() {#aabfea0675d601df03f2b2bda2bceb157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DFSanFunction::storeZeroPrimitiveShadow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ShadowAlign, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="#ae5891c006deae56c728ecb8f22aec419">DFS</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a1616baf1b22efae9f17bb3d499ac8931">storePrimitiveShadowOrigin</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collapseAggregateShadow() {#a08920d8002e237eb7a2b55b8134aaad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class AggregateType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{DataFlowSanitizer.cpp}::DFSanFunction::collapseAggregateShadow (AggregateType * AT, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shadow, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collapses the shadow with aggregate type into a single primitive shadow value.</p>

<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### collapseToPrimitiveShadow() {#a91ab02b8c74269ddde83303fa4514df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::collapseToPrimitiveShadow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shadow, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### convertToBool() {#ab0d6a258f4d4ba2a638e878ab85d1b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::convertToBool (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert a scalar value to an i1 by comparing with 0.</p>

<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### getOriginAlign() {#a7b094311af3fb65b6a4b9e3c6ef0258e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align DFSanFunction::getOriginAlign (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> InstAlignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### getShadowForTLSArgument() {#a43045cbf2529a8a24b8e01c9dc5963fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::getShadowForTLSArgument (<a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> * A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the shadow value of an argument A.</p>

<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### loadShadowFast() {#a318a54739deed47cd3bb219a7e95a65b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; DFSanFunction::loadShadowFast (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ShadowAddr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OriginAddr, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ShadowAlign, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> OriginAlign, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FirstOrigin, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The fast path of loading shadows.</p>

<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### loadShadowOriginSansLoadTracking() {#a8c1bc93430ac199974bb787017743376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; DFSanFunction::loadShadowOriginSansLoadTracking (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> InstAlignment, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates IR to load shadow and origin corresponding to bytes [<span class="doxyComputerOutput">Addr</span>, <span class="doxyComputerOutput">Addr</span> + <span class="doxyComputerOutput">Size</span>), where addr has alignment <span class="doxyComputerOutput">InstAlignment</span>, and take the union of each of those shadows.</p>


<p>The returned shadow always has primitive type.</p>


<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### originToIntptr() {#a6703435154fcac958e856758d9166f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::originToIntptr (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates an Intptr = Origin | Origin &lt;&lt; 32 if Intptr's size is 64.</p>


<p>Returns Origin otherwise.</p>


<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### paintOrigin() {#a089eaa5b94881cf92a59f74bee02f92b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DFSanFunction::paintOrigin (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StoreOriginAddr, uint64_t StoreOriginSize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores Origin into the address range [StoreOriginAddr, StoreOriginAddr + Size).</p>

<p>Definition at line 757 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### shouldInstrumentWithCall() {#a20e91ee0f05eafb079eb896a23b60e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DFSanFunction::shouldInstrumentWithCall ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### storeOrigin() {#a67f31096683389ae32883513c0b32f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DFSanFunction::storeOrigin (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shadow, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StoreOriginAddr, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> InstAlignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores Origin in terms of its Shadow value.</p>


<ul class="doxyList ">
<li>Do not write origins for zero shadows because we do not trace origins for untainted sinks.</li>
<li><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> __dfsan_maybe_store_origin if there are too many origin store instrumentations.</li>
</ul>

<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### updateOrigin() {#a6be13ba9d35bcef8bc7eb00a858dbf47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::updateOrigin (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a chain at the current stack with previous origin V.</p>

<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### updateOriginIfTainted() {#abf49498f1f50715b6ed34d12d9d72dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DFSanFunction::updateOriginIfTainted (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shadow, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a chain at the current stack with previous origin V if Shadow is tainted.</p>

<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### useCallbackLoadLabelAndOrigin() {#a8bbd8d4c945b5d02f562d6567e5c9a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DFSanFunction::useCallbackLoadLabelAndOrigin (uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> InstAlignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Because 4 contiguous bytes share one 4-byte origin, the most accurate load is __dfsan_load_label_and_origin.</p>


<p>This function returns the union of all labels and the origin of the first taint label. However this is an additional call with many instructions. To ensure common cases are fast, checks if it is possible to load labels and origins without using the callback function.</p>


<p>When enabling tracking load instructions, we always use __dfsan_load_label_and_origin to reduce code size.</p>


<p>Definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllocaOriginMap {#a5da03bf9c3f0c03c9b628b7eda42db1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AllocaInst *, AllocaInst *&gt; anonymous{DataFlowSanitizer.cpp}::DFSanFunction::AllocaOriginMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a1616baf1b22efae9f17bb3d499ac8931">storePrimitiveShadowOrigin</a>.</p>

</div>
</div>

### AllocaShadowMap {#aa54fc6dfeba0265b130001781f606010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AllocaInst *, AllocaInst *&gt; anonymous{DataFlowSanitizer.cpp}::DFSanFunction::AllocaShadowMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a1616baf1b22efae9f17bb3d499ac8931">storePrimitiveShadowOrigin</a>.</p>

</div>
</div>

### CachedCollapsedShadows {#aeccdffea142ea41bba8c5ebc9718a5de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, Value *&gt; anonymous{DataFlowSanitizer.cpp}::DFSanFunction::CachedCollapsedShadows</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps a value to its latest collapsed shadow value it was converted to in terms of domination tree.</p>


<p>When ClDebugNonzeroLabels is on, this cache is used at a post process where CFG blocks are split. So it does not cache <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> like CachedShadows, but uses domination between values.</p>


<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a4b65c40648346b8d99dd58a2d3d318e9">collapseToPrimitiveShadow</a> and <a href="#af512bce8ac0099600eaf443bde3d975f">expandFromPrimitiveShadow</a>.</p>

</div>
</div>

### CachedShadows {#aef62266aa7ddab4b91e67bde55fa5ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;Value *, Value *&gt;, CachedShadow&gt; anonymous{DataFlowSanitizer.cpp}::DFSanFunction::CachedShadows</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps a value to its latest shadow value in terms of domination tree.</p>

<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a52fb7e69634a02e492f7285741b43f84">combineShadows</a>.</p>

</div>
</div>

### DFS {#ae5891c006deae56c728ecb8f22aec419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataFlowSanitizer&amp; anonymous{DataFlowSanitizer.cpp}::DFSanFunction::DFS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#abb18e068cfa4ee49c6cc19a2ea5278d9">addConditionalCallbacksIfEnabled</a>, <a href="#ac04b6d4e5d3715d33fee0cf6c80a15c8">addReachesFunctionCallbacksIfEnabled</a>, <a href="#a08920d8002e237eb7a2b55b8134aaad6">collapseAggregateShadow</a>, <a href="#ad7d79bd0b027705195d79619a1d0450a">combineOperandShadows</a>, <a href="#a92dd8bdf6470ea49d360683ec825dd4a">combineOrigins</a>, <a href="#a52fb7e69634a02e492f7285741b43f84">combineShadows</a>, <a href="#ab8c5c5b0f17f72c5cb46a534a46f80e7">DFSanFunction</a>, <a href="#af512bce8ac0099600eaf443bde3d975f">expandFromPrimitiveShadow</a>, <a href="#a1ea2f1d59ceaa0deb10ae51f8e1d71d9">getArgOriginTLS</a>, <a href="#a5759fab5ef52a7e3ee96af7eb5e42c64">getArgTLS</a>, <a href="#a9e596bf4044aed2cf004290fe49a1a03">getOrigin</a>, <a href="#a6ba279a3c1456d5e86e5ba8d509807fd">getRetvalOriginTLS</a>, <a href="#ae1eff2ac03032a7ba69baaaa62904ca0">getRetvalTLS</a>, <a href="#a7b7b17b8c343bd803b7381e95331701c">getShadow</a>, <a href="#a2bdefa4c8e1d99d585232cf526147891">getShadowAlign</a>, <a href="#acc28d73804bc12a7a70c2e323ccb45fd">isLookupTableConstant</a>, <a href="#aca49f1e83822401c87d4984bf57694a6">loadShadowOrigin</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="#ae548511913b150465cebb7956571da83">setOrigin</a>, <a href="#a1616baf1b22efae9f17bb3d499ac8931">storePrimitiveShadowOrigin</a> and <a href="#aabfea0675d601df03f2b2bda2bceb157">storeZeroPrimitiveShadow</a>.</p>

</div>
</div>

### DT {#a9e6c855198ed4beffa4af56bcfe5f4fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree anonymous{DataFlowSanitizer.cpp}::DFSanFunction::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a4b65c40648346b8d99dd58a2d3d318e9">collapseToPrimitiveShadow</a>, <a href="#a52fb7e69634a02e492f7285741b43f84">combineShadows</a> and <a href="#ab8c5c5b0f17f72c5cb46a534a46f80e7">DFSanFunction</a>.</p>

</div>
</div>

### F {#a95173e429ac64ad7584ff95a36d39b98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{DataFlowSanitizer.cpp}::DFSanFunction::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#ab8c5c5b0f17f72c5cb46a534a46f80e7">DFSanFunction</a>, <a href="#a9e596bf4044aed2cf004290fe49a1a03">getOrigin</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>.</p>

</div>
</div>

### IsForceZeroLabels {#a7c9aa49e5cfc560471f72b0a0b72e368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DataFlowSanitizer.cpp}::DFSanFunction::IsForceZeroLabels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#ab8c5c5b0f17f72c5cb46a534a46f80e7">DFSanFunction</a> and <a href="#a7b7b17b8c343bd803b7381e95331701c">getShadow</a>.</p>

</div>
</div>

### IsNativeABI {#abe0381e7237b33d93121d98e68d58d43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DataFlowSanitizer.cpp}::DFSanFunction::IsNativeABI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#ab8c5c5b0f17f72c5cb46a534a46f80e7">DFSanFunction</a>, <a href="#a9e596bf4044aed2cf004290fe49a1a03">getOrigin</a> and <a href="#a7b7b17b8c343bd803b7381e95331701c">getShadow</a>.</p>

</div>
</div>

### LabelReturnAlloca {#ab3624367c2faa9620fe2fba48078f011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst* anonymous{DataFlowSanitizer.cpp}::DFSanFunction::LabelReturnAlloca = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### NonZeroChecks {#a76b93b5c0d047eba65daf2d3afcf31b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Value *&gt; anonymous{DataFlowSanitizer.cpp}::DFSanFunction::NonZeroChecks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a7b7b17b8c343bd803b7381e95331701c">getShadow</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>.</p>

</div>
</div>

### OriginReturnAlloca {#ac005470c874f6ef4a6e3cf96ba739e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst* anonymous{DataFlowSanitizer.cpp}::DFSanFunction::OriginReturnAlloca = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

### PHIFixups {#aefe636103263c2f6bb2f30b56cc339d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;PHIFixupElement&gt; anonymous{DataFlowSanitizer.cpp}::DFSanFunction::PHIFixups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>.</p>

</div>
</div>

### ShadowElements {#ad7f730268a549f710f28795d3524ce2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, std::set&lt;Value *&gt; &gt; anonymous{DataFlowSanitizer.cpp}::DFSanFunction::ShadowElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a52fb7e69634a02e492f7285741b43f84">combineShadows</a>.</p>

</div>
</div>

### SkipInsts {#ae661edba632a774dfa41217e00b02300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;Instruction *&gt; anonymous{DataFlowSanitizer.cpp}::DFSanFunction::SkipInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>.</p>

</div>
</div>

### TLI {#a27316d777114a9ce32af8834d7ee206f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo&amp; anonymous{DataFlowSanitizer.cpp}::DFSanFunction::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#ab8c5c5b0f17f72c5cb46a534a46f80e7">DFSanFunction</a>.</p>

</div>
</div>

### ValOriginMap {#ae13923e40e5bb88596e16e20d44c3a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, Value *&gt; anonymous{DataFlowSanitizer.cpp}::DFSanFunction::ValOriginMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a9e596bf4044aed2cf004290fe49a1a03">getOrigin</a> and <a href="#ae548511913b150465cebb7956571da83">setOrigin</a>.</p>

</div>
</div>

### ValShadowMap {#af18f1fe1eec7040abc10fffdf41a2f96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, Value *&gt; anonymous{DataFlowSanitizer.cpp}::DFSanFunction::ValShadowMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a7b7b17b8c343bd803b7381e95331701c">getShadow</a> and <a href="#a853ce539733c2eaa910c92d9cad6062a">setShadow</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NumOriginStores {#a7e7d024c791916c39183f5c9c980f44d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{DataFlowSanitizer.cpp}::DFSanFunction::NumOriginStores = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp">DataFlowSanitizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
