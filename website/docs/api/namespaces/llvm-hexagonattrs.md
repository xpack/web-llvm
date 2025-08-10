---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/hexagonattrs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `HexagonAttrs` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::HexagonAttrs { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AttrType : unsigned { <a href="#a9273648ff11b0cd9cc6c1fca21757b0a">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8ba0ebd86185aea94f29ed853c4dd97f">TagNameMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af945bee73dd4cb14503ed90eff8333a5">getHexagonAttributeTags</a> ()</td>
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

### AttrType {#a9273648ff11b0cd9cc6c1fca21757b0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::HexagonAttrs::AttrType : unsigned</td>
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
<td class="doxyEnumItemName">ARCH<a id="a9273648ff11b0cd9cc6c1fca21757b0aadf72f328baf0f5acf40009bfc48dabb3"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HVXARCH<a id="a9273648ff11b0cd9cc6c1fca21757b0aac5818b77afe27e45bb4800bc6ccf19ba"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HVXIEEEFP<a id="a9273648ff11b0cd9cc6c1fca21757b0aa473fdbf9b41b7242e1d5b95a3cd91753"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HVXQFLOAT<a id="a9273648ff11b0cd9cc6c1fca21757b0aa7f4e1b73534a3e4fe81b45dfa70e4fa8"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZREG<a id="a9273648ff11b0cd9cc6c1fca21757b0aa7616170e3a6a5aa236da071bf245f9fb"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUDIO<a id="a9273648ff11b0cd9cc6c1fca21757b0aae726e716c8bf8c371147056555698773"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CABAC<a id="a9273648ff11b0cd9cc6c1fca21757b0aaab7a5dc2a04b0f4ee795b3b9254a46cd"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hexagonattributes-h">HexagonAttributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getHexagonAttributeTags() {#af945bee73dd4cb14503ed90eff8333a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagNameMap &amp; llvm::HexagonAttrs::getHexagonAttributeTags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 17 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hexagonattributes-h">HexagonAttributes.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/support/hexagonattributes-cpp">HexagonAttributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/hexagonattributes-cpp/#a57945d97d5a41098f96869a539f8be96">HexagonAttributeTags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetasmstreamer/#ae2ca0484586c67bb74f2e1d2c34da106">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetAsmStreamer::emitAttribute</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hexagonattributes-h">HexagonAttributes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/hexagonattributes-cpp">HexagonAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
