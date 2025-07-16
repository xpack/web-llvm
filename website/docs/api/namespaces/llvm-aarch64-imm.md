---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/aarch64-imm
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `AArch64_IMM` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::AArch64_IMM { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aarch64-imm/imminsnmodel">ImmInsnModel</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a4e6615fbc6c2bbcf179370dbd0fa9">expandMOVImm</a> (uint64_t Imm, unsigned BitSize, SmallVectorImpl&lt; ImmInsnModel &gt; &amp;Insn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand a MOVi32imm or MOVi64imm pseudo instruction to one or more real move-immediate instructions to synthesize the immediate. <a href="#a77a4e6615fbc6c2bbcf179370dbd0fa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### expandMOVImm() {#a77a4e6615fbc6c2bbcf179370dbd0fa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64_IMM::expandMOVImm (uint64_t Imm, unsigned BitSize, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aarch64-imm/imminsnmodel">ImmInsnModel</a> &gt; &amp; Insn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand a MOVi32imm or MOVi64imm pseudo instruction to one or more real move-immediate instructions to synthesize the immediate.</p>

<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-h">AArch64ExpandImm.h</a>, definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#a2edf9e8f09bfb0cc4949aa1813872322">expandMOVImmSimple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#aa5bbae3632b4bfe0de4faea7a4da829f">getChunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#aeae88f12b667477f90db9b726556b337">llvm::AArch64_AM::getShifterImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a2cd3e23b97b495a98c0b723ab18e4d96">llvm::AArch64_AM::processLogicalImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#aa20f3eb24c28efa9c93053a733a172c1">tryAndOfLogicalImmediates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#ab2f723b31c9dbe46610248a047805046">tryEorOfLogicalImmediates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#ae492dde0ae62ef0c16a80f8b648bae19">tryOrrOfLogicalImmediates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#a7000ac817f63a64697020f0538311927">trySequenceOfOnes</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#a6efd5b30fe34a042d2937ba63a73ad07">tryToreplicateChunks</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aca56c12eb63eea9e71e826a1e888b51d">llvm::AArch64TTIImpl::getIntImmCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aec461d6b4eaa16935dd0b7691b39ec4a">isCheapImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0b5597ce1a7049500d0b30bef14951ca">llvm::AArch64TargetLowering::isFPImmLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#af8e97755935ce2a3c03a0ba055b310c2">llvm::AArch64TargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#abb8ed73d70e625c6ab95a50c2ba8b546">splitAddSubImm</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a681a012ac18b27513b6715881d002520">anonymous{AArch64PostLegalizerLowering.cpp}::tryAdjustICmpImmAndPred</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp">AArch64ExpandImm.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-h">AArch64ExpandImm.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
