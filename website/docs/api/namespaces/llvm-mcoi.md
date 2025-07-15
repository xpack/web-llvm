---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/mcoi
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `MCOI` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::MCOI { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandConstraint { <a href="#aaa8eb58fd1b8466eb64a43df890cb8c1">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Operand constraints. <a href="#aaa8eb58fd1b8466eb64a43df890cb8c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandFlags { <a href="#a998e4790d0be1c768cbd5bb476686876">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These are flags set on operands, but should be considered private, all access should go through the <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo">MCOperandInfo</a> accessors. <a href="#a998e4790d0be1c768cbd5bb476686876">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandType { <a href="#ad9dfed338ec3d47f30c593ee49cbf96d">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Operands are tagged with one of the values of this enum. <a href="#ad9dfed338ec3d47f30c593ee49cbf96d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### OperandConstraint {#aaa8eb58fd1b8466eb64a43df890cb8c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCOI::OperandConstraint </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Operand constraints.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TIED_TO<a id="aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EARLY_CLOBBER<a id="aaa8eb58fd1b8466eb64a43df890cb8c1aa8498cb1d31308a367c23286fa443716"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>These are encoded in 16 bits with one of the low-order 3 bits specifying that a constraint is present and the corresponding high-order hex digit specifying the constraint value. This allows for a maximum of 3 constraints.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>

</div>
</div>

### OperandFlags {#a998e4790d0be1c768cbd5bb476686876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCOI::OperandFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These are flags set on operands, but should be considered private, all access should go through the <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo">MCOperandInfo</a> accessors.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LookupPtrRegClass<a id="a998e4790d0be1c768cbd5bb476686876a3f4613c966a25662474f5d1645af6b00"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Predicate<a id="a998e4790d0be1c768cbd5bb476686876ab1461a089ae820c837ae97bc8c612dc8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OptionalDef<a id="a998e4790d0be1c768cbd5bb476686876a45389b0b54f87d8dd6451e607463e2f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BranchTarget<a id="a998e4790d0be1c768cbd5bb476686876a7214f80b52abfda8216712827a8743a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>See the accessors for a description of what these are.</p>


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>

</div>
</div>

### OperandType {#ad9dfed338ec3d47f30c593ee49cbf96d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCOI::OperandType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Operands are tagged with one of the values of this enum.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UNKNOWN<a id="ad9dfed338ec3d47f30c593ee49cbf96da83076f86f6450732bc883b8723492eb2"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_IMMEDIATE<a id="ad9dfed338ec3d47f30c593ee49cbf96da767514e15ea244ad3e683ae79b583534"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_REGISTER<a id="ad9dfed338ec3d47f30c593ee49cbf96da62a6ddcdddcce55f836b1720d29f90dc"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_MEMORY<a id="ad9dfed338ec3d47f30c593ee49cbf96da777022119f804325c388f44ccd8524e5"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_PCREL<a id="ad9dfed338ec3d47f30c593ee49cbf96da4ab8ff4de9da34b9b60f04a21860aec1"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_FIRST_GENERIC<a id="ad9dfed338ec3d47f30c593ee49cbf96da9c1b4fee0481848b7ede086f9bba9ded"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_GENERIC_0<a id="ad9dfed338ec3d47f30c593ee49cbf96da9d91ca77438f331351ff52a89bf14c88"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_GENERIC_1<a id="ad9dfed338ec3d47f30c593ee49cbf96da58357ec2eafafe432f311d2e6d81077b"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_GENERIC_2<a id="ad9dfed338ec3d47f30c593ee49cbf96da4c331d30c2ed39ba95bef6d7276021e6"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_GENERIC_3<a id="ad9dfed338ec3d47f30c593ee49cbf96da75a285ee8fad18f515d9dde7868cfb53"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_GENERIC_4<a id="ad9dfed338ec3d47f30c593ee49cbf96da12ba721e6374735955b7fd1b89146dce"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_GENERIC_5<a id="ad9dfed338ec3d47f30c593ee49cbf96daa7f9e35ab0a7d9b58d114769a5944f6f"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_LAST_GENERIC<a id="ad9dfed338ec3d47f30c593ee49cbf96da8b1f03c574eba95352f9e531dbad42b4"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_FIRST_GENERIC_IMM<a id="ad9dfed338ec3d47f30c593ee49cbf96dabc8440cd13a43eecdbd002b4f2779140"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_GENERIC_IMM_0<a id="ad9dfed338ec3d47f30c593ee49cbf96da6a3d9b8c91fef9c0b179f5cdbaab2133"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_LAST_GENERIC_IMM<a id="ad9dfed338ec3d47f30c593ee49cbf96dac75b98f7dd3d0cfc2a89eed680e66f27"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_FIRST_TARGET<a id="ad9dfed338ec3d47f30c593ee49cbf96da6619d4370b1a40e206553ecf49e168e0"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
