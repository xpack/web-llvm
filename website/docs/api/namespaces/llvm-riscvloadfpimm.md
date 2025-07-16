---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/riscvloadfpimm
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `RISCVLoadFPImm` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::RISCVLoadFPImm { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac166c30cbcd4c3c3896916495fedebfd">getFPImm</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56787dd7342f7a3d1ba14262d29d1aab">getLoadFPImm</a> (APFloat FPImm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLoadFPImm - Return a 5-bit binary encoding of the floating-point immediate value. <a href="#a56787dd7342f7a3d1ba14262d29d1aab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### getFPImm() {#ac166c30cbcd4c3c3896916495fedebfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::RISCVLoadFPImm::getFPImm (unsigned Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-cpp">RISCVBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a66801fd0c24bf8b4be297d5b5b974777">llvm::LoadFP32ImmArr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a930e8675c9ef99ced183aea742952d8a">llvm::RISCVInstPrinter::printFPImmOperand</a>.</p>

</div>
</div>

### getLoadFPImm() {#a56787dd7342f7a3d1ba14262d29d1aab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::RISCVLoadFPImm::getLoadFPImm (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> FPImm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getLoadFPImm - Return a 5-bit binary encoding of the floating-point immediate value.</p>


<p>If the value cannot be represented as a 5-bit binary encoding, then return -1.</p>


<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-cpp">RISCVBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a643f8cd038a6fa41604fe8e3df11f977">llvm::APFloat::getSemantics</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86415bb448a78ef1fed893f9eb0f5d06">llvm::APFloatBase::IEEEhalf</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a0c5765e9acba977f6e462c2917276d8f">llvm::APFloatBase::IEEEsingle</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a2b901c3a0625a7d7173e9bd4864e2775">llvm::APFloat::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af8943302f831d2fc16d84eaf1f2740ed">llvm::APFloat::isSmallestNormalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66801fd0c24bf8b4be297d5b5b974777">llvm::LoadFP32ImmArr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aa8092c6b52c0412d8198a63bc995761e9">llvm::APFloatBase::opOK</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a72b37da283ebf9ecc9ef3b8468b9569d">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addFPImmOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac30b30f02593b9a583a7aabb074c2084">llvm::RISCVTargetLowering::getLegalZfaFPImm</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a65b07c2d3b33166b642509347647acee">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isLoadFPImm</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-cpp">RISCVBaseInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
