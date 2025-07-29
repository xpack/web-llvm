---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/riscvzc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `RISCVZC` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::RISCVZC { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RLISTENCODE { <a href="#a828db3401ee4af8cdef6f92bf07c51c5">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54e2576d34133375bf591c8ce734bb9b">encodeRlist</a> (MCRegister EndReg, bool IsRV32E=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ab72861aa74ed55a7b19eabfdcaef0">getStackAdjBase</a> (unsigned RlistVal, bool IsRV64)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9902e13717671a0f79f10c767625bd7">getSpimm</a> (unsigned RlistVal, unsigned &amp;SpimmVal, int64_t StackAdjustment, bool IsRV64)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a4e8a70f59e180ae2284aebb60e42a3">printRlist</a> (unsigned SlistEncode, raw_ostream &amp;OS)</td>
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

## Enumerations

### RLISTENCODE {#a828db3401ee4af8cdef6f92bf07c51c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RISCVZC::RLISTENCODE </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RA<a id="a828db3401ee4af8cdef6f92bf07c51c5ae7ab1a212f15abd8348b30007f66c1af"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RA_S0<a id="a828db3401ee4af8cdef6f92bf07c51c5a8ed1eda3896fa43338e7d230a0a4993d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RA_S0_S1<a id="a828db3401ee4af8cdef6f92bf07c51c5a187af652b39061ed41d0b62352661f32"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RA_S0_S2<a id="a828db3401ee4af8cdef6f92bf07c51c5a31e3e9d613967296c388d36615f6f97d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RA_S0_S3<a id="a828db3401ee4af8cdef6f92bf07c51c5aadd2972b9caac589722230f8a0e765eb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RA_S0_S4<a id="a828db3401ee4af8cdef6f92bf07c51c5ac17ab07c26d45484136905fd4399b743"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RA_S0_S5<a id="a828db3401ee4af8cdef6f92bf07c51c5a0171e14e615b8a32d8e0144f6857f4f3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RA_S0_S6<a id="a828db3401ee4af8cdef6f92bf07c51c5a43ef1bb5618a7dfec8447935265bc7a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RA_S0_S7<a id="a828db3401ee4af8cdef6f92bf07c51c5a5fc8d3f95877d92dac0387673be112f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RA_S0_S8<a id="a828db3401ee4af8cdef6f92bf07c51c5a3150087b02a06cf72986c42415be65d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RA_S0_S9<a id="a828db3401ee4af8cdef6f92bf07c51c5a3b4cce13ba862cdd68e4ef5c7262745c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RA_S0_S11<a id="a828db3401ee4af8cdef6f92bf07c51c5a5ab1e5a9b1ba4f448389be88afcb5127"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INVALID_RLIST<a id="a828db3401ee4af8cdef6f92bf07c51c5a88c54d5a1b8d0b2add526cf7424fc165"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### encodeRlist() {#a54e2576d34133375bf591c8ce734bb9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVZC::encodeRlist (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> EndReg, bool IsRV32E=false)</td>
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



<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a88c54d5a1b8d0b2add526cf7424fc165">INVALID_RLIST</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5ae7ab1a212f15abd8348b30007f66c1af">RA</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a8ed1eda3896fa43338e7d230a0a4993d">RA_S0</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a187af652b39061ed41d0b62352661f32">RA_S0_S1</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a5ab1e5a9b1ba4f448389be88afcb5127">RA_S0_S11</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a31e3e9d613967296c388d36615f6f97d">RA_S0_S2</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5aadd2972b9caac589722230f8a0e765eb">RA_S0_S3</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5ac17ab07c26d45484136905fd4399b743">RA_S0_S4</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a0171e14e615b8a32d8e0144f6857f4f3">RA_S0_S5</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a43ef1bb5618a7dfec8447935265bc7a3">RA_S0_S6</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a5fc8d3f95877d92dac0387673be112f4">RA_S0_S7</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a3150087b02a06cf72986c42415be65d7">RA_S0_S8</a> and <a href="#a828db3401ee4af8cdef6f92bf07c51c5a3b4cce13ba862cdd68e4ef5c7262745c">RA_S0_S9</a>.</p>

</div>
</div>

### getSpimm() {#ac9902e13717671a0f79f10c767625bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVZC::getSpimm (unsigned RlistVal, unsigned &amp; SpimmVal, int64_t StackAdjustment, bool IsRV64)</td>
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



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>.</p>


<p>References <a href="#a33ab72861aa74ed55a7b19eabfdcaef0">getStackAdjBase</a> and <a href="#a828db3401ee4af8cdef6f92bf07c51c5a88c54d5a1b8d0b2add526cf7424fc165">INVALID_RLIST</a>.</p>

</div>
</div>

### getStackAdjBase() {#a33ab72861aa74ed55a7b19eabfdcaef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVZC::getStackAdjBase (unsigned RlistVal, bool IsRV64)</td>
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



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a88c54d5a1b8d0b2add526cf7424fc165">INVALID_RLIST</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5ae7ab1a212f15abd8348b30007f66c1af">RA</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a8ed1eda3896fa43338e7d230a0a4993d">RA_S0</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a187af652b39061ed41d0b62352661f32">RA_S0_S1</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a5ab1e5a9b1ba4f448389be88afcb5127">RA_S0_S11</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a31e3e9d613967296c388d36615f6f97d">RA_S0_S2</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5aadd2972b9caac589722230f8a0e765eb">RA_S0_S3</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5ac17ab07c26d45484136905fd4399b743">RA_S0_S4</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a0171e14e615b8a32d8e0144f6857f4f3">RA_S0_S5</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a43ef1bb5618a7dfec8447935265bc7a3">RA_S0_S6</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a5fc8d3f95877d92dac0387673be112f4">RA_S0_S7</a>, <a href="#a828db3401ee4af8cdef6f92bf07c51c5a3150087b02a06cf72986c42415be65d7">RA_S0_S8</a> and <a href="#a828db3401ee4af8cdef6f92bf07c51c5a3b4cce13ba862cdd68e4ef5c7262745c">RA_S0_S9</a>.</p>


<p>Referenced by <a href="#ac9902e13717671a0f79f10c767625bd7">getSpimm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ad10e372bdad63fb7b26aef3ea2e33fc9">llvm::RISCVInstPrinter::printStackAdj</a>.</p>

</div>
</div>

### printRlist() {#a9a4e8a70f59e180ae2284aebb60e42a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RISCVZC::printRlist (unsigned SlistEncode, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-cpp">RISCVBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a5c67f50a9eeeeebe54d2cb8393b3d956">anonymous{RISCVAsmParser.cpp}::RISCVOperand::print</a>.</p>

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
