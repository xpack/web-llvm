---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `X86InterleavedAccess.cpp` File Reference

<p>This file contains the <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> implementation of the interleaved accesses optimization generating X86-specific instructions/intrinsics for interleaved access groups. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86subtarget-h">X86Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">llvm/Analysis/VectorUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/machinevaluetype-h">llvm/CodeGenTypes/MachineValueType.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cmath&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86interleavedaccess-cpp-">anonymous{X86InterleavedAccess.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86interleavedaccess-cpp-/x86interleavedaccessgroup">X86InterleavedAccessGroup</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class holds necessary information to represent an interleaved access group and supports utilities to lower the group into X86-specific instructions/intrinsics. <a href="/web-llvm/docs/api/classes/anonymous-x86interleavedaccess-cpp-/x86interleavedaccessgroup/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bc9bd66618581850aca0d4ac86e6281">scaleVectorType</a> (MVT VT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49570d8463bc060cddd7b65335685002">genShuffleBland</a> (MVT VT, ArrayRef&lt; int &gt; Mask, SmallVectorImpl&lt; int &gt; &amp;Out, int LowOffset, int HighOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaf0abeac6c9f6e4698dd90c080611fa">reorderSubVector</a> (MVT VT, SmallVectorImpl&lt; Value * &gt; &amp;TransposedMatrix, ArrayRef&lt; Value * &gt; Vec, ArrayRef&lt; int &gt; VPShuf, unsigned VecElems, unsigned Stride, IRBuilder&lt;&gt; &amp;Builder)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf385bdb1a42f2648e94d92fbe51a9df">createShuffleStride</a> (MVT VT, int Stride, SmallVectorImpl&lt; int &gt; &amp;Mask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcbb3fbae2a0dfe66454040a45525a95">setGroupSize</a> (MVT VT, SmallVectorImpl&lt; int &gt; &amp;SizeInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0283fbbacd7e1b520ab58b9b867b1c71">DecodePALIGNRMask</a> (MVT VT, unsigned Imm, SmallVectorImpl&lt; int &gt; &amp;ShuffleMask, bool AlignDirection=true, bool Unary=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6fab051afe7926d360bac2cd1e82819">concatSubVector</a> (Value **Vec, ArrayRef&lt; Instruction * &gt; InVec, unsigned VecElems, IRBuilder&lt;&gt; &amp;Builder)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6c5507fc91d0ca19adbac9927262086">group2Shuffle</a> (MVT VT, SmallVectorImpl&lt; int &gt; &amp;Mask, SmallVectorImpl&lt; int &gt; &amp;Output)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76c9562101f54d25482f88ae29ed6131">Concat</a>[] = ...</td>
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

<p>This file contains the <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> implementation of the interleaved accesses optimization generating X86-specific instructions/intrinsics for interleaved access groups.</p>

<div class="doxySectionDef">

## Functions

### concatSubVector() {#ad6fab051afe7926d360bac2cd1e82819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void concatSubVector (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ** Vec, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; InVec, unsigned VecElems, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="#a76c9562101f54d25482f88ae29ed6131">Concat</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>.</p>

</div>
</div>

### createShuffleStride() {#abf385bdb1a42f2648e94d92fbe51a9df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createShuffleStride (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, int Stride, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Mask)</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a>.</p>

</div>
</div>

### DecodePALIGNRMask() {#a0283fbbacd7e1b520ab58b9b867b1c71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DecodePALIGNRMask (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, unsigned Imm, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; ShuffleMask, bool AlignDirection=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool Unary=false)</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### genShuffleBland() {#a49570d8463bc060cddd7b65335685002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void genShuffleBland (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Out, int LowOffset, int HighOffset)</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#aeaf0abeac6c9f6e4698dd90c080611fa">reorderSubVector</a>.</p>

</div>
</div>

### group2Shuffle() {#ab6c5507fc91d0ca19adbac9927262086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void group2Shuffle (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Mask, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Output)</td>
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



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### reorderSubVector() {#aeaf0abeac6c9f6e4698dd90c080611fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reorderSubVector (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; TransposedMatrix, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Vec, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; VPShuf, unsigned VecElems, unsigned Stride, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#a76c9562101f54d25482f88ae29ed6131">Concat</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a> and <a href="#a49570d8463bc060cddd7b65335685002">genShuffleBland</a>.</p>

</div>
</div>

### scaleVectorType() {#a5bc9bd66618581850aca0d4ac86e6281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT scaleVectorType (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>.</p>

</div>
</div>

### setGroupSize() {#adcbb3fbae2a0dfe66454040a45525a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setGroupSize (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; SizeInfo)</td>
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



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Concat {#a76c9562101f54d25482f88ae29ed6131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Concat[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    0,  1,  2,  3,  4,  5,  6,  7,  8,  9,  10, 11, 12, 13, 14, 15,
    16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31,
    32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47,
    48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63}
</div>
</dd>
</dl>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5e2ad1fd4e6db82aeeb143564ecca7fd">AddCombineVUZPToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa701b28d5848c3250994e2e03a2dab97">combineScalarAndWithMaskSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a364872c4ff0debf2cd93e9694b261b07">combineShuffleOfConcatUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a3eb03bef656ad82043fbb7742038dba2">ConcatStringInits</a>, <a href="#ad6fab051afe7926d360bac2cd1e82819">concatSubVector</a>, <a href="/web-llvm/docs/api/structs/tomp/type/definedoperatort/#ad583f1fe80f85a5c8af3b609214c5b1a">tomp::type::DefinedOperatorT&lt; I, E &gt;::ENUM</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad6bb7ee72f79badd15b563bf112de6e5">performBuildVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae1413a27963c6b3bb1f370867e16b61e">performUADDVZextCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8bdc70b2f7ce13fccad6913d54322dcf">performUzpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a8a9e8cccbe98907e9c282728ab9ea7c0">performVectorTruncZeroCombine</a>, <a href="#aeaf0abeac6c9f6e4698dd90c080611fa">reorderSubVector</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
