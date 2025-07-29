---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/riscvisautils
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `RISCVISAUtils` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::RISCVISAUtils { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/riscvisautils/extensionversion">ExtensionVersion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents the major and version number components of a RISC-V extension. <a href="/web-llvm/docs/api/structs/llvm/riscvisautils/extensionversion/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/riscvisautils/extensioncomparator">ExtensionComparator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class for <a href="#a8557faa65915a2ad7c9f4576d736f50b">OrderedExtensionMap</a>. <a href="/web-llvm/docs/api/structs/llvm/riscvisautils/extensioncomparator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::map&lt; std::string, <a href="/web-llvm/docs/api/structs/llvm/riscvisautils/extensionversion">ExtensionVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvisautils/extensioncomparator">ExtensionComparator</a> &gt; <a href="#a8557faa65915a2ad7c9f4576d736f50b">OrderedExtensionMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a8557faa65915a2ad7c9f4576d736f50b">OrderedExtensionMap</a> is std::map, it's specialized to keep entries in canonical order of extension. <a href="#a8557faa65915a2ad7c9f4576d736f50b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a654410af74995521d4f50201f8d88368">compareExtension</a> (const std::string &amp;LHS, const std::string &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065d642864b925bfe666f5faf6020165">AllStdExts</a> = "mafdqlcbkjtpvnh"</td>
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

## Typedefs

### OrderedExtensionMap {#a8557faa65915a2ad7c9f4576d736f50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::map&lt;std::string, ExtensionVersion, ExtensionComparator&gt; llvm::RISCVISAUtils::OrderedExtensionMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a8557faa65915a2ad7c9f4576d736f50b">OrderedExtensionMap</a> is std::map, it's specialized to keep entries in canonical order of extension.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvisautils-h">RISCVISAUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### compareExtension() {#a654410af74995521d4f50201f8d88368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVISAUtils::compareExtension (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvisautils-h">RISCVISAUtils.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/support/riscvisautils-cpp">RISCVISAUtils.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/riscvisautils-cpp/#adf45c1638338f84c631d8f5a361fbf86">getExtensionRank</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/riscvisautils/extensioncomparator/#a8ac9814f484992b57a137a676bdfd38a">llvm::RISCVISAUtils::ExtensionComparator::operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AllStdExts {#a065d642864b925bfe666f5faf6020165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral llvm::RISCVISAUtils::AllStdExts = "mafdqlcbkjtpvnh"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvisautils-h">RISCVISAUtils.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/riscvisautils-cpp/#ae0834ffd88d8197c3afbc8c356cfb27a">singleLetterExtensionRank</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvisautils-h">RISCVISAUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/riscvisautils-cpp">RISCVISAUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
