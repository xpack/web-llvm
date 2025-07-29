---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AArch64ExpandImm.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64-h">AArch64.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-h">AArch64ExpandImm.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">MCTargetDesc/AArch64AddressingModes.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5bbae3632b4bfe0de4faea7a4da829f">getChunk</a> (uint64_t Imm, unsigned ChunkIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function which extracts the specified 16-bit chunk from a 64-bit value. <a href="#aa5bbae3632b4bfe0de4faea7a4da829f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a436cd44154cf245c297b6b5a5fac9a84">canUseOrr</a> (uint64_t Chunk, uint64_t &amp;Encoding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given 16-bit chunk replicated to full 64-bit width can be materialized with an ORR instruction. <a href="#a436cd44154cf245c297b6b5a5fac9a84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6efd5b30fe34a042d2937ba63a73ad07">tryToreplicateChunks</a> (uint64_t UImm, SmallVectorImpl&lt; ImmInsnModel &gt; &amp;Insn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for identical 16-bit chunks within the constant and if so materialize them with a single ORR instruction. <a href="#a6efd5b30fe34a042d2937ba63a73ad07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad84ff3d34cc228b799e8bc2f070fc4ab">isStartChunk</a> (uint64_t Chunk)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this chunk matches the pattern '1...0...'. <a href="#ad84ff3d34cc228b799e8bc2f070fc4ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add895e8580b9acacceb10b92edcd4d37">isEndChunk</a> (uint64_t Chunk)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this chunk matches the pattern '0...1...' This pattern ends a contiguous sequence of ones if we look at the bits from the LSB towards the MSB. <a href="#add895e8580b9acacceb10b92edcd4d37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4323e3fa0f558ea22393bc68e9520b27">updateImm</a> (uint64_t Imm, unsigned Idx, bool Clear)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear or set all bits in the chunk at the given index. <a href="#a4323e3fa0f558ea22393bc68e9520b27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7000ac817f63a64697020f0538311927">trySequenceOfOnes</a> (uint64_t UImm, SmallVectorImpl&lt; ImmInsnModel &gt; &amp;Insn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the constant contains a sequence of contiguous ones, which might be interrupted by one or two chunks. <a href="#a7000ac817f63a64697020f0538311927">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e2936fed450c145238eeca56cf4572e">GetRunOfOnesStartingAt</a> (uint64_t V, uint64_t StartPosition)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78822aec5f2ccbac50c2b2ac068dc7d7">MaximallyReplicateSubImmediate</a> (uint64_t V, uint64_t Subset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad62d9bcb5891de134deb4465831a762b">maximalLogicalImmWithin</a> (uint64_t RemainingBits, uint64_t OriginalBits)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; std::pair&lt; uint64_t, uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb71b2a77bd02c4e0e01aecf2d392452">decomposeIntoOrrOfLogicalImmediates</a> (uint64_t UImm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae492dde0ae62ef0c16a80f8b648bae19">tryOrrOfLogicalImmediates</a> (uint64_t UImm, SmallVectorImpl&lt; ImmInsnModel &gt; &amp;Insn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa20f3eb24c28efa9c93053a733a172c1">tryAndOfLogicalImmediates</a> (uint64_t UImm, SmallVectorImpl&lt; ImmInsnModel &gt; &amp;Insn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2f723b31c9dbe46610248a047805046">tryEorOfLogicalImmediates</a> (uint64_t Imm, SmallVectorImpl&lt; ImmInsnModel &gt; &amp;Insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2edf9e8f09bfb0cc4949aa1813872322">expandMOVImmSimple</a> (uint64_t Imm, unsigned BitSize, unsigned OneChunks, unsigned ZeroChunks, SmallVectorImpl&lt; ImmInsnModel &gt; &amp;Insn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand a MOVi32imm or MOVi64imm pseudo instruction to a MOVZ or MOVN of width BitSize followed by up to 3 MOVK instructions. <a href="#a2edf9e8f09bfb0cc4949aa1813872322">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### canUseOrr() {#a436cd44154cf245c297b6b5a5fac9a84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canUseOrr (uint64_t Chunk, uint64_t &amp; Encoding)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given 16-bit chunk replicated to full 64-bit width can be materialized with an ORR instruction.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a2cd3e23b97b495a98c0b723ab18e4d96">llvm::AArch64_AM::processLogicalImmediate</a>.</p>


<p>Referenced by <a href="#a6efd5b30fe34a042d2937ba63a73ad07">tryToreplicateChunks</a>.</p>

</div>
</div>

### decomposeIntoOrrOfLogicalImmediates() {#aeb71b2a77bd02c4e0e01aecf2d392452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; uint64_t, uint64_t &gt; &gt; decomposeIntoOrrOfLogicalImmediates (uint64_t UImm)</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a239abca11deebf2731206dd41cf43c0e">llvm::countr_one</a>, <a href="#ad62d9bcb5891de134deb4465831a762b">maximalLogicalImmWithin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef2599d8a5a682c348b25f74051cdb2d">llvm::rotl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="#aa20f3eb24c28efa9c93053a733a172c1">tryAndOfLogicalImmediates</a> and <a href="#ae492dde0ae62ef0c16a80f8b648bae19">tryOrrOfLogicalImmediates</a>.</p>

</div>
</div>

### expandMOVImmSimple() {#a2edf9e8f09bfb0cc4949aa1813872322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void expandMOVImmSimple (uint64_t Imm, unsigned BitSize, unsigned OneChunks, unsigned ZeroChunks, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aarch64-imm/imminsnmodel">ImmInsnModel</a> &gt; &amp; Insn)</td>
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

<p>Expand a MOVi32imm or MOVi64imm pseudo instruction to a MOVZ or MOVN of width BitSize followed by up to 3 MOVK instructions.</p>

<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#aeae88f12b667477f90db9b726556b337">llvm::AArch64_AM::getShifterImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp/#a2762113571c7956c9818c452b2d256ae">isNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>.</p>

</div>
</div>

### getChunk() {#aa5bbae3632b4bfe0de4faea7a4da829f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getChunk (uint64_t Imm, unsigned ChunkIdx)</td>
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

<p>Helper function which extracts the specified 16-bit chunk from a 64-bit value.</p>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>, <a href="#a7000ac817f63a64697020f0538311927">trySequenceOfOnes</a> and <a href="#a6efd5b30fe34a042d2937ba63a73ad07">tryToreplicateChunks</a>.</p>

</div>
</div>

### GetRunOfOnesStartingAt() {#a2e2936fed450c145238eeca56cf4572e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t GetRunOfOnesStartingAt (uint64_t V, uint64_t StartPosition)</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a239abca11deebf2731206dd41cf43c0e">llvm::countr_one</a>.</p>


<p>Referenced by <a href="#ad62d9bcb5891de134deb4465831a762b">maximalLogicalImmWithin</a>.</p>

</div>
</div>

### isEndChunk() {#add895e8580b9acacceb10b92edcd4d37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isEndChunk (uint64_t Chunk)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this chunk matches the pattern '0...1...' This pattern ends a contiguous sequence of ones if we look at the bits from the LSB towards the MSB.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a82a9558b6319303ae62f59dab9669685">llvm::isMask_64</a>.</p>


<p>Referenced by <a href="#a7000ac817f63a64697020f0538311927">trySequenceOfOnes</a>.</p>

</div>
</div>

### isStartChunk() {#ad84ff3d34cc228b799e8bc2f070fc4ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isStartChunk (uint64_t Chunk)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this chunk matches the pattern '1...0...'.</p>


<p>This pattern starts a contiguous sequence of ones if we look at the bits from the LSB towards the MSB.</p>


<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a82a9558b6319303ae62f59dab9669685">llvm::isMask_64</a>.</p>


<p>Referenced by <a href="#a7000ac817f63a64697020f0538311927">trySequenceOfOnes</a>.</p>

</div>
</div>

### maximalLogicalImmWithin() {#ad62d9bcb5891de134deb4465831a762b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t maximalLogicalImmWithin (uint64_t RemainingBits, uint64_t OriginalBits)</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="#a2e2936fed450c145238eeca56cf4572e">GetRunOfOnesStartingAt</a> and <a href="#a78822aec5f2ccbac50c2b2ac068dc7d7">MaximallyReplicateSubImmediate</a>.</p>


<p>Referenced by <a href="#aeb71b2a77bd02c4e0e01aecf2d392452">decomposeIntoOrrOfLogicalImmediates</a>.</p>

</div>
</div>

### MaximallyReplicateSubImmediate() {#a78822aec5f2ccbac50c2b2ac068dc7d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MaximallyReplicateSubImmediate (uint64_t V, uint64_t Subset)</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aef2599d8a5a682c348b25f74051cdb2d">llvm::rotl</a>.</p>


<p>Referenced by <a href="#ad62d9bcb5891de134deb4465831a762b">maximalLogicalImmWithin</a>.</p>

</div>
</div>

### tryAndOfLogicalImmediates() {#aa20f3eb24c28efa9c93053a733a172c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryAndOfLogicalImmediates (uint64_t UImm, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aarch64-imm/imminsnmodel">ImmInsnModel</a> &gt; &amp; Insn)</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>References <a href="#aeb71b2a77bd02c4e0e01aecf2d392452">decomposeIntoOrrOfLogicalImmediates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a2cd3e23b97b495a98c0b723ab18e4d96">llvm::AArch64_AM::processLogicalImmediate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>.</p>

</div>
</div>

### tryEorOfLogicalImmediates() {#ab2f723b31c9dbe46610248a047805046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryEorOfLogicalImmediates (uint64_t Imm, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aarch64-imm/imminsnmodel">ImmInsnModel</a> &gt; &amp; Insn)</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a239abca11deebf2731206dd41cf43c0e">llvm::countr_one</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a2cd3e23b97b495a98c0b723ab18e4d96">llvm::AArch64_AM::processLogicalImmediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef2599d8a5a682c348b25f74051cdb2d">llvm::rotl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>.</p>

</div>
</div>

### tryOrrOfLogicalImmediates() {#ae492dde0ae62ef0c16a80f8b648bae19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryOrrOfLogicalImmediates (uint64_t UImm, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aarch64-imm/imminsnmodel">ImmInsnModel</a> &gt; &amp; Insn)</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>References <a href="#aeb71b2a77bd02c4e0e01aecf2d392452">decomposeIntoOrrOfLogicalImmediates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a2cd3e23b97b495a98c0b723ab18e4d96">llvm::AArch64_AM::processLogicalImmediate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>.</p>

</div>
</div>

### trySequenceOfOnes() {#a7000ac817f63a64697020f0538311927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool trySequenceOfOnes (uint64_t UImm, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aarch64-imm/imminsnmodel">ImmInsnModel</a> &gt; &amp; Insn)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the constant contains a sequence of contiguous ones, which might be interrupted by one or two chunks.</p>


<p>If so, materialize the sequence of contiguous ones with an ORR instruction. Materialize the chunks which are either interrupting the sequence or outside of the sequence with a MOVK instruction.</p>


<p>Assuming S is a chunk which starts the sequence (1...0...), E is a chunk which ends the sequence (0...1...). Then we are looking for constants which contain at least one S and E chunk. E.g. |E|A|B|S|, |A|E|B|S| or |A|B|E|S|.</p>


<p>We are also looking for constants like |S|A|B|E| where the contiguous sequence of ones wraps around the MSB into the LSB.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa5bbae3632b4bfe0de4faea7a4da829f">getChunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#aeae88f12b667477f90db9b726556b337">llvm::AArch64_AM::getShifterImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="#add895e8580b9acacceb10b92edcd4d37">isEndChunk</a>, <a href="#ad84ff3d34cc228b799e8bc2f070fc4ab">isStartChunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a2cd3e23b97b495a98c0b723ab18e4d96">llvm::AArch64_AM::processLogicalImmediate</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="#a4323e3fa0f558ea22393bc68e9520b27">updateImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>.</p>

</div>
</div>

### tryToreplicateChunks() {#a6efd5b30fe34a042d2937ba63a73ad07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryToreplicateChunks (uint64_t UImm, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aarch64-imm/imminsnmodel">ImmInsnModel</a> &gt; &amp; Insn)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for identical 16-bit chunks within the constant and if so materialize them with a single ORR instruction.</p>


<p>The remaining one or two 16-bit chunks will be materialized with MOVK instructions.</p>


<p>This allows us to materialize constants like |A|B|A|A| or |A|B|C|A| (order of the chunks doesn't matter), assuming |A|A|A|A| can be materialized with an ORR instruction.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>References <a href="#a436cd44154cf245c297b6b5a5fac9a84">canUseOrr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#aa5bbae3632b4bfe0de4faea7a4da829f">getChunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#aeae88f12b667477f90db9b726556b337">llvm::AArch64_AM::getShifterImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>.</p>

</div>
</div>

### updateImm() {#a4323e3fa0f558ea22393bc68e9520b27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t updateImm (uint64_t Imm, unsigned Idx, bool Clear)</td>
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

<p>Clear or set all bits in the chunk at the given index.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>Referenced by <a href="#a7000ac817f63a64697020f0538311927">trySequenceOfOnes</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
