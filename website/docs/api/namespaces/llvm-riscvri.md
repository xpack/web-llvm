---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/riscvri
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `RISCVRI` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::RISCVRI { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a78e6c59845eada72aa855b2bb9f1e6b4">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0b0c32a37a8ee1a3a8f8b3e1b2affa3">isVRegClass</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6342cae1bd76356e312a8dbcedd1cf4f">getLMul</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98ed2715209a3dddd9b613c56c389210">getNF</a> (uint64_t TSFlags)</td>
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

### anonymous enum  {#a78e6c59845eada72aa855b2bb9f1e6b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">IsVRegClassShift<a id="a78e6c59845eada72aa855b2bb9f1e6b4ab70e0b2c69d11661822b76a39791f561"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsVRegClassShiftMask<a id="a78e6c59845eada72aa855b2bb9f1e6b4a18d930e1cf574b2b37518c426338ab67"></a></td>
<td class="doxyEnumItemDescription"> (= 0b1 &lt;&lt; IsVRegClassShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLMulShift<a id="a78e6c59845eada72aa855b2bb9f1e6b4aa1aab7fc1bc26b06971b5dee334b2755"></a></td>
<td class="doxyEnumItemDescription"> (= IsVRegClassShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLMulShiftMask<a id="a78e6c59845eada72aa855b2bb9f1e6b4a65b111b72f3fa0cb0aab3e18fb22f783"></a></td>
<td class="doxyEnumItemDescription"> (= 0b111 &lt;&lt; VLMulShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFShift<a id="a78e6c59845eada72aa855b2bb9f1e6b4a61c080d5573d39f23cf0ed58399c7d8e"></a></td>
<td class="doxyEnumItemDescription"> (= VLMulShift + 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFShiftMask<a id="a78e6c59845eada72aa855b2bb9f1e6b4a5573d5572ea9c8a6f0c58234d2b5f09a"></a></td>
<td class="doxyEnumItemDescription"> (= 0b111 &lt;&lt; NFShift)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvregisterinfo-h">RISCVRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getLMul() {#a6342cae1bd76356e312a8dbcedd1cf4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVII::VLMUL llvm::RISCVRI::getLMul (uint64_t TSFlags)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the LMUL for the register class.</p></dd>
</dl>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvregisterinfo-h">RISCVRegisterInfo.h</a>.</p>


<p>References <a href="#a78e6c59845eada72aa855b2bb9f1e6b4aa1aab7fc1bc26b06971b5dee334b2755">VLMulShift</a> and <a href="#a78e6c59845eada72aa855b2bb9f1e6b4a65b111b72f3fa0cb0aab3e18fb22f783">VLMulShiftMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a436965f98f9e4301e33096c32ed6dbd2">llvm::RISCVInstrInfo::copyPhysRegVector</a>.</p>

</div>
</div>

### getNF() {#a98ed2715209a3dddd9b613c56c389210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVRI::getNF (uint64_t TSFlags)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the NF for the register class.</p></dd>
</dl>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvregisterinfo-h">RISCVRegisterInfo.h</a>.</p>


<p>References <a href="#a78e6c59845eada72aa855b2bb9f1e6b4a61c080d5573d39f23cf0ed58399c7d8e">NFShift</a> and <a href="#a78e6c59845eada72aa855b2bb9f1e6b4a5573d5572ea9c8a6f0c58234d2b5f09a">NFShiftMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a436965f98f9e4301e33096c32ed6dbd2">llvm::RISCVInstrInfo::copyPhysRegVector</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a332bd6d18c6843b98cd5638ed6516bf1">llvm::RISCVRegisterInfo::isVRNRegClass</a> and <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#acbb4c61a970c46bace27495c19538ac5">llvm::RISCVRegisterInfo::isVRRegClass</a>.</p>

</div>
</div>

### isVRegClass() {#af0b0c32a37a8ee1a3a8f8b3e1b2affa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVRI::isVRegClass (uint64_t TSFlags)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the IsVRegClass for the register class.</p></dd>
</dl>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvregisterinfo-h">RISCVRegisterInfo.h</a>.</p>


<p>References <a href="#a78e6c59845eada72aa855b2bb9f1e6b4ab70e0b2c69d11661822b76a39791f561">IsVRegClassShift</a> and <a href="#a78e6c59845eada72aa855b2bb9f1e6b4a18d930e1cf574b2b37518c426338ab67">IsVRegClassShiftMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a6b0e6be6a451881260fcd7f29b7fb4fc">llvm::RISCVRegisterInfo::isRVVRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#aa7416d4f582d65182fdc05986c346f95">isVectorRegClass</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a332bd6d18c6843b98cd5638ed6516bf1">llvm::RISCVRegisterInfo::isVRNRegClass</a> and <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#acbb4c61a970c46bace27495c19538ac5">llvm::RISCVRegisterInfo::isVRRegClass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvregisterinfo-h">RISCVRegisterInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
