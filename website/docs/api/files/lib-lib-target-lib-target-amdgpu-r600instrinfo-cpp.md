---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `R600InstrInfo.cpp` File

<p><a href="/web-llvm/docs/api/namespaces/llvm/r600">R600</a> Implementation of <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a>. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/r600mctargetdesc-h">MCTargetDesc/R600MCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h">R600Defines.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600subtarget-h">R600Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "R600GenDFAPacketizer.inc"
#include "R600GenInstrInfo.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; std::pair&lt; int, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97379d7fa3126a13ded0f0d0da0b451d">Swizzle</a> (std::vector&lt; std::pair&lt; int, unsigned &gt; &gt; Src, R600InstrInfo::BankSwizzle Swz)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58438639da1cbfa02c522d1a0132de7">getTransSwizzle</a> (R600InstrInfo::BankSwizzle Swz, unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9477a0a18c76d6cf088f26c7af54e3">NextPossibleSolution</a> (std::vector&lt; R600InstrInfo::BankSwizzle &gt; &amp;SwzCandidate, unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a swizzle sequence SwzCandidate and an index Idx, returns the next (in lexicographic term) swizzle sequence assuming that all swizzles after Idx can be skipped. <a href="#add9477a0a18c76d6cf088f26c7af54e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4f8cbf733d43f4c7fb0d2f2699813e5">isConstCompatible</a> (R600InstrInfo::BankSwizzle TransSwz, const std::vector&lt; std::pair&lt; int, unsigned &gt; &gt; &amp;TransOps, unsigned ConstCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instructions in Trans slot can't read gpr at cycle 0 if they also read a const, and can't read a gpr at cycle 1 if they read 2 const. <a href="#ab4f8cbf733d43f4c7fb0d2f2699813e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdfa90a858cec4adf79af2ca2985b520">isPredicateSetter</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aaab3b6598c7349f766220c8b318744">findFirstPredicateSetterFrom</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af47aa3a4bd7d95e1a17e3bc8d20d92e3">isJump</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d7439b3555f2971b6fe775ae65fc13">isBranch</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a869d77ae27dd6a3e2883d5988c66dd70">FindLastAluClause</a> (MachineBasicBlock &amp;MBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4276d8c21b0e693ccacb27ba6122e70">getSlotedOps</a> (unsigned Op, unsigned Slot)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d99008fb7e5cdc4774786d0743a2c4f">GET_INSTRINFO_CTOR_DTOR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac821edf376bc9320e04db3fbfc85d370">GET_INSTRINFO_CTOR_DTOR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68cd09032654ae05bb2a11b7c60a1cdd">GET_INSTRMAP_INFO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f11ade4c7901484baa40cab9d0d011">GET_INSTRINFO_NAMED_OPS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91cd4602f489830d37bb4f28eabb7996">OPERAND_CASE</a>(Label)&nbsp;&nbsp;&nbsp;...</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/r600">R600</a> Implementation of <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a>.</p>

<div class="doxySectionDef">

## Functions

### findFirstPredicateSetterFrom() {#a0aaab3b6598c7349f766220c8b318744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * findFirstPredicateSetterFrom (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I)</td>
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



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#abdfa90a858cec4adf79af2ca2985b520">isPredicateSetter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a648e69f41d62376b996b0b5209022fbd">llvm::R600InstrInfo::insertBranch</a> and <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a5c764241e49b1b62cbe5153f384ef196">llvm::R600InstrInfo::removeBranch</a>.</p>

</div>
</div>

### FindLastAluClause() {#a869d77ae27dd6a3e2883d5988c66dd70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator FindLastAluClause (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a648e69f41d62376b996b0b5209022fbd">llvm::R600InstrInfo::insertBranch</a> and <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a5c764241e49b1b62cbe5153f384ef196">llvm::R600InstrInfo::removeBranch</a>.</p>

</div>
</div>

### getSlotedOps() {#af4276d8c21b0e693ccacb27ba6122e70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getSlotedOps (unsigned Op, unsigned Slot)</td>
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



<p>Definition at line 1253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a91cd4602f489830d37bb4f28eabb7996">OPERAND_CASE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#aca2b6568c134ce283d74d23db8d6b665">llvm::R600InstrInfo::buildSlotOfVectorInstruction</a>.</p>

</div>
</div>

### getTransSwizzle() {#aa58438639da1cbfa02c522d1a0132de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getTransSwizzle (<a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73">R600InstrInfo::BankSwizzle</a> Swz, unsigned Op)</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73a0832a5c3ff57aae92a383a07ee10062e">llvm::R600InstrInfo::ALU_VEC_012_SCL_210</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73a119ae5f9f75c4e7e3c3dfb1d27b8ef4c">llvm::R600InstrInfo::ALU_VEC_021_SCL_122</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73a6f0dc124051d7de7745100cc80e1db35">llvm::R600InstrInfo::ALU_VEC_102_SCL_221</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73a899a4c04ab90aedc9371144fda3ae335">llvm::R600InstrInfo::ALU_VEC_120_SCL_212</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#ab4f8cbf733d43f4c7fb0d2f2699813e5">isConstCompatible</a> and <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a2fce8516b6f35622360433c3bae2b70c">llvm::R600InstrInfo::isLegalUpTo</a>.</p>

</div>
</div>

### isBranch() {#a54d7439b3555f2971b6fe775ae65fc13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isBranch (unsigned Opcode)</td>
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



