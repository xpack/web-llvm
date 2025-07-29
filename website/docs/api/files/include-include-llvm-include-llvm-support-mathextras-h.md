---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/support/mathextras-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MathExtras.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bit-h">llvm/ADT/bit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include &lt;cassert&gt;
#include &lt;climits&gt;
#include &lt;cstdint&gt;
#include &lt;cstring&gt;
#include &lt;limits&gt;
#include &lt;type_traits&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/numbers">numbers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mathematical constants. <a href="/web-llvm/docs/api/namespaces/llvm/numbers/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>(n)&nbsp;&nbsp;&nbsp;n, n + 2 * 64, n + 1 * 64, n + 3 * 64</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a166646d6a4037a236119b6e156051d90">R4</a>(n)&nbsp;&nbsp;&nbsp;<a href="#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>(n), <a href="#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>(n + 2 * 16), <a href="#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>(n + 1 * 16), <a href="#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>(n + 3 * 16)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace331bebb5bd2780b8dfb7e6e97db7dd">R6</a>(n)&nbsp;&nbsp;&nbsp;<a href="#a166646d6a4037a236119b6e156051d90">R4</a>(n), <a href="#a166646d6a4037a236119b6e156051d90">R4</a>(n + 2 * 4), <a href="#a166646d6a4037a236119b6e156051d90">R4</a>(n + 1 * 4), <a href="#a166646d6a4037a236119b6e156051d90">R4</a>(n + 3 * 4)</td>
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


<div class="doxySectionDef">

## Macro Definitions

### R2 {#a9211f62d8e1e6de999eaa63ec0f6ae02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define R2(n)&nbsp;&nbsp;&nbsp;n, n + 2 * 64, n + 1 * 64, n + 3 * 64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">MathExtras.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a0adb0a856adef09fd017379f4644ba4e">convertFSqrtDivIntoFMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a5e94665a52b9daea5f22841f60760ab2">emitBSIC</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#afbb80dd4d686b8eda7304201f49f48e9">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateANDrr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a3a175283278a754c84b75df5e20c5796">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPrr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a5c9526b09e12ac8a17ba2ab79aeff1c5">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateORrr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a812ba4120e868c63ef47c07d4963ec29">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateXORrr</a>, <a href="/web-llvm/docs/api/structs/llvm/signeddivisionbyconstantinfo/#affa10b6ac03585fea6d8f1832071ebd5">llvm::SignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#a6a7ecd0f6bb250280a31e56173931e31">llvm::UnsignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#afb719bff41b5688bcd0e39208d11677f">llvm::HexagonRegisterInfo::getCallerSavedRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#af38036e5099e79ebfc62e46c71deb448">llvm::HexagonMCInstrInfo::getDuplexRegisterNumbering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a41add7dc9178ec10f8f2d4d6fd2a6f9a">getFSqrtDivOptPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#aeee622fb99bdc4c058a9ef179d0a0d09">getMaskedTypeForICmpPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#a446af5357a9d75c1c6230bb23792a9f8">IntersectSignedRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#aac7331d34e77a2d041b4ecc387db1318">IntersectUnsignedRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23937faaecd6b00acda39f636f62a986">llvm::isARMLowRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a4d3ad60400165f1708ea8572d996abc3">isFSqrtDivToFMulLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a94974538095721fcce4cf479555bc25c">llvm::AMDGPULegalizerInfo::legalizeBVHIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a68889f2d01c03d8f0e8810917f4db9e3">llvm::mismatch</a>, <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a455d3003d7f58d83850c9f33c259d3bf">llvm::SimpleBitstreamCursor::Read</a>, <a href="/web-llvm/docs/api/classes/anonymous-basicblocksections-cpp-/basicblocksections/#a977d864b83223a6ae106ddc332dba144">anonymous{BasicBlockSections.cpp}::BasicBlockSections::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparciseldagtodag-cpp-/sparcdagtodagisel/#ac1624ad58ad4ccb033d0e35a2f771098">anonymous{SparcISelDAGToDAG.cpp}::SparcDAGToDAGISel::SelectADDRrr</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a19e2ffc6c8269a09ca18d5255ec2345a">llvm::GCNIterativeScheduler::sortRegionsByPressure</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a1671cc3411876afb45d27eac3a048d4a">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectXAR</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a0e3d706240976157dfd3542311dc48cb">upgradeIntrinsicFunction1</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5457b45fe74cf2f411f5824d32fd389d">llvm::InstCombinerImpl::visitFDiv</a>.</p>

</div>
</div>

### R4 {#a166646d6a4037a236119b6e156051d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define R4(n)&nbsp;&nbsp;&nbsp;<a href="#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>(n), <a href="#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>(n + 2 * 16), <a href="#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>(n + 1 * 16), <a href="#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>(n + 3 * 16)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">MathExtras.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#afb719bff41b5688bcd0e39208d11677f">llvm::HexagonRegisterInfo::getCallerSavedRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#af38036e5099e79ebfc62e46c71deb448">llvm::HexagonMCInstrInfo::getDuplexRegisterNumbering</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a23937faaecd6b00acda39f636f62a986">llvm::isARMLowRegister</a>.</p>

</div>
</div>

### R6 {#ace331bebb5bd2780b8dfb7e6e97db7dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define R6(n)&nbsp;&nbsp;&nbsp;<a href="#a166646d6a4037a236119b6e156051d90">R4</a>(n), <a href="#a166646d6a4037a236119b6e156051d90">R4</a>(n + 2 * 4), <a href="#a166646d6a4037a236119b6e156051d90">R4</a>(n + 1 * 4), <a href="#a166646d6a4037a236119b6e156051d90">R4</a>(n + 3 * 4)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">MathExtras.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#afb719bff41b5688bcd0e39208d11677f">llvm::HexagonRegisterInfo::getCallerSavedRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#af38036e5099e79ebfc62e46c71deb448">llvm::HexagonMCInstrInfo::getDuplexRegisterNumbering</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a23937faaecd6b00acda39f636f62a986">llvm::isARMLowRegister</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
