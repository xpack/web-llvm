---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/lto/symbolresolution
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SymbolResolution` Struct Reference

<p>The resolution for a symbol. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::lto::SymbolResolution { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">llvm/LTO/LTO.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcbf60331a53339261d2ec8080d95748">SymbolResolution</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61e14815eb907619ac67d15a4cf569c9">Prevailing</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The linker has chosen this definition of the symbol. <a href="#a61e14815eb907619ac67d15a4cf569c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a265afe9113e2a15b2b6346e52bc9b0dd">FinalDefinitionInLinkageUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The definition of this symbol is unpreemptable at runtime and is known to be in this linkage unit. <a href="#a265afe9113e2a15b2b6346e52bc9b0dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb3e0896a781c723c79fb33d9cd100b">VisibleToRegularObj</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The definition of this symbol is visible outside of the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> unit. <a href="#accb3e0896a781c723c79fb33d9cd100b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d7d11866406ec8debc4b5929006fe7">ExportDynamic</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The symbol was exported dynamically, and therefore could be referenced by a shared library not visible to the linker. <a href="#a46d7d11866406ec8debc4b5929006fe7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93ee267ff61f467091d1cde5f7b13543">LinkerRedefined</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/linker">Linker</a> redefined version of the symbol which appeared in -wrap or -defsym linker option. <a href="#a93ee267ff61f467091d1cde5f7b13543">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The resolution for a symbol.</p>


<p>The linker must provide a <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution">SymbolResolution</a> for each global symbol based on its internal resolution of that symbol.</p>


<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SymbolResolution() {#adcbf60331a53339261d2ec8080d95748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::lto::SymbolResolution::SymbolResolution ()</td>
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



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>References <a href="#a46d7d11866406ec8debc4b5929006fe7">ExportDynamic</a>, <a href="#a265afe9113e2a15b2b6346e52bc9b0dd">FinalDefinitionInLinkageUnit</a>, <a href="#a93ee267ff61f467091d1cde5f7b13543">LinkerRedefined</a>, <a href="#a61e14815eb907619ac67d15a4cf569c9">Prevailing</a> and <a href="#accb3e0896a781c723c79fb33d9cd100b">VisibleToRegularObj</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ExportDynamic {#a46d7d11866406ec8debc4b5929006fe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::lto::SymbolResolution::ExportDynamic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The symbol was exported dynamically, and therefore could be referenced by a shared library not visible to the linker.</p>

<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lto/lto/#ada5eca1803d5afcb1005ea05ffc62636">llvm::lto::LTO::run</a> and <a href="#adcbf60331a53339261d2ec8080d95748">SymbolResolution</a>.</p>

</div>
</div>

### FinalDefinitionInLinkageUnit {#a265afe9113e2a15b2b6346e52bc9b0dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::lto::SymbolResolution::FinalDefinitionInLinkageUnit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The definition of this symbol is unpreemptable at runtime and is known to be in this linkage unit.</p>

<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="#adcbf60331a53339261d2ec8080d95748">SymbolResolution</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a2b96fb8bf782a1b498a82682ab8e74c9">writeToResolutionFile</a>.</p>

</div>
</div>

### LinkerRedefined {#a93ee267ff61f467091d1cde5f7b13543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::lto::SymbolResolution::LinkerRedefined</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/linker">Linker</a> redefined version of the symbol which appeared in -wrap or -defsym linker option.</p>

<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="#adcbf60331a53339261d2ec8080d95748">SymbolResolution</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a2b96fb8bf782a1b498a82682ab8e74c9">writeToResolutionFile</a>.</p>

</div>
</div>

### Prevailing {#a61e14815eb907619ac67d15a4cf569c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::lto::SymbolResolution::Prevailing</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The linker has chosen this definition of the symbol.</p>

<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lto/lto/#ada5eca1803d5afcb1005ea05ffc62636">llvm::lto::LTO::run</a>, <a href="#adcbf60331a53339261d2ec8080d95748">SymbolResolution</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a2b96fb8bf782a1b498a82682ab8e74c9">writeToResolutionFile</a>.</p>

</div>
</div>

### VisibleToRegularObj {#accb3e0896a781c723c79fb33d9cd100b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::lto::SymbolResolution::VisibleToRegularObj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The definition of this symbol is visible outside of the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> unit.</p>

<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="#adcbf60331a53339261d2ec8080d95748">SymbolResolution</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a2b96fb8bf782a1b498a82682ab8e74c9">writeToResolutionFile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