<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a086f43049b2d52208b7727be22f5e604">llvm::R600InstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/disassembler/systemzdisassembler-cpp/#a75f4ac701a183d154f7798bf5db43311">decodePCDBLOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmctargetdesc-cpp-/loongarchmcinstranalysis/#a9bbaa778eb8fe8688ceebefc7cc54125">anonymous{LoongArchMCTargetDesc.cpp}::LoongArchMCInstrAnalysis::evaluateBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#aafe1b52718a5cd8afd0dbb15e45b5c17">llvm::HexagonShuffler::GetPacketSummary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0dc17f36db22a5d62643fdce547bb3ea">llvm::HexagonMCInstrInfo::isConstExtended</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a270bc5bd7ab995418f181261d7222804">llvm::HexagonInstrInfo::isPredictedTaken</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a5d95586ea588b8d6938a3e7679766688">llvm::HexagonInstrInfo::reverseBranchCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a409baefdf6be89e38deebefb129c1978">translateImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a4a6656f7c09de82cedabccc211da65c8">tryAddingSymbolicOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#abdc683d623957c050da55f0a39873937">tryAddingSymbolicOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa5797af9ab82a541bb328fc944ce90ea">tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### isConstCompatible() {#ab4f8cbf733d43f4c7fb0d2f2699813e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConstCompatible (<a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73">R600InstrInfo::BankSwizzle</a> TransSwz, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; std::pair&lt; int, unsigned &gt; &gt; &amp; TransOps, unsigned ConstCount)</td>
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

<p>Instructions in Trans slot can't read gpr at cycle 0 if they also read a const, and can't read a gpr at cycle 1 if they read 2 const.</p>

<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Reference <a href="#aa58438639da1cbfa02c522d1a0132de7">getTransSwizzle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#ad4bc494da88251a58ca644dec0d15a2e">llvm::R600InstrInfo::fitsReadPortLimitations</a>.</p>

</div>
</div>

### isJump() {#af47aa3a4bd7d95e1a17e3bc8d20d92e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isJump (unsigned Opcode)</td>
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



<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a086f43049b2d52208b7727be22f5e604">llvm::R600InstrInfo::analyzeBranch</a>.</p>

</div>
</div>

### isPredicateSetter() {#abdfa90a858cec4adf79af2ca2985b520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isPredicateSetter (unsigned Opcode)</td>
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



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a086f43049b2d52208b7727be22f5e604">llvm::R600InstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#ad70329ea652d85d2cdc7095f7ad9c453">llvm::R600InstrInfo::ClobbersPredicate</a> and <a href="#a0aaab3b6598c7349f766220c8b318744">findFirstPredicateSetterFrom</a>.</p>

</div>
</div>

### NextPossibleSolution() {#add9477a0a18c76d6cf088f26c7af54e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NextPossibleSolution (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73">R600InstrInfo::BankSwizzle</a> &gt; &amp; SwzCandidate, unsigned Idx)</td>
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

<p>Given a swizzle sequence SwzCandidate and an index Idx, returns the next (in lexicographic term) swizzle sequence assuming that all swizzles after Idx can be skipped.</p>

<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73a0832a5c3ff57aae92a383a07ee10062e">llvm::R600InstrInfo::ALU_VEC_012_SCL_210</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73a86885db28ad1792f1b4cd022b368d669">llvm::R600InstrInfo::ALU_VEC_210</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#accae71a18e9054f96a7919785976ee15">llvm::R600InstrInfo::FindSwizzleForVectorSlot</a>.</p>

</div>
</div>

### Swizzle() {#a97379d7fa3126a13ded0f0d0da0b451d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::pair&lt; int, unsigned &gt; &gt; Swizzle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; std::pair&lt; int, unsigned &gt; &gt; Src, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73">R600InstrInfo::BankSwizzle</a> Swz)</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73a0832a5c3ff57aae92a383a07ee10062e">llvm::R600InstrInfo::ALU_VEC_012_SCL_210</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73a119ae5f9f75c4e7e3c3dfb1d27b8ef4c">llvm::R600InstrInfo::ALU_VEC_021_SCL_122</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73a6f0dc124051d7de7745100cc80e1db35">llvm::R600InstrInfo::ALU_VEC_102_SCL_221</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73a899a4c04ab90aedc9371144fda3ae335">llvm::R600InstrInfo::ALU_VEC_120_SCL_212</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73aa6bf14686367ef224ca73de39bf15703">llvm::R600InstrInfo::ALU_VEC_201</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a684a33b88b11aeed1300272bb4cf9f73a86885db28ad1792f1b4cd022b368d669">llvm::R600InstrInfo::ALU_VEC_210</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a2fce8516b6f35622360433c3bae2b70c">llvm::R600InstrInfo::isLegalUpTo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### GET\_INSTRINFO\_CTOR\_DTOR {#a5d99008fb7e5cdc4774786d0743a2c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_CTOR_DTOR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### GET\_INSTRINFO\_CTOR\_DTOR {#ac821edf376bc9320e04db3fbfc85d370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_CTOR_DTOR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### GET\_INSTRINFO\_NAMED\_OPS {#a16f11ade4c7901484baa40cab9d0d011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_NAMED_OPS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### GET\_INSTRMAP\_INFO {#a68cd09032654ae05bb2a11b7c60a1cdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRMAP_INFO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### OPERAND\_CASE {#a91cd4602f489830d37bb4f28eabb7996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OPERAND_CASE(Label)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case Label: { \
    static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">Ops</a>[] = \
    { \
      Label##_X, \
      Label##_Y, \
      Label##_Z, \
      Label##_W \
    }; \
    return <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">Ops</a>[Slot]; \
  }
</div>
</dd>
</dl>

<p>Definition at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#af4276d8c21b0e693ccacb27ba6122e70">getSlotedOps</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
