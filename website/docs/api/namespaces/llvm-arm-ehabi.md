---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/arm/ehabi
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `EHABI` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::ARM::EHABI { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EHTEntryKind { <a href="#afc1f04cd16158b4185cda78332876407">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> exception handling table entry kinds. <a href="#afc1f04cd16158b4185cda78332876407">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#ae9c298f7e89c08953de7592e884a8b58">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">UnwindOpcodes { <a href="#a391979058f7394854c8e99446129c5aa">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ARM-defined frame unwinding opcodes. <a href="#a391979058f7394854c8e99446129c5aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PersonalityRoutineIndex { <a href="#a7b99cf0c7d83797700266fe3d55872e7">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ARM-defined Personality Routine Index. <a href="#a7b99cf0c7d83797700266fe3d55872e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#ae9c298f7e89c08953de7592e884a8b58}

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
<td class="doxyEnumItemName">EXIDX_CANTUNWIND<a id="ae9c298f7e89c08953de7592e884a8b58a66015da63b154337078e073b41ae19ee"></a></td>
<td class="doxyEnumItemDescription">Special entry for the function never unwind (= 0x1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armehabi-h">ARMEHABI.h</a>.</p>

</div>
</div>

### EHTEntryKind {#afc1f04cd16158b4185cda78332876407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARM::EHABI::EHTEntryKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> exception handling table entry kinds.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EHT_GENERIC<a id="afc1f04cd16158b4185cda78332876407ae264097ea85fec893386d1f3a5d05610"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EHT_COMPACT<a id="afc1f04cd16158b4185cda78332876407aaefc75aa4a61986d09351560125d7e2f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x80)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armehabi-h">ARMEHABI.h</a>.</p>

</div>
</div>

### PersonalityRoutineIndex {#a7b99cf0c7d83797700266fe3d55872e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARM::EHABI::PersonalityRoutineIndex </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ARM-defined Personality Routine Index.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AEABI_UNWIND_CPP_PR0<a id="a7b99cf0c7d83797700266fe3d55872e7a74f0546618adde7fd3715e03c8af0d09"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AEABI_UNWIND_CPP_PR1<a id="a7b99cf0c7d83797700266fe3d55872e7a091a1026c8394033f84acddfe2ad596d"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AEABI_UNWIND_CPP_PR2<a id="a7b99cf0c7d83797700266fe3d55872e7ac660a01899d3599dec718aca532db0de"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NUM_PERSONALITY_INDEX<a id="a7b99cf0c7d83797700266fe3d55872e7a95314429fa79c010af353b0a2c8f75d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armehabi-h">ARMEHABI.h</a>.</p>

</div>
</div>

### UnwindOpcodes {#a391979058f7394854c8e99446129c5aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARM::EHABI::UnwindOpcodes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ARM-defined frame unwinding opcodes.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_INC_VSP<a id="a391979058f7394854c8e99446129c5aaaa5fb6fa61b25402c5a11953776e94069"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_DEC_VSP<a id="a391979058f7394854c8e99446129c5aaa88017af7551328f81fac3ba62cd12258"></a></td>
<td class="doxyEnumItemDescription"> (= 0x40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_REFUSE<a id="a391979058f7394854c8e99446129c5aaa28de741b7d8a551512cbd8e812d48e66"></a></td>
<td class="doxyEnumItemDescription"> (= 0x8000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_REG_MASK_R4<a id="a391979058f7394854c8e99446129c5aaaf6b4129defb78ab1e27de68558cdad7e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x8000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_SET_VSP<a id="a391979058f7394854c8e99446129c5aaafb874bc6779295f8e3e6b4cecfd406bf"></a></td>
<td class="doxyEnumItemDescription"> (= 0x90)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_REG_RANGE_R4<a id="a391979058f7394854c8e99446129c5aaa0a91a90150205dd8f3e3f3e5d764e34c"></a></td>
<td class="doxyEnumItemDescription"> (= 0xa0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_REG_RANGE_R4_R14<a id="a391979058f7394854c8e99446129c5aaae8ab15ac55a28dc3b1954b3159a9cd61"></a></td>
<td class="doxyEnumItemDescription"> (= 0xa8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_FINISH<a id="a391979058f7394854c8e99446129c5aaa0aaf8dcf3c0ab164c43d61219444ea9f"></a></td>
<td class="doxyEnumItemDescription"> (= 0xb0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_RA_AUTH_CODE<a id="a391979058f7394854c8e99446129c5aaaefcc1e6af568599a852b5a634db6f75d"></a></td>
<td class="doxyEnumItemDescription"> (= 0xb4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_REG_MASK<a id="a391979058f7394854c8e99446129c5aaa9a03bf3866742ac1b888bee3b12b36f6"></a></td>
<td class="doxyEnumItemDescription"> (= 0xb100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_INC_VSP_ULEB128<a id="a391979058f7394854c8e99446129c5aaac7fec19e4c3252adc0fe1c56e7517633"></a></td>
<td class="doxyEnumItemDescription"> (= 0xb2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_VFP_REG_RANGE_FSTMFDX<a id="a391979058f7394854c8e99446129c5aaae57f6a4d3ecba2c13f8cb42a33d22f22"></a></td>
<td class="doxyEnumItemDescription"> (= 0xb300)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_VFP_REG_RANGE_FSTMFDX_D8<a id="a391979058f7394854c8e99446129c5aaa33a9dd3ac5d672917f867f8ef5d6569b"></a></td>
<td class="doxyEnumItemDescription"> (= 0xb8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_WIRELESS_MMX_REG_RANGE_WR10<a id="a391979058f7394854c8e99446129c5aaa8f9dbd9546ae0a82113bb7891296cad2"></a></td>
<td class="doxyEnumItemDescription"> (= 0xc0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_WIRELESS_MMX_REG_RANGE<a id="a391979058f7394854c8e99446129c5aaa47fb210095d0373575ac7208866a2e1e"></a></td>
<td class="doxyEnumItemDescription"> (= 0xc600)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_WIRELESS_MMX_REG_MASK<a id="a391979058f7394854c8e99446129c5aaa35e150c8337de682649a961eb3b4d8ec"></a></td>
<td class="doxyEnumItemDescription"> (= 0xc700)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_VFP_REG_RANGE_FSTMFDD_D16<a id="a391979058f7394854c8e99446129c5aaa943f3a70dcab5069c2f70c1745031102"></a></td>
<td class="doxyEnumItemDescription"> (= 0xc800)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_VFP_REG_RANGE_FSTMFDD<a id="a391979058f7394854c8e99446129c5aaaf3a1f5132396873d78fb4e5810ad2f82"></a></td>
<td class="doxyEnumItemDescription"> (= 0xc900)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_OPCODE_POP_VFP_REG_RANGE_FSTMFDD_D8<a id="a391979058f7394854c8e99446129c5aaa70e34569a0cdd4886c25ce46c454bbbb"></a></td>
<td class="doxyEnumItemDescription"> (= 0xd0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armehabi-h">ARMEHABI.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armehabi-h">ARMEHABI.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
