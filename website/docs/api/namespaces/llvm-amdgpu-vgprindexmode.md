---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpu/vgprindexmode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `VGPRIndexMode` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPU::VGPRIndexMode { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Id : unsigned { <a href="#a9afd95476c40096a5898ba0f06370b3a">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">EncBits : unsigned { <a href="#af5252ebf458b72b49d66ec97f51841e3">...</a> }</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3633540a5f742545174e6c251a5aa77a">IdSymbolic</a>[] = ...</td>
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

### EncBits {#af5252ebf458b72b49d66ec97f51841e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::VGPRIndexMode::EncBits : unsigned</td>
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
<td class="doxyEnumItemName">OFF<a id="af5252ebf458b72b49d66ec97f51841e3a11888c04a6eafe3c6e1bd5c1267f92aa"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRC0_ENABLE<a id="af5252ebf458b72b49d66ec97f51841e3a064e9e9900217c959cd4bec112627012"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; ID_SRC0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRC1_ENABLE<a id="af5252ebf458b72b49d66ec97f51841e3a2c817b1bc3c82db4a5a4da59d6c46166"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; ID_SRC1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRC2_ENABLE<a id="af5252ebf458b72b49d66ec97f51841e3a28ed8b99cc4a42fdf2118a6c56370ed7"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; ID_SRC2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DST_ENABLE<a id="af5252ebf458b72b49d66ec97f51841e3adf241b71cde6b36cee10241a2e89fda3"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; ID_DST)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENABLE_MASK<a id="af5252ebf458b72b49d66ec97f51841e3a6e7bf5dc7392f0c436832b8f4925edca"></a></td>
<td class="doxyEnumItemDescription"> (= SRC0_ENABLE | SRC1_ENABLE | SRC2_ENABLE | DST_ENABLE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNDEF<a id="af5252ebf458b72b49d66ec97f51841e3a281986d81382b7cb4d8b26022b439d54"></a></td>
<td class="doxyEnumItemDescription"> (= 0xFFFF)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### Id {#a9afd95476c40096a5898ba0f06370b3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::VGPRIndexMode::Id : unsigned</td>
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
<td class="doxyEnumItemName">ID_SRC0<a id="a9afd95476c40096a5898ba0f06370b3aab08c37eb0230d24d838f80a7702bd174"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_SRC1<a id="a9afd95476c40096a5898ba0f06370b3aa3a427c2cfe11fb3c9c5ecf724d8fdfba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_SRC2<a id="a9afd95476c40096a5898ba0f06370b3aaf579a869dd947df8162726874ef4f920"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_DST<a id="a9afd95476c40096a5898ba0f06370b3aa39b4c604ae3c3c92137e9edbc4f4a149"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_MIN<a id="a9afd95476c40096a5898ba0f06370b3aac95e69cbecdf2384529d8d832b09a9fd"></a></td>
<td class="doxyEnumItemDescription"> (= ID_SRC0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_MAX<a id="a9afd95476c40096a5898ba0f06370b3aa7f78de6c8b0734050d847d1cb4c68298"></a></td>
<td class="doxyEnumItemDescription"> (= ID_DST)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### IdSymbolic {#a3633540a5f742545174e6c251a5aa77a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char *const llvm::AMDGPU::VGPRIndexMode::IdSymbolic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "SRC0",
  "SRC1",
  "SRC2",
  "DST",
}
</div>
</dd>
</dl>

<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
