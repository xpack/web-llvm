---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mdbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MDBuilder` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MDBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2cd1bb39bb5642af61639f9e6d0aa0d">PCSection</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pair of PC section name with auxilliary constant data. <a href="#ad2cd1bb39bb5642af61639f9e6d0aa0d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6fc112f5890dbae8b1b8f3e90e5abbd">MDBuilder</a> (LLVMContext &amp;context)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7939b917f71d9664707d8ec51da88418">createString</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the given string as metadata. <a href="#a7939b917f71d9664707d8ec51da88418">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantasmetadata">ConstantAsMetadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a> (Constant *C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the given constant as metadata. <a href="#a3c8d885c5746db440058fc8a285126b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e9594f698a6092e755b6ce7ee6905cd">createFPMath</a> (float Accuracy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata with the given settings. <a href="#a5e9594f698a6092e755b6ce7ee6905cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75043d12a76b84200e9ed593719dc5eb">createBranchWeights</a> (uint32_t TrueWeight, uint32_t FalseWeight, bool IsExpected=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata containing two branch weights. <a href="#a75043d12a76b84200e9ed593719dc5eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba565f72261aa7d6207da89db949d991">createLikelyBranchWeights</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata containing two branch weights, with significant bias towards <span class="doxyComputerOutput">true</span> destination. <a href="#aba565f72261aa7d6207da89db949d991">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae609aeb09c2b1c9f03fb90228654b281">createUnlikelyBranchWeights</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata containing two branch weights, with significant bias towards <span class="doxyComputerOutput">false</span> destination. <a href="#ae609aeb09c2b1c9f03fb90228654b281">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff293fef41b4eb80fca7c47b2e2c99a">createBranchWeights</a> (ArrayRef&lt; uint32_t &gt; Weights, bool IsExpected=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata containing a number of branch weights. <a href="#adff293fef41b4eb80fca7c47b2e2c99a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cea521fb45003a63caeb04f2b13ec0b">createUnpredictable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata specifying that a branch or switch is unpredictable. <a href="#a8cea521fb45003a63caeb04f2b13ec0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a208093b76ef0d541b5e0d09498be189d">createFunctionEntryCount</a> (uint64_t Count, bool Synthetic, const DenseSet&lt; GlobalValue::GUID &gt; *Imports)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata containing the entry <span class="doxyComputerOutput">Count</span> for a function, a boolean \Synthetic indicating whether the counts were synthetized, and the GUIDs stored in <span class="doxyComputerOutput">Imports</span> that need to be imported for sample PGO, to enable the same inlines as the profiled optimized binary. <a href="#a208093b76ef0d541b5e0d09498be189d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82becabaf8605815a54c862c3f5eeafe">createFunctionSectionPrefix</a> (StringRef Prefix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata containing the section prefix for a function. <a href="#a82becabaf8605815a54c862c3f5eeafe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c0f85e1d2ebeeddea5c58df5fca12f7">createPseudoProbeDesc</a> (uint64_t GUID, uint64_t Hash, StringRef FName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata containing the pseudo probe descriptor for a function. <a href="#a3c0f85e1d2ebeeddea5c58df5fca12f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3d7fcf79c6f64a51803f438fad104fb">createLLVMStats</a> (ArrayRef&lt; std::pair&lt; StringRef, uint64_t &gt; &gt; LLVMStatsVec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata containing llvm statistics. <a href="#ad3d7fcf79c6f64a51803f438fad104fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6af8e6189a4d10f4a9c20daab0280b8">createRange</a> (const APInt &amp;Lo, const APInt &amp;Hi)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata describing the range [Lo, Hi). <a href="#ab6af8e6189a4d10f4a9c20daab0280b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60449e81a26e16d5dab5ae8c82188ece">createRange</a> (Constant *Lo, Constant *Hi)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata describing the range [Lo, Hi). <a href="#a60449e81a26e16d5dab5ae8c82188ece">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa81136ed319a6187cf349eb602da963a">createCallees</a> (ArrayRef&lt; Function * &gt; Callees)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata indicating the possible callees of indirect calls. <a href="#aa81136ed319a6187cf349eb602da963a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d51e11adfffd05afe252d3398f50d4e">createCallbackEncoding</a> (unsigned CalleeArgNo, ArrayRef&lt; int &gt; Arguments, bool VarArgsArePassed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata describing a callback (see <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite">llvm::AbstractCallSite</a>). <a href="#a1d51e11adfffd05afe252d3398f50d4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac71132402ff64d05b8acf6ca8a00fd92">mergeCallbackEncodings</a> (MDNode *ExistingCallbacks, MDNode *NewCB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge the new callback encoding <span class="doxyComputerOutput">NewCB</span> into <span class="doxyComputerOutput">ExistingCallbacks</span>. <a href="#ac71132402ff64d05b8acf6ca8a00fd92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc9fe7836755744b735d32c7e58901f">createRTTIPointerPrologue</a> (Constant *PrologueSig, Constant *RTTI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata feeding to the CodeGen about how to generate a function prologue for the "function" santizier. <a href="#adcc9fe7836755744b735d32c7e58901f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6022d366369fcd539dadfaefc80927db">createPCSections</a> (ArrayRef&lt; PCSection &gt; Sections)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata for PC sections. <a href="#a6022d366369fcd539dadfaefc80927db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e5caa6fb42d0d3898bb206b4a79ea81">createAnonymousTBAARoot</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata appropriate for a TBAA root node. <a href="#a7e5caa6fb42d0d3898bb206b4a79ea81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2c00c06e087680961c2e70ef16e1f8f">createAnonymousAliasScopeDomain</a> (StringRef Name=StringRef())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata appropriate for an alias scope domain node. <a href="#ae2c00c06e087680961c2e70ef16e1f8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29982864b11594aec54699f962f650ec">createAnonymousAliasScope</a> (MDNode *Domain, StringRef Name=StringRef())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata appropriate for an alias scope root node. <a href="#a29982864b11594aec54699f962f650ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67bf9051fbfa7989d8677ed3eb22fc64">createTBAARoot</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata appropriate for a TBAA root node with the given name. <a href="#a67bf9051fbfa7989d8677ed3eb22fc64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac71221e57ec4d5f3a1e409ae06b63ac">createAliasScopeDomain</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata appropriate for an alias scope domain node with the given name. <a href="#aac71221e57ec4d5f3a1e409ae06b63ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7850c6f16a34372cc279c562db8fae3">createAliasScope</a> (StringRef Name, MDNode *Domain)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata appropriate for an alias scope node with the given name. <a href="#ae7850c6f16a34372cc279c562db8fae3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61e4a8cfd0d268c67b6cc5c86861c18b">createTBAANode</a> (StringRef Name, MDNode *Parent, bool isConstant=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata for a non-root TBAA node with the given name, parent in the TBAA tree, and value for 'pointsToConstantMemory'. <a href="#a61e4a8cfd0d268c67b6cc5c86861c18b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf39f615f0eef682e349ee230cec4fbf">createTBAAStructNode</a> (ArrayRef&lt; TBAAStructField &gt; Fields)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata for a tbaa.struct node with the given struct field descriptions. <a href="#abf39f615f0eef682e349ee230cec4fbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f79697a0b629233029dab1823b23be8">createTBAAStructTypeNode</a> (StringRef Name, ArrayRef&lt; std::pair&lt; MDNode *, uint64_t &gt; &gt; Fields)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata for a TBAA struct node in the type DAG with the given name, a list of pairs (offset, field type in the type DAG). <a href="#a9f79697a0b629233029dab1823b23be8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e8c8a5d3688506df87d627259578c06">createTBAAScalarTypeNode</a> (StringRef Name, MDNode *Parent, uint64_t Offset=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata for a TBAA scalar type node with the given name, an offset and a parent in the TBAA type DAG. <a href="#a7e8c8a5d3688506df87d627259578c06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8e9e63ea1324e1c2ac905f4b9b68bd6">createTBAAStructTagNode</a> (MDNode *BaseType, MDNode *AccessType, uint64_t Offset, bool IsConstant=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata for a TBAA tag node with the given base type, access type and offset relative to the base type. <a href="#ae8e9e63ea1324e1c2ac905f4b9b68bd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecae3ba429df973662fc145e3347149b">createTBAATypeNode</a> (MDNode *Parent, uint64_t Size, Metadata *Id, ArrayRef&lt; TBAAStructField &gt; Fields=ArrayRef&lt; TBAAStructField &gt;())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata for a TBAA type node in the TBAA type DAG with the given parent type, size in bytes, type identifier and a list of fields. <a href="#aecae3ba429df973662fc145e3347149b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc11a237cde4f082d956d6c60af0113">createTBAAAccessTag</a> (MDNode *BaseType, MDNode *AccessType, uint64_t Offset, uint64_t Size, bool IsImmutable=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata for a TBAA access tag with the given base type, final access type, offset of the access relative to the base type, size of the access and flag indicating whether the accessed object can be considered immutable for the purposes of the TBAA analysis. <a href="#a0dc11a237cde4f082d956d6c60af0113">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1cfc11850432a4ab7d952d5f71ad94f">createMutableTBAAAccessTag</a> (MDNode *Tag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return mutable version of the given mutable or immutable TBAA access tag. <a href="#ad1cfc11850432a4ab7d952d5f71ad94f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fb87fc21e00d45516f625f9dd4067eb">createIrrLoopHeaderWeight</a> (uint64_t Weight)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata containing an irreducible loop header weight. <a href="#a7fb87fc21e00d45516f625f9dd4067eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d88e43189490975b0f361a491275bf4">createAnonymousAARoot</a> (StringRef Name=StringRef(), MDNode *Extra=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return metadata appropriate for a <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> root node (scope or TBAA). <a href="#a1d88e43189490975b0f361a491275bf4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21bd3782dc0cad64eed0a2aeaa26488c">Context</a></td>
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


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### PCSection {#ad2cd1bb39bb5642af61639f9e6d0aa0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MDBuilder::PCSection =  std::pair&lt;StringRef, SmallVector&lt;Constant *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A pair of PC section name with auxilliary constant data.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MDBuilder() {#ac6fc112f5890dbae8b1b8f3e90e5abbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDBuilder::MDBuilder (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; context)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createAliasScope() {#ae7850c6f16a34372cc279c562db8fae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createAliasScope (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Domain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata appropriate for an alias scope node with the given name.</p>


<p>This may be identified (uniqued) with other scopes with the same name and domain.</p>


<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="#a7939b917f71d9664707d8ec51da88418">createString</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createAliasScopeDomain() {#aac71221e57ec4d5f3a1e409ae06b63ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createAliasScopeDomain (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata appropriate for an alias scope domain node with the given name.</p>


<p>This may be identified (uniqued) with other roots with the same name.</p>


<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="#a7939b917f71d9664707d8ec51da88418">createString</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createAnonymousAliasScope() {#a29982864b11594aec54699f962f650ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::MDBuilder::createAnonymousAliasScope (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Domain, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
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

<p>Return metadata appropriate for an alias scope root node.</p>


<p>Each returned node is distinct from all other metadata and will never be identified (uniqued) with anything else.</p>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>.</p>


<p>Reference <a href="#a1d88e43189490975b0f361a491275bf4">createAnonymousAARoot</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8eade0f2933d0684681065b3960122e2">llvm::cloneNoAliasScopes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a> and <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a3afb2369af2abf8e93badf5822eca761">llvm::LoopVersioning::prepareNoAliasMetadata</a>.</p>

</div>
</div>

### createAnonymousAliasScopeDomain() {#ae2c00c06e087680961c2e70ef16e1f8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::MDBuilder::createAnonymousAliasScopeDomain (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
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

<p>Return metadata appropriate for an alias scope domain node.</p>


<p>Each returned node is distinct from all other metadata and will never be identified (uniqued) with anything else.</p>


<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>.</p>


<p>Reference <a href="#a1d88e43189490975b0f361a491275bf4">createAnonymousAARoot</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a> and <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a3afb2369af2abf8e93badf5822eca761">llvm::LoopVersioning::prepareNoAliasMetadata</a>.</p>

</div>
</div>

### createAnonymousTBAARoot() {#a7e5caa6fb42d0d3898bb206b4a79ea81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::MDBuilder::createAnonymousTBAARoot ()</td>
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

<p>Return metadata appropriate for a TBAA root node.</p>


<p>Each returned node is distinct from all other metadata and will never be identified (uniqued) with anything else.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>.</p>


<p>Reference <a href="#a1d88e43189490975b0f361a491275bf4">createAnonymousAARoot</a>.</p>

</div>
</div>

### createBranchWeights() {#a75043d12a76b84200e9ed593719dc5eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createBranchWeights (uint32_t TrueWeight, uint32_t FalseWeight, bool IsExpected=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata containing two branch weights.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TrueWeight</td>
<td class="doxyParamItemDescription"><p>the weight of the true branch</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FalseWeight</td>
<td class="doxyParamItemDescription"><p>the weight of the false branch</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Do</td>
<td class="doxyParamItemDescription"><p>these weights come from __builtin_expect*</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>Reference <a href="#a75043d12a76b84200e9ed593719dc5eb">createBranchWeights</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/switchinstprofupdatewrapper/#ab2834f787d0273fe7af2f1db987c02c9">llvm::SwitchInstProfUpdateWrapper::buildProfBranchWeightsMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp/#a7a886a9d5072d74e893ac6322b5729c2">createBranchWeights</a>, <a href="#a75043d12a76b84200e9ed593719dc5eb">createBranchWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c3ae5ad4be121cbb1bc87e871b679da">llvm::createCallMatchingInvoke</a>, <a href="#aba565f72261aa7d6207da89db949d991">createLikelyBranchWeights</a>, <a href="#ae609aeb09c2b1c9f03fb90228654b281">createUnlikelyBranchWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a6ac9067dc7c125cd83855df3e480e04c">handleBrSelExpect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#aea5dd05a61257355d99f96d8d6dc9f94">handlePhiDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a2e130f575ee6cbddeb0d62b295dee036">InsertStackProtectors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27aee52717271be9e79135bfaab890ce">llvm::makeGuardControlFlowExplicit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6cf82c052d63a1b464be8e48ff38c48e">llvm::setBranchWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a939fe4165e88bc40fb5831d3d7a42976">setBranchWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4c6e9504894d5f9468c5f151bdc75de2">setBranchWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad7cd933f586fc0c66656a4751ac069f">llvm::setLoopEstimatedTripCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a3e8ca2c20b8c4c14c72c49d98f3801ed">simplifySwitchOfCmpIntrinsic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### createBranchWeights() {#adff293fef41b4eb80fca7c47b2e2c99a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createBranchWeights (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; Weights, bool IsExpected=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata containing a number of branch weights.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Weights</td>
<td class="doxyParamItemDescription"><p>the weights of all the branches</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Do</td>
<td class="doxyParamItemDescription"><p>these weights come from __builtin_expect*</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="#a7939b917f71d9664707d8ec51da88418">createString</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### createCallbackEncoding() {#a1d51e11adfffd05afe252d3398f50d4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createCallbackEncoding (unsigned CalleeArgNo, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Arguments, bool VarArgsArePassed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata describing a callback (see <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite">llvm::AbstractCallSite</a>).</p>

<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a1161e5a4e753384aaba3a8e4533c4261">Arguments</a>, <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a3cc05cd6e06dd1976f88ed7d808ac0a1">Int1</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c">Int64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a034dc6253a2a36f78ac071a7c12d5c27">llvm::OpenMPIRBuilder::getOrCreateRuntimeFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>.</p>

</div>
</div>

### createCallees() {#aa81136ed319a6187cf349eb602da963a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createCallees (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; Callees)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata indicating the possible callees of indirect calls.</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp/#a1d2bce545ae26cccf351c2c0d35d64e4">runCVP</a>.</p>

</div>
</div>

### createConstant() {#a3c8d885c5746db440058fc8a285126b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantAsMetadata * MDBuilder::createConstant (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the given constant as metadata.</p>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/cgprofile-cpp/#a6445e21ce50f407f94bac93afebf6c66">addModuleFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a521a0263cd32258d251908a3b8ab2f78">llvm::annotateValueSite</a>, <a href="#adff293fef41b4eb80fca7c47b2e2c99a">createBranchWeights</a>, <a href="#a1d51e11adfffd05afe252d3398f50d4e">createCallbackEncoding</a>, <a href="#aa81136ed319a6187cf349eb602da963a">createCallees</a>, <a href="#a5e9594f698a6092e755b6ce7ee6905cd">createFPMath</a>, <a href="#a208093b76ef0d541b5e0d09498be189d">createFunctionEntryCount</a>, <a href="#a7fb87fc21e00d45516f625f9dd4067eb">createIrrLoopHeaderWeight</a>, <a href="#ad3d7fcf79c6f64a51803f438fad104fb">createLLVMStats</a>, <a href="#a6022d366369fcd539dadfaefc80927db">createPCSections</a>, <a href="#a3c0f85e1d2ebeeddea5c58df5fca12f7">createPseudoProbeDesc</a>, <a href="#a60449e81a26e16d5dab5ae8c82188ece">createRange</a>, <a href="#adcc9fe7836755744b735d32c7e58901f">createRTTIPointerPrologue</a>, <a href="#a0dc11a237cde4f082d956d6c60af0113">createTBAAAccessTag</a>, <a href="#a61e4a8cfd0d268c67b6cc5c86861c18b">createTBAANode</a>, <a href="#a7e8c8a5d3688506df87d627259578c06">createTBAAScalarTypeNode</a>, <a href="#abf39f615f0eef682e349ee230cec4fbf">createTBAAStructNode</a>, <a href="#ae8e9e63ea1324e1c2ac905f4b9b68bd6">createTBAAStructTagNode</a>, <a href="#a9f79697a0b629233029dab1823b23be8">createTBAAStructTypeNode</a>, <a href="#aecae3ba429df973662fc145e3347149b">createTBAATypeNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a804c9545f28631dc405eccad6d7234a7">lowerKernelArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af38c031cd1488ca8f80ada31b3df9eac">llvm::scaleProfData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3dadc94dc9df93690ba937226744797">llvm::setKCFIType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#ab10b653a914cecca232400be7a563633">translateBranchMetadata</a>.</p>

</div>
</div>

### createFPMath() {#a5e9594f698a6092e755b6ce7ee6905cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createFPMath (float Accuracy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata with the given settings.</p>


<p>The special value 0.0 for the Accuracy parameter indicates the default (maximal precision) setting.</p>


<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a>.</p>

</div>
</div>

### createFunctionEntryCount() {#a208093b76ef0d541b5e0d09498be189d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createFunctionEntryCount (uint64_t Count, bool Synthetic, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; * Imports)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata containing the entry <span class="doxyComputerOutput">Count</span> for a function, a boolean \Synthetic indicating whether the counts were synthetized, and the GUIDs stored in <span class="doxyComputerOutput">Imports</span> that need to be imported for sample PGO, to enable the same inlines as the profiled optimized binary.</p>

<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad7dc7318244359268414719e0959346e">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="#a7939b917f71d9664707d8ec51da88418">createString</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a8cd802dcaed35e1f28ea3cbe4af4eff5">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

### createFunctionSectionPrefix() {#a82becabaf8605815a54c862c3f5eeafe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createFunctionSectionPrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata containing the section prefix for a function.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="#a7939b917f71d9664707d8ec51da88418">createString</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createIrrLoopHeaderWeight() {#a7fb87fc21e00d45516f625f9dd4067eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createIrrLoopHeaderWeight (uint64_t Weight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata containing an irreducible loop header weight.</p>

<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="#a7939b917f71d9664707d8ec51da88418">createString</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a08c7dd6c9db484e7609dc95fca6cc55e">llvm::setIrrLoopHeaderMetadata</a>.</p>

</div>
</div>

### createLikelyBranchWeights() {#aba565f72261aa7d6207da89db949d991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createLikelyBranchWeights ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata containing two branch weights, with significant bias towards <span class="doxyComputerOutput">true</span> destination.</p>

<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>Reference <a href="#a75043d12a76b84200e9ed593719dc5eb">createBranchWeights</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a> and <a href="/web-llvm/docs/api/structs/anonymous-crossdsocfi-cpp-/crossdsocfi/#a1446c390b416fa0c68a832b3eb623b2d">anonymous{CrossDSOCFI.cpp}::CrossDSOCFI::runOnModule</a>.</p>

</div>
</div>

### createLLVMStats() {#ad3d7fcf79c6f64a51803f438fad104fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createLLVMStats (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, uint64_t &gt; &gt; LLVMStatsVec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata containing llvm statistics.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="#a7939b917f71d9664707d8ec51da88418">createString</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### createMutableTBAAAccessTag() {#ad1cfc11850432a4ab7d952d5f71ad94f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createMutableTBAAAccessTag (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return mutable version of the given mutable or immutable TBAA access tag.</p>

<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a0dc11a237cde4f082d956d6c60af0113">createTBAAAccessTag</a>, <a href="#ae8e9e63ea1324e1c2ac905f4b9b68bd6">createTBAAStructTagNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a2bf12026ed9de594d2117077b422c24d">stripNonValidDataFromBody</a>.</p>

</div>
</div>

### createPCSections() {#a6022d366369fcd539dadfaefc80927db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createPCSections (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#ad2cd1bb39bb5642af61639f9e6d0aa0d">PCSection</a> &gt; Sections)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata for PC sections.</p>

<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="#a7939b917f71d9664707d8ec51da88418">createString</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/machinesanitizerbinarymetadata/#a937f0d635f382c2a5befe696ddd43770">anonymous{SanitizerBinaryMetadata.cpp}::MachineSanitizerBinaryMetadata::runOnMachineFunction</a>.</p>

</div>
</div>

### createPseudoProbeDesc() {#a3c0f85e1d2ebeeddea5c58df5fca12f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createPseudoProbeDesc (uint64_t GUID, uint64_t Hash, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata containing the pseudo probe descriptor for a function.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="#a7939b917f71d9664707d8ec51da88418">createString</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprofileprober/#af77769bc44a5fe5006bbc89befd75e4b">llvm::SampleProfileProber::instrumentOneFunc</a>.</p>

</div>
</div>

### createRange() {#ab6af8e6189a4d10f4a9c20daab0280b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Lo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Hi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata describing the range [Lo, Hi).</p>

<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab6af8e6189a4d10f4a9c20daab0280b8">createRange</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp/#ada9cd9202fbb1b38f39030725baddad6">annotateGridSizeLoadWithRangeMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab057ca6ed74ccfa73d1a0d2cf15b2300">llvm::copyNonnullMetadata</a>, <a href="#ab6af8e6189a4d10f4a9c20daab0280b8">createRange</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a804c9545f28631dc405eccad6d7234a7">lowerKernelArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a553c1b079d8168cdff5b62f756fccf93">llvm::AMDGPUSubtarget::makeLIDRangeMetadata</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#afd9e63b8a22ad3b90efbd3e5bd8b1b93">anonymous{AMDGPUSwLowerLDS.cpp}::recordLDSAbsoluteAddress</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a9d9ad1173db1cee0c288f1b773baaf65">upgradeAMDGCNIntrinsicCall</a>.</p>

</div>
</div>

### createRange() {#a60449e81a26e16d5dab5ae8c82188ece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createRange (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Lo, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Hi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata describing the range [Lo, Hi).</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>

</div>
</div>

### createRTTIPointerPrologue() {#adcc9fe7836755744b735d32c7e58901f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createRTTIPointerPrologue (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PrologueSig, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * RTTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata feeding to the CodeGen about how to generate a function prologue for the "function" santizier.</p>

<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createString() {#a7939b917f71d9664707d8ec51da88418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString * MDBuilder::createString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the given string as metadata.</p>

<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9a7c63edb94ce4fab2a5bb34dbf6079a">llvm::Instruction::addAnnotationMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6762e9e611c29b13a5c94bf8488fe798">llvm::Instruction::addAnnotationMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a1765b2301f26e0db70d0ba12b3a0e15a">annotateFunctionWithHashMismatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a521a0263cd32258d251908a3b8ab2f78">llvm::annotateValueSite</a>, <a href="#ae7850c6f16a34372cc279c562db8fae3">createAliasScope</a>, <a href="#aac71221e57ec4d5f3a1e409ae06b63ac">createAliasScopeDomain</a>, <a href="#a1d88e43189490975b0f361a491275bf4">createAnonymousAARoot</a>, <a href="#adff293fef41b4eb80fca7c47b2e2c99a">createBranchWeights</a>, <a href="#a208093b76ef0d541b5e0d09498be189d">createFunctionEntryCount</a>, <a href="#a82becabaf8605815a54c862c3f5eeafe">createFunctionSectionPrefix</a>, <a href="#a7fb87fc21e00d45516f625f9dd4067eb">createIrrLoopHeaderWeight</a>, <a href="#ad3d7fcf79c6f64a51803f438fad104fb">createLLVMStats</a>, <a href="#a6022d366369fcd539dadfaefc80927db">createPCSections</a>, <a href="#a3c0f85e1d2ebeeddea5c58df5fca12f7">createPseudoProbeDesc</a>, <a href="#a61e4a8cfd0d268c67b6cc5c86861c18b">createTBAANode</a>, <a href="#a67bf9051fbfa7989d8677ed3eb22fc64">createTBAARoot</a>, <a href="#a7e8c8a5d3688506df87d627259578c06">createTBAAScalarTypeNode</a>, <a href="#a9f79697a0b629233029dab1823b23be8">createTBAAStructTypeNode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#ab10b653a914cecca232400be7a563633">translateBranchMetadata</a>.</p>

</div>
</div>

### createTBAAAccessTag() {#a0dc11a237cde4f082d956d6c60af0113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createTBAAAccessTag (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * BaseType, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * AccessType, uint64_t Offset, uint64_t Size, bool IsImmutable=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata for a TBAA access tag with the given base type, final access type, offset of the access relative to the base type, size of the access and flag indicating whether the accessed object can be considered immutable for the purposes of the TBAA analysis.</p>

<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c">Int64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#ad1cfc11850432a4ab7d952d5f71ad94f">createMutableTBAAAccessTag</a>.</p>

</div>
</div>

### createTBAANode() {#a61e4a8cfd0d268c67b6cc5c86861c18b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createTBAANode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Parent, bool isConstant=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata for a non-root TBAA node with the given name, parent in the TBAA tree, and value for 'pointsToConstantMemory'.</p>

<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="#a7939b917f71d9664707d8ec51da88418">createString</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a6dee2d9e1e2a288de903228075ac71de">isConstant</a>.</p>

</div>
</div>

### createTBAARoot() {#a67bf9051fbfa7989d8677ed3eb22fc64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createTBAARoot (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata appropriate for a TBAA root node with the given name.</p>


<p>This may be identified (uniqued) with other roots with the same name.</p>


<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="#a7939b917f71d9664707d8ec51da88418">createString</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### createTBAAScalarTypeNode() {#a7e8c8a5d3688506df87d627259578c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createTBAAScalarTypeNode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Parent, uint64_t Offset=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata for a TBAA scalar type node with the given name, an offset and a parent in the TBAA type DAG.</p>

<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="#a7939b917f71d9664707d8ec51da88418">createString</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### createTBAAStructNode() {#abf39f615f0eef682e349ee230cec4fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createTBAAStructNode (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mdbuilder/tbaastructfield">TBAAStructField</a> &gt; Fields)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata for a tbaa.struct node with the given struct field descriptions.</p>

<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c">Int64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### createTBAAStructTagNode() {#ae8e9e63ea1324e1c2ac905f4b9b68bd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createTBAAStructTagNode (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * BaseType, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * AccessType, uint64_t Offset, bool IsConstant=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata for a TBAA tag node with the given base type, access type and offset relative to the base type.</p>

<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c">Int64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#ad1cfc11850432a4ab7d952d5f71ad94f">createMutableTBAAAccessTag</a>.</p>

</div>
</div>

### createTBAAStructTypeNode() {#a9f79697a0b629233029dab1823b23be8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createTBAAStructTypeNode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, uint64_t &gt; &gt; Fields)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata for a TBAA struct node in the type DAG with the given name, a list of pairs (offset, field type in the type DAG).</p>

<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="#a7939b917f71d9664707d8ec51da88418">createString</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c">Int64</a>.</p>

</div>
</div>

### createTBAATypeNode() {#aecae3ba429df973662fc145e3347149b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createTBAATypeNode (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Parent, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Id, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mdbuilder/tbaastructfield">TBAAStructField</a> &gt; Fields=<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mdbuilder/tbaastructfield">TBAAStructField</a> &gt;())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata for a TBAA type node in the TBAA type DAG with the given parent type, size in bytes, type identifier and a list of fields.</p>

<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a3c8d885c5746db440058fc8a285126b2">createConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c">Int64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### createUnlikelyBranchWeights() {#ae609aeb09c2b1c9f03fb90228654b281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createUnlikelyBranchWeights ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata containing two branch weights, with significant bias towards <span class="doxyComputerOutput">false</span> destination.</p>

<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>Reference <a href="#a75043d12a76b84200e9ed593719dc5eb">createBranchWeights</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#af54e01fb7fd5db7ff76495fcabc90ea1">anonymous{AddressSanitizer.cpp}::AddressSanitizer::genAMDGPUReportBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7bccc5bea4b7b3b3fe9387570f2fabd5">llvm::AMDGPU::genAMDGPUReportBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a9b79beccbeb33ff89c797f5ac7b3fce3">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/kcfipass/#a19dcb564cb3c8a4de327c6f9cabed5b3">llvm::KCFIPass::run</a>.</p>

</div>
</div>

### createUnpredictable() {#a8cea521fb45003a63caeb04f2b13ec0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createUnpredictable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata specifying that a branch or switch is unpredictable.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>

</div>
</div>

### mergeCallbackEncodings() {#ac71132402ff64d05b8acf6ca8a00fd92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::mergeCallbackEncodings (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * ExistingCallbacks, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * NewCB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge the new callback encoding <span class="doxyComputerOutput">NewCB</span> into <span class="doxyComputerOutput">ExistingCallbacks</span>.</p>

<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### createAnonymousAARoot() {#a1d88e43189490975b0f361a491275bf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDBuilder::createAnonymousAARoot (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(), <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Extra=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return metadata appropriate for a <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> root node (scope or TBAA).</p>


<p>Each returned node is distinct from all other metadata and will never be identified (uniqued) with anything else.</p>


<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a>.</p>


<p>References <a href="#a7939b917f71d9664707d8ec51da88418">createString</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a21a975fd58c287a6ca3f1c89c048e7d3">llvm::MDNode::getDistinct</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a>.</p>


<p>Referenced by <a href="#a29982864b11594aec54699f962f650ec">createAnonymousAliasScope</a>, <a href="#ae2c00c06e087680961c2e70ef16e1f8f">createAnonymousAliasScopeDomain</a> and <a href="#a7e5caa6fb42d0d3898bb206b4a79ea81">createAnonymousTBAARoot</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Context {#a21bd3782dc0cad64eed0a2aeaa26488c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; llvm::MDBuilder::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">MDBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/mdbuilder-cpp">MDBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
