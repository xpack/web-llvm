---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/binarysubstreamref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `BinarySubstreamRef` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::BinarySubstreamRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">llvm/Support/BinaryStreamRef.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab83ec07611d87158d4858519e507a973">slice</a> (uint64_t Off, uint64_t Size) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee6463dc56686cedc45c6ffbdf982854">drop_front</a> (uint64_t N) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e872383f7bcc3fa4147128e58faa9d">keep_front</a> (uint64_t N) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a>, <a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a279d1ec7e06ccdf0e4e373ac53961c0e">split</a> (uint64_t Off) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38d3fbef06b67cad0ad4bffceadb17a7">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8fc7f16d8fb731fe9c08de262e1af28">empty</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a76f93d0ed241960268594a52faf9f0">Offset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f1c066ed5746fba7a6c07552c84713">StreamData</a></td>
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


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### drop\_front() {#aee6463dc56686cedc45c6ffbdf982854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef llvm::BinarySubstreamRef::drop_front (uint64_t N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a38d3fbef06b67cad0ad4bffceadb17a7">size</a> and <a href="#ab83ec07611d87158d4858519e507a973">slice</a>.</p>


<p>Referenced by <a href="#a279d1ec7e06ccdf0e4e373ac53961c0e">split</a>.</p>

</div>
</div>

### empty() {#aa8fc7f16d8fb731fe9c08de262e1af28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BinarySubstreamRef::empty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Reference <a href="#a38d3fbef06b67cad0ad4bffceadb17a7">size</a>.</p>

</div>
</div>

### keep\_front() {#a92e872383f7bcc3fa4147128e58faa9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef llvm::BinarySubstreamRef::keep_front (uint64_t N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ab83ec07611d87158d4858519e507a973">slice</a>.</p>


<p>Referenced by <a href="#a279d1ec7e06ccdf0e4e373ac53961c0e">split</a>.</p>

</div>
</div>

### size() {#a38d3fbef06b67cad0ad4bffceadb17a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BinarySubstreamRef::size ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Reference <a href="#ad1f1c066ed5746fba7a6c07552c84713">StreamData</a>.</p>


<p>Referenced by <a href="#aee6463dc56686cedc45c6ffbdf982854">drop_front</a> and <a href="#aa8fc7f16d8fb731fe9c08de262e1af28">empty</a>.</p>

</div>
</div>

### slice() {#ab83ec07611d87158d4858519e507a973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef llvm::BinarySubstreamRef::slice (uint64_t Off, uint64_t Size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a1a76f93d0ed241960268594a52faf9f0">Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#ad1f1c066ed5746fba7a6c07552c84713">StreamData</a>.</p>


<p>Referenced by <a href="#aee6463dc56686cedc45c6ffbdf982854">drop_front</a> and <a href="#a92e872383f7bcc3fa4147128e58faa9d">keep_front</a>.</p>

</div>
</div>

### split() {#a279d1ec7e06ccdf0e4e373ac53961c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; BinarySubstreamRef, BinarySubstreamRef &gt; llvm::BinarySubstreamRef::split (uint64_t Off)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#aee6463dc56686cedc45c6ffbdf982854">drop_front</a> and <a href="#a92e872383f7bcc3fa4147128e58faa9d">keep_front</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Offset {#a1a76f93d0ed241960268594a52faf9f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BinarySubstreamRef::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/lineprinter/#a37bafcfeb658e650c7c5841e0badc421">llvm::pdb::LinePrinter::formatMsfStreamData</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/lineprinter/#a6060a150c1da2417e904c7ce98eb1297">llvm::pdb::LinePrinter::formatMsfStreamData</a> and <a href="#ab83ec07611d87158d4858519e507a973">slice</a>.</p>

</div>
</div>

### StreamData {#ad1f1c066ed5746fba7a6c07552c84713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef llvm::BinarySubstreamRef::StreamData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/lineprinter/#a37bafcfeb658e650c7c5841e0badc421">llvm::pdb::LinePrinter::formatMsfStreamData</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/lineprinter/#a6060a150c1da2417e904c7ce98eb1297">llvm::pdb::LinePrinter::formatMsfStreamData</a>, <a href="#a38d3fbef06b67cad0ad4bffceadb17a7">size</a> and <a href="#ab83ec07611d87158d4858519e507a973">slice</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
