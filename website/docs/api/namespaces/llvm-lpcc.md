---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/lpcc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `LPCC` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::LPCC { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CondCode { <a href="#a402439560272232a2e241a32dcb19f63">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d3fc0a526c1cca09194592113edb43">lanaiCondCodeToString</a> (LPCC::CondCode CC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a402439560272232a2e241a32dcb19f63">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a444b7661fff6a2bcb99552d068bb3aca">suffixToLanaiCondCode</a> (StringRef S)</td>
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

### CondCode {#a402439560272232a2e241a32dcb19f63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LPCC::CondCode </td>
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
<td class="doxyEnumItemName">ICC_T<a id="a402439560272232a2e241a32dcb19f63a8deb801305591326bd46652c46a63af9"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_F<a id="a402439560272232a2e241a32dcb19f63ae0a7df38f0c12918214e854e6deee51d"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_HI<a id="a402439560272232a2e241a32dcb19f63ac145e413a917503f7a67eb6bc48d04ef"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_UGT<a id="a402439560272232a2e241a32dcb19f63a2ba53401f8d9a21d6ae2d6a58a1a64c2"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_LS<a id="a402439560272232a2e241a32dcb19f63addd15e46a2dd7b17ad5f9e1361894c7b"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_ULE<a id="a402439560272232a2e241a32dcb19f63a6c9b960377b413c99d31e8967c5ccd5e"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_CC<a id="a402439560272232a2e241a32dcb19f63a6b459fb381cd6527b9d3ef42cd9dff94"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_ULT<a id="a402439560272232a2e241a32dcb19f63ab0124a0d76493ea36ad8a6e026c315fd"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_CS<a id="a402439560272232a2e241a32dcb19f63a735741ae657bc89272f0ae7450083955"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_UGE<a id="a402439560272232a2e241a32dcb19f63a724e26bce1694b023f3b753479d51a04"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_NE<a id="a402439560272232a2e241a32dcb19f63a5f1cb00bb0ede601421beb828a5d4b76"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_EQ<a id="a402439560272232a2e241a32dcb19f63ad36d0e67aa10b86b18c882bdcaf8b1e6"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_VC<a id="a402439560272232a2e241a32dcb19f63ab4b351de10d06667563764f4bde545ba"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_VS<a id="a402439560272232a2e241a32dcb19f63ace781999f382382719a06a2980682289"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_PL<a id="a402439560272232a2e241a32dcb19f63a65ea2278be672ad82bbdd398e55a1385"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_MI<a id="a402439560272232a2e241a32dcb19f63a815c7346bf7c8148f67f65c435a5b5dc"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_GE<a id="a402439560272232a2e241a32dcb19f63a12652b0d33f1f971dbf5a4fd38bc5aff"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_LT<a id="a402439560272232a2e241a32dcb19f63ad9d53591ae8b91e43083845563944a70"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_GT<a id="a402439560272232a2e241a32dcb19f63a593c3982b94c15ee37c1eedae8ad32af"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICC_LE<a id="a402439560272232a2e241a32dcb19f63a70d686d83ff0b4e0e35b9fb7f58baec2"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNKNOWN<a id="a402439560272232a2e241a32dcb19f63aa2b0af36cf77392c4cb0b9d17e06f2ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 10 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaicondcode-h">LanaiCondCode.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### lanaiCondCodeToString() {#a62d3fc0a526c1cca09194592113edb43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::LPCC::lanaiCondCodeToString (<a href="#a402439560272232a2e241a32dcb19f63">LPCC::CondCode</a> CC)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaicondcode-h">LanaiCondCode.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a402439560272232a2e241a32dcb19f63ad36d0e67aa10b86b18c882bdcaf8b1e6">ICC_EQ</a>, <a href="#a402439560272232a2e241a32dcb19f63ae0a7df38f0c12918214e854e6deee51d">ICC_F</a>, <a href="#a402439560272232a2e241a32dcb19f63a12652b0d33f1f971dbf5a4fd38bc5aff">ICC_GE</a>, <a href="#a402439560272232a2e241a32dcb19f63a593c3982b94c15ee37c1eedae8ad32af">ICC_GT</a>, <a href="#a402439560272232a2e241a32dcb19f63a70d686d83ff0b4e0e35b9fb7f58baec2">ICC_LE</a>, <a href="#a402439560272232a2e241a32dcb19f63ad9d53591ae8b91e43083845563944a70">ICC_LT</a>, <a href="#a402439560272232a2e241a32dcb19f63a815c7346bf7c8148f67f65c435a5b5dc">ICC_MI</a>, <a href="#a402439560272232a2e241a32dcb19f63a5f1cb00bb0ede601421beb828a5d4b76">ICC_NE</a>, <a href="#a402439560272232a2e241a32dcb19f63a65ea2278be672ad82bbdd398e55a1385">ICC_PL</a>, <a href="#a402439560272232a2e241a32dcb19f63a8deb801305591326bd46652c46a63af9">ICC_T</a>, <a href="#a402439560272232a2e241a32dcb19f63a724e26bce1694b023f3b753479d51a04">ICC_UGE</a>, <a href="#a402439560272232a2e241a32dcb19f63a2ba53401f8d9a21d6ae2d6a58a1a64c2">ICC_UGT</a>, <a href="#a402439560272232a2e241a32dcb19f63a6c9b960377b413c99d31e8967c5ccd5e">ICC_ULE</a>, <a href="#a402439560272232a2e241a32dcb19f63ab0124a0d76493ea36ad8a6e026c315fd">ICC_ULT</a>, <a href="#a402439560272232a2e241a32dcb19f63ab4b351de10d06667563764f4bde545ba">ICC_VC</a>, <a href="#a402439560272232a2e241a32dcb19f63ace781999f382382719a06a2980682289">ICC_VS</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### suffixToLanaiCondCode() {#a444b7661fff6a2bcb99552d068bb3aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CondCode llvm::LPCC::suffixToLanaiCondCode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaicondcode-h">LanaiCondCode.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa50a7b1fb270f50ee5fe0db126b9f75f">llvm::StringSwitch&lt; T, R &gt;::EndsWith</a>, <a href="#a402439560272232a2e241a32dcb19f63a6b459fb381cd6527b9d3ef42cd9dff94">ICC_CC</a>, <a href="#a402439560272232a2e241a32dcb19f63a735741ae657bc89272f0ae7450083955">ICC_CS</a>, <a href="#a402439560272232a2e241a32dcb19f63ad36d0e67aa10b86b18c882bdcaf8b1e6">ICC_EQ</a>, <a href="#a402439560272232a2e241a32dcb19f63ae0a7df38f0c12918214e854e6deee51d">ICC_F</a>, <a href="#a402439560272232a2e241a32dcb19f63a12652b0d33f1f971dbf5a4fd38bc5aff">ICC_GE</a>, <a href="#a402439560272232a2e241a32dcb19f63a593c3982b94c15ee37c1eedae8ad32af">ICC_GT</a>, <a href="#a402439560272232a2e241a32dcb19f63ac145e413a917503f7a67eb6bc48d04ef">ICC_HI</a>, <a href="#a402439560272232a2e241a32dcb19f63a70d686d83ff0b4e0e35b9fb7f58baec2">ICC_LE</a>, <a href="#a402439560272232a2e241a32dcb19f63addd15e46a2dd7b17ad5f9e1361894c7b">ICC_LS</a>, <a href="#a402439560272232a2e241a32dcb19f63ad9d53591ae8b91e43083845563944a70">ICC_LT</a>, <a href="#a402439560272232a2e241a32dcb19f63a815c7346bf7c8148f67f65c435a5b5dc">ICC_MI</a>, <a href="#a402439560272232a2e241a32dcb19f63a5f1cb00bb0ede601421beb828a5d4b76">ICC_NE</a>, <a href="#a402439560272232a2e241a32dcb19f63a65ea2278be672ad82bbdd398e55a1385">ICC_PL</a>, <a href="#a402439560272232a2e241a32dcb19f63a8deb801305591326bd46652c46a63af9">ICC_T</a>, <a href="#a402439560272232a2e241a32dcb19f63a724e26bce1694b023f3b753479d51a04">ICC_UGE</a>, <a href="#a402439560272232a2e241a32dcb19f63a2ba53401f8d9a21d6ae2d6a58a1a64c2">ICC_UGT</a>, <a href="#a402439560272232a2e241a32dcb19f63a6c9b960377b413c99d31e8967c5ccd5e">ICC_ULE</a>, <a href="#a402439560272232a2e241a32dcb19f63ab0124a0d76493ea36ad8a6e026c315fd">ICC_ULT</a>, <a href="#a402439560272232a2e241a32dcb19f63ab4b351de10d06667563764f4bde545ba">ICC_VC</a>, <a href="#a402439560272232a2e241a32dcb19f63ace781999f382382719a06a2980682289">ICC_VS</a> and <a href="#a402439560272232a2e241a32dcb19f63aa2b0af36cf77392c4cb0b9d17e06f2ef">UNKNOWN</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaicondcode-h">LanaiCondCode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
