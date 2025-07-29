---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/riscvcc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `RISCVCC` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::RISCVCC { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CondCode { <a href="#a54a545c3f090650e4ae09e3174045976">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a54a545c3f090650e4ae09e3174045976">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a037799205d78d34011531cad6a28e92e">getOppositeBranchCondition</a> (CondCode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0cd53e76269a5b4fb26eccfaf39a979">getBrCond</a> (CondCode CC, bool Imm=false)</td>
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

### CondCode {#a54a545c3f090650e4ae09e3174045976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RISCVCC::CondCode </td>
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
<td class="doxyEnumItemName">COND_EQ<a id="a54a545c3f090650e4ae09e3174045976a57d7c413055b2060a90dc73ab8f1a512"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_NE<a id="a54a545c3f090650e4ae09e3174045976a11bb96a4ca4e914a149e9a63e6875ea6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_LT<a id="a54a545c3f090650e4ae09e3174045976a442618536f16dd10730e054e0825b482"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_GE<a id="a54a545c3f090650e4ae09e3174045976a9e7c8526fc843e319e53e5c3174296cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_LTU<a id="a54a545c3f090650e4ae09e3174045976aefa5b6a280d2aec8bf02b490b207a3cb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_GEU<a id="a54a545c3f090650e4ae09e3174045976a12fd715db7ef1428e9cf7b6af55997b8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_INVALID<a id="a54a545c3f090650e4ae09e3174045976af2efde5f90024ff3961e07c0f5f950d9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-h">RISCVInstrInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getBrCond() {#ae0cd53e76269a5b4fb26eccfaf39a979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVCC::getBrCond (<a href="#a54a545c3f090650e4ae09e3174045976">CondCode</a> CC, bool Imm=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-h">RISCVInstrInfo.h</a>, definition at line 951 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a54a545c3f090650e4ae09e3174045976a57d7c413055b2060a90dc73ab8f1a512">COND_EQ</a>, <a href="#a54a545c3f090650e4ae09e3174045976a9e7c8526fc843e319e53e5c3174296cc">COND_GE</a>, <a href="#a54a545c3f090650e4ae09e3174045976a12fd715db7ef1428e9cf7b6af55997b8">COND_GEU</a>, <a href="#a54a545c3f090650e4ae09e3174045976a442618536f16dd10730e054e0825b482">COND_LT</a>, <a href="#a54a545c3f090650e4ae09e3174045976aefa5b6a280d2aec8bf02b490b207a3cb">COND_LTU</a>, <a href="#a54a545c3f090650e4ae09e3174045976a11bb96a4ca4e914a149e9a63e6875ea6">COND_NE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a4d827f36392e59fb8c28117a98873a1c">llvm::RISCVInstrInfo::getBrCond</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a285142054aed60907906550e49ed07e2">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::select</a>.</p>

</div>
</div>

### getOppositeBranchCondition() {#a037799205d78d34011531cad6a28e92e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVCC::CondCode llvm::RISCVCC::getOppositeBranchCondition (<a href="#a54a545c3f090650e4ae09e3174045976">CondCode</a> CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-h">RISCVInstrInfo.h</a>, definition at line 975 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a54a545c3f090650e4ae09e3174045976a57d7c413055b2060a90dc73ab8f1a512">COND_EQ</a>, <a href="#a54a545c3f090650e4ae09e3174045976a9e7c8526fc843e319e53e5c3174296cc">COND_GE</a>, <a href="#a54a545c3f090650e4ae09e3174045976a12fd715db7ef1428e9cf7b6af55997b8">COND_GEU</a>, <a href="#a54a545c3f090650e4ae09e3174045976a442618536f16dd10730e054e0825b482">COND_LT</a>, <a href="#a54a545c3f090650e4ae09e3174045976aefa5b6a280d2aec8bf02b490b207a3cb">COND_LTU</a>, <a href="#a54a545c3f090650e4ae09e3174045976a11bb96a4ca4e914a149e9a63e6875ea6">COND_NE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aabdf5cb19126a5e4243ff0818a908ccb">llvm::RISCVInstrInfo::commuteInstructionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a55d733ab1cd738ca996fd3e415b59c99">llvm::RISCVInstrInfo::optimizeSelect</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-h">RISCVInstrInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
