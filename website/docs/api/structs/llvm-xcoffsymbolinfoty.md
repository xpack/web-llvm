---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/xcoffsymbolinfoty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `XCOFFSymbolInfoTy` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::XCOFFSymbolInfoTy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcdisassembler-h">llvm/MC/MCDisassembler/MCDisassembler.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65fb8e5e2d4cfbd4d7e1a47f58452e7d">operator&lt;</a> (const XCOFFSymbolInfoTy &amp;SymInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function is for symbol sorting when symbols have the same address. <a href="#a65fb8e5e2d4cfbd4d7e1a47f58452e7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502c">XCOFF::StorageMappingClass</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac60cea02478e4afe523c826cf49ceee5">StorageMappingClass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9b34ac971fc7a774a083c51de16707d">Index</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b9256679e29b148a4ba782ce84b9fc">IsLabel</a> = false</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcdisassembler-h">MCDisassembler.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a65fb8e5e2d4cfbd4d7e1a47f58452e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool XCOFFSymbolInfoTy::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/xcoffsymbolinfoty">XCOFFSymbolInfoTy</a> &amp; SymInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function is for symbol sorting when symbols have the same address.</p>


<p>The symbols in the same section are sorted in ascending order. llvm-objdump -D will choose the highest priority symbol to display when there are symbols with the same address.</p>


<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcdisassembler-h">MCDisassembler.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/mcdisassembler-cpp">MCDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/mcdisassembler-cpp/#a1adaeab22112e46dd8b933c51c3ea60a">getSMCPriority</a>, <a href="#a54b9256679e29b148a4ba782ce84b9fc">IsLabel</a> and <a href="#ac60cea02478e4afe523c826cf49ceee5">StorageMappingClass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Index {#aa9b34ac971fc7a774a083c51de16707d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint32_t&gt; llvm::XCOFFSymbolInfoTy::Index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcdisassembler-h">MCDisassembler.h</a>.</p>

</div>
</div>

### IsLabel {#a54b9256679e29b148a4ba782ce84b9fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XCOFFSymbolInfoTy::IsLabel = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcdisassembler-h">MCDisassembler.h</a>.</p>


<p>Referenced by <a href="#a65fb8e5e2d4cfbd4d7e1a47f58452e7d">operator&lt;</a>.</p>

</div>
</div>

### StorageMappingClass {#ac60cea02478e4afe523c826cf49ceee5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;XCOFF::StorageMappingClass&gt; llvm::XCOFFSymbolInfoTy::StorageMappingClass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcdisassembler-h">MCDisassembler.h</a>.</p>


<p>Referenced by <a href="#a65fb8e5e2d4cfbd4d7e1a47f58452e7d">operator&lt;</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcdisassembler-h">MCDisassembler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/mcdisassembler-cpp">MCDisassembler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
