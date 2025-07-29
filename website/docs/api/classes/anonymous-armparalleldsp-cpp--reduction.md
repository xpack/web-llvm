---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-armparalleldsp-cpp-/reduction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Reduction` Class

<p>Represent a sequence of multiply-accumulate operations with the aim to perform the multiplications in parallel. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{ARMParallelDSP.cpp}::Reduction { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa38eaf5bcfbccb38cf33579a2c94a8c3">Reduction</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a330ba1dd3d26f93f62888bad0065bd60">Reduction</a> (Instruction *Add)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a9069d31fa9683ab1bf124732cb41c">InsertAdd</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> an Add instruction that is a part of the this reduction. <a href="#a28a9069d31fa9683ab1bf124732cb41c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad59edfa37452cad2bf11eb014636101">InsertMuls</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create MulCandidates, each rooted at a Mul instruction, that is a part of this reduction. <a href="#aad59edfa37452cad2bf11eb014636101">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae339cfdd04f4c821c4757a725d4745bf">InsertAcc</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the incoming accumulator value, returns true if a value had not already been added. <a href="#ae339cfdd04f4c821c4757a725d4745bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a181a6bac261671ae24b57cf17edc2675">AddMulPair</a> (MulCandidate *Mul0, MulCandidate *Mul1, bool Exchange=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set two MulCandidates, rooted at muls, that can be executed as a single parallel operation. <a href="#a181a6bac261671ae24b57cf17edc2675">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa63815fc1e72aa45c0a83477f6709dbd">getRoot</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the add instruction which is the root of the reduction. <a href="#aa63815fc1e72aa45c0a83477f6709dbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10213187fe76af63064e55c4dd46de17">is64Bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3566f1d7d16e60e47108a040a08eb5a3">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c53f521d43ae7e7b62c9ce981a4b4b">getAccumulator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the incoming value to be accumulated. This maybe null. <a href="#a97c53f521d43ae7e7b62c9ce981a4b4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a4bcdcd3a57a30ea39976fd2fd45397">getAdds</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the set of adds that comprise the reduction. <a href="#a1a4bcdcd3a57a30ea39976fd2fd45397">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-armparalleldsp-cpp-/#ae1544a61df14546cc597d881b864f803">MulCandList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac32bec869156eb9c2683b0fef5c1a1f1">getMuls</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/structs/anonymous-armparalleldsp-cpp-/mulcandidate">MulCandidate</a>, rooted at mul instruction, that comprise the the reduction. <a href="#ac32bec869156eb9c2683b0fef5c1a1f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-armparalleldsp-cpp-/#a98103abb8a3581315f0b2992da1ea0d7">MulPairList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae699deedcf16c4fc944777f38af0e0ac">getMulPairs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/structs/anonymous-armparalleldsp-cpp-/mulcandidate">MulCandidate</a>, rooted at mul instructions, that have been paired for parallel execution. <a href="#ae699deedcf16c4fc944777f38af0e0ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acea432c683bbb6745045a5fd0fe3b4b6">UpdateRoot</a> (Instruction *SMLAD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To finalise, replace the uses of the root with the intrinsic call. <a href="#acea432c683bbb6745045a5fd0fe3b4b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc2c8cd2ffff02bf73074d539edf966">dump</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfbfec8a9f3fa69a99da7678afc21b67">Root</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42c25ba6a595c316f90dc1ab6d1f9bde">Acc</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-armparalleldsp-cpp-/#ae1544a61df14546cc597d881b864f803">MulCandList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f6703c09462ccee3d3f034e324cf6f4">Muls</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-armparalleldsp-cpp-/#a98103abb8a3581315f0b2992da1ea0d7">MulPairList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed7f49aede3bba0e15c8e19bf2a16794">MulPairs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f55212accb50f36c3258ff68c23eb14">Adds</a></td>
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

<p>Represent a sequence of multiply-accumulate operations with the aim to perform the multiplications in parallel.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Reduction() {#aa38eaf5bcfbccb38cf33579a2c94a8c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMParallelDSP.cpp}::Reduction::Reduction ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### Reduction() {#a330ba1dd3d26f93f62888bad0065bd60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMParallelDSP.cpp}::Reduction::Reduction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Add)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddMulPair() {#a181a6bac261671ae24b57cf17edc2675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMParallelDSP.cpp}::Reduction::AddMulPair (<a href="/web-llvm/docs/api/structs/anonymous-armparalleldsp-cpp-/mulcandidate">MulCandidate</a> * Mul0, <a href="/web-llvm/docs/api/structs/anonymous-armparalleldsp-cpp-/mulcandidate">MulCandidate</a> * Mul1, bool Exchange=false)</td>
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

<p>Set two MulCandidates, rooted at muls, that can be executed as a single parallel operation.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/anonymous-armparalleldsp-cpp-/mulcandidate/#a515a4fd469e9f71db959022a73045b41">anonymous{ARMParallelDSP.cpp}::MulCandidate::Exchange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/anonymous-armparalleldsp-cpp-/mulcandidate/#a511d678a00adf3d0aff731991a4f38ba">anonymous{ARMParallelDSP.cpp}::MulCandidate::Paired</a> and <a href="/web-llvm/docs/api/structs/anonymous-armparalleldsp-cpp-/mulcandidate/#ab3579457c0ec0bb5e59f5e902da6034c">anonymous{ARMParallelDSP.cpp}::MulCandidate::Root</a>.</p>

</div>
</div>

### dump() {#aebc2c8cd2ffff02bf73074d539edf966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMParallelDSP.cpp}::Reduction::dump ()</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#ae0f503db91504a3f3440ab81260e4134">Mul</a>.</p>

</div>
</div>

### getAccumulator() {#a97c53f521d43ae7e7b62c9ce981a4b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{ARMParallelDSP.cpp}::Reduction::getAccumulator ()</td>
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

<p>Return the incoming value to be accumulated. This maybe null.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### getAdds() {#a1a4bcdcd3a57a30ea39976fd2fd45397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt; Instruction * &gt; &amp; anonymous{ARMParallelDSP.cpp}::Reduction::getAdds ()</td>
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

<p>Return the set of adds that comprise the reduction.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### getMulPairs() {#ae699deedcf16c4fc944777f38af0e0ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MulPairList &amp; anonymous{ARMParallelDSP.cpp}::Reduction::getMulPairs ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/structs/anonymous-armparalleldsp-cpp-/mulcandidate">MulCandidate</a>, rooted at mul instructions, that have been paired for parallel execution.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### getMuls() {#ac32bec869156eb9c2683b0fef5c1a1f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MulCandList &amp; anonymous{ARMParallelDSP.cpp}::Reduction::getMuls ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/structs/anonymous-armparalleldsp-cpp-/mulcandidate">MulCandidate</a>, rooted at mul instruction, that comprise the the reduction.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### getRoot() {#aa63815fc1e72aa45c0a83477f6709dbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * anonymous{ARMParallelDSP.cpp}::Reduction::getRoot ()</td>
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

<p>Return the add instruction which is the root of the reduction.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### getType() {#a3566f1d7d16e60e47108a040a08eb5a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{ARMParallelDSP.cpp}::Reduction::getType ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### InsertAcc() {#ae339cfdd04f4c821c4757a725d4745bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMParallelDSP.cpp}::Reduction::InsertAcc (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Add the incoming accumulator value, returns true if a value had not already been added.</p>


<p>Returning false signals to the user that this reduction already has a value to initialise the accumulator.</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### InsertAdd() {#a28a9069d31fa9683ab1bf124732cb41c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMParallelDSP.cpp}::Reduction::InsertAdd (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> an Add instruction that is a part of the this reduction.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### InsertMuls() {#aad59edfa37452cad2bf11eb014636101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMParallelDSP.cpp}::Reduction::InsertMuls ()</td>
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

<p>Create MulCandidates, each rooted at a Mul instruction, that is a part of this reduction.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#ae0f503db91504a3f3440ab81260e4134">Mul</a>.</p>

</div>
</div>

### is64Bit() {#a10213187fe76af63064e55c4dd46de17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMParallelDSP.cpp}::Reduction::is64Bit ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### UpdateRoot() {#acea432c683bbb6745045a5fd0fe3b4b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMParallelDSP.cpp}::Reduction::UpdateRoot (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * SMLAD)</td>
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

<p>To finalise, replace the uses of the root with the intrinsic call.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Acc {#a42c25ba6a595c316f90dc1ab6d1f9bde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{ARMParallelDSP.cpp}::Reduction::Acc = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### Adds {#a7f55212accb50f36c3258ff68c23eb14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;Instruction*&gt; anonymous{ARMParallelDSP.cpp}::Reduction::Adds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### MulPairs {#aed7f49aede3bba0e15c8e19bf2a16794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MulPairList anonymous{ARMParallelDSP.cpp}::Reduction::MulPairs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### Muls {#a1f6703c09462ccee3d3f034e324cf6f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MulCandList anonymous{ARMParallelDSP.cpp}::Reduction::Muls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### Root {#acfbfec8a9f3fa69a99da7678afc21b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{ARMParallelDSP.cpp}::Reduction::Root = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
