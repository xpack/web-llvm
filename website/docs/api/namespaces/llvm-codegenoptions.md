---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/codegenoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `codegenoptions` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::codegenoptions { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DebugInfoFormat { <a href="#af2387489ade7dedcd3eb3fbde4e329cd">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">DebugInfoKind { <a href="#a53c8523a6f1da6d46597d57e212f2d6a">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DebugTemplateNamesKind { <a href="#a8bdfd02a4927b28f11c7340a92cbbb09">...</a> }</td>
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

### DebugInfoFormat {#af2387489ade7dedcd3eb3fbde4e329cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::codegenoptions::DebugInfoFormat </td>
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
<td class="doxyEnumItemName">DIF_DWARF<a id="af2387489ade7dedcd3eb3fbde4e329cdad7c214a86efc666f6ad3d11d0d806051"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIF_CodeView<a id="af2387489ade7dedcd3eb3fbde4e329cda8a525d637b9e61cf897876ac83c2e8c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/debug/options-h">Options.h</a>.</p>

</div>
</div>

### DebugInfoKind {#a53c8523a6f1da6d46597d57e212f2d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::codegenoptions::DebugInfoKind </td>
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
<td class="doxyEnumItemName">NoDebugInfo<a id="a53c8523a6f1da6d46597d57e212f2d6aa5efa96508bffc65b3c13b5bdd74f2091"></a></td>
<td class="doxyEnumItemDescription">Don't generate debug info</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LocTrackingOnly<a id="a53c8523a6f1da6d46597d57e212f2d6aa61014427e5e6bec75b7a5236cdd45b7d"></a></td>
<td class="doxyEnumItemDescription">Emit location information but do not generate debug info in the output</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DebugDirectivesOnly<a id="a53c8523a6f1da6d46597d57e212f2d6aa85c6aa4f4f5bde0abc3477560e571c70"></a></td>
<td class="doxyEnumItemDescription">Emit only debug directives with the line numbers data</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DebugLineTablesOnly<a id="a53c8523a6f1da6d46597d57e212f2d6aade1654f042c5976646d4447775a2cb0a"></a></td>
<td class="doxyEnumItemDescription">Emit only debug info necessary for generating line number tables (-gline-tables-only)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DebugInfoConstructor<a id="a53c8523a6f1da6d46597d57e212f2d6aa3b01b0bb8f8defb1ca19687e7f5f7789"></a></td>
<td class="doxyEnumItemDescription">Limit generated debug info for classes to reduce size</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LimitedDebugInfo<a id="a53c8523a6f1da6d46597d57e212f2d6aa618351bacb827e6a919e8be550cc319a"></a></td>
<td class="doxyEnumItemDescription">Limit generated debug info to reduce size (-fno-standalone-debug)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FullDebugInfo<a id="a53c8523a6f1da6d46597d57e212f2d6aa6836cdc835f0b87af75c226a2f175ab7"></a></td>
<td class="doxyEnumItemDescription">Generate complete debug info</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnusedTypeInfo<a id="a53c8523a6f1da6d46597d57e212f2d6aa0e3504dab6615356f73ce8fdc5db0ede"></a></td>
<td class="doxyEnumItemDescription">Generate debug info for types that may be unused in the source (-fno-eliminate-unused-debug-types)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/debug/options-h">Options.h</a>.</p>

</div>
</div>

### DebugTemplateNamesKind {#a8bdfd02a4927b28f11c7340a92cbbb09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::codegenoptions::DebugTemplateNamesKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Full<a id="a8bdfd02a4927b28f11c7340a92cbbb09abbd47109890259c0127154db1af26c75"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Simple<a id="a8bdfd02a4927b28f11c7340a92cbbb09a1fbb1e3943c2c6c560247ac8f9289780"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mangled<a id="a8bdfd02a4927b28f11c7340a92cbbb09aebe9e17696fcfe4afbf16b9437973d39"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/debug/options-h">Options.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/debug/options-h">Options.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
