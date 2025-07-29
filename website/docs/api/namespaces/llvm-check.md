---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/check
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `Check` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::Check { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/check/filechecktype">FileCheckType</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FileCheckKind { <a href="#a61538d341f95c09113a9a0d0434d8dcc">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">FileCheckKindModifier { <a href="#a067ee17412e800f03802fa9517685732">...</a> }</td>
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

### FileCheckKind {#a61538d341f95c09113a9a0d0434d8dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Check::FileCheckKind </td>
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
<td class="doxyEnumItemName">CheckNone<a id="a61538d341f95c09113a9a0d0434d8dcca9852bebd673f9c43a584b08401e3197d"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckMisspelled<a id="a61538d341f95c09113a9a0d0434d8dccabced3746e039f44b8e662be748fd4e17"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckPlain<a id="a61538d341f95c09113a9a0d0434d8dcca166f25ea09a5e0064149ae472c8d8f2e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckNext<a id="a61538d341f95c09113a9a0d0434d8dcca49f3a249a76b57b5659baae2c45dfb75"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckSame<a id="a61538d341f95c09113a9a0d0434d8dccaf738504ab1341813c0cda15fa68a6310"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckNot<a id="a61538d341f95c09113a9a0d0434d8dcca4f9655da5198915aff91bd25115d22fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckDAG<a id="a61538d341f95c09113a9a0d0434d8dcca6e00b905236376d8aec56ad3351a45b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckLabel<a id="a61538d341f95c09113a9a0d0434d8dccad88307ccd9067d72cfb0e62d19daa77d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckEmpty<a id="a61538d341f95c09113a9a0d0434d8dcca80e33945f521f203f2a632bc0f2041e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckComment<a id="a61538d341f95c09113a9a0d0434d8dccaf16a622382af4f7939c473b436c8f2ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckEOF<a id="a61538d341f95c09113a9a0d0434d8dccaba2d525032487e7def52c8154b19e29c"></a></td>
<td class="doxyEnumItemDescription">Indicates the pattern only matches the end of file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckBadNot<a id="a61538d341f95c09113a9a0d0434d8dcca8b26e2b469fdd62f96446d3299b4189e"></a></td>
<td class="doxyEnumItemDescription">Marks when parsing found a -NOT check combined with another CHECK suffix</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckBadCount<a id="a61538d341f95c09113a9a0d0434d8dccab74df0ffb39a8f2c0918324e23a899f2"></a></td>
<td class="doxyEnumItemDescription">Marks when parsing found a -COUNT directive with invalid count value</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>

</div>
</div>

### FileCheckKindModifier {#a067ee17412e800f03802fa9517685732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Check::FileCheckKindModifier </td>
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
<td class="doxyEnumItemName">ModifierLiteral<a id="a067ee17412e800f03802fa9517685732a563a220961f1b2753b54ca54c648119e"></a></td>
<td class="doxyEnumItemDescription">Modifies directive to perform literal match (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Size<a id="a067ee17412e800f03802fa9517685732a3450a9712780ac26b071f9da4288a396"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
