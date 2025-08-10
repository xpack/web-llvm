---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/xtensa
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `Xtensa` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::Xtensa { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FixupKind { <a href="#a7660016e6225977067ab7a52b8b79139">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c2628ded8243112e65c841f7d5fc15e">isValidAddrOffset</a> (int Scale, int64_t OffsetVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ca95e6bbe211b58b5668adccf4dded">isValidAddrOffsetForOpcode</a> (unsigned Opcode, int64_t Offset)</td>
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

### FixupKind {#a7660016e6225977067ab7a52b8b79139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Xtensa::FixupKind </td>
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
<td class="doxyEnumItemName">fixup_xtensa_branch_6<a id="a7660016e6225977067ab7a52b8b79139a5792ea157beaf1cfbf6f8f483b01e8af"></a></td>
<td class="doxyEnumItemDescription"> (= FirstTargetFixupKind)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_xtensa_branch_8<a id="a7660016e6225977067ab7a52b8b79139a3fc9f6933faa36f6115502ad28d83884"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_xtensa_branch_12<a id="a7660016e6225977067ab7a52b8b79139a245faf4bead69100d71b864e34a61288"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_xtensa_jump_18<a id="a7660016e6225977067ab7a52b8b79139afda3cf189692b2acad44b63268ef2698"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_xtensa_call_18<a id="a7660016e6225977067ab7a52b8b79139a83acfe932684605f57edc1dc381e3496"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_xtensa_l32r_16<a id="a7660016e6225977067ab7a52b8b79139a7d2505eb255d54422355d2f809a68e05"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_xtensa_invalid<a id="a7660016e6225977067ab7a52b8b79139ad08546373b51f49c9e69a8332e14eb1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastTargetFixupKind<a id="a7660016e6225977067ab7a52b8b79139af15b99e316b3c4990adf4a1ea7828518"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumTargetFixupKinds<a id="a7660016e6225977067ab7a52b8b79139ae1d153b6ca9da4594ba5804b08a2ebd4"></a></td>
<td class="doxyEnumItemDescription"> (= LastTargetFixupKind - FirstTargetFixupKind)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensafixupkinds-h">XtensaFixupKinds.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### isValidAddrOffset() {#a7c2628ded8243112e65c841f7d5fc15e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Xtensa::isValidAddrOffset (int Scale, int64_t OffsetVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-h">XtensaMCTargetDesc.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp">XtensaMCTargetDesc.cpp</a>.</p>


<p>Referenced by <a href="#aa5ca95e6bbe211b58b5668adccf4dded">isValidAddrOffsetForOpcode</a> and <a href="/web-llvm/docs/api/classes/anonymous-xtensaiseldagtodag-cpp-/xtensadagtodagisel/#a611332c1cb50a3749442786ad5576359">anonymous{XtensaISelDAGToDAG.cpp}::XtensaDAGToDAGISel::selectMemRegAddr</a>.</p>

</div>
</div>

### isValidAddrOffsetForOpcode() {#aa5ca95e6bbe211b58b5668adccf4dded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Xtensa::isValidAddrOffsetForOpcode (unsigned Opcode, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-h">XtensaMCTargetDesc.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp">XtensaMCTargetDesc.cpp</a>.</p>


<p>References <a href="#a7c2628ded8243112e65c841f7d5fc15e">isValidAddrOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaregisterinfo/#a6411a92c3a3ac8af31ab80b05b0b24fe">llvm::XtensaRegisterInfo::eliminateFrameIndex</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensafixupkinds-h">XtensaFixupKinds.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp">XtensaMCTargetDesc.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-h">XtensaMCTargetDesc.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
