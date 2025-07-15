---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/symbolize/request
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Request` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::symbolize::Request { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/diprinter-h">llvm/DebugInfo/Symbolize/DIPrinter.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f33064ef397b8459aed69fbec6678dd">ModuleName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83c781c64952d6872733020df238024c">Address</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28fbc3b40283db46d112cdd6a4483c3c">Symbol</a></td>
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


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/diprinter-h">DIPrinter.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Address {#a83c781c64952d6872733020df238024c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::symbolize::Request::Address</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/diprinter-h">DIPrinter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#a7f435370eac27a8d71d7ec885910bf0b">llvm::symbolize::PlainPrinterBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#a6bff6c70586253ff2ff4384e22e4055d">llvm::symbolize::PlainPrinterBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#a9eceb285970ae32b1492fe2ad2e7462d">llvm::symbolize::PlainPrinterBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#abf95e7e26e59bb529cc62cbf06285524">llvm::symbolize::PlainPrinterBase::print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#a865e83348693ae24ada91964c6da76e4">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

### ModuleName {#a4f33064ef397b8459aed69fbec6678dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::symbolize::Request::ModuleName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/diprinter-h">DIPrinter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#a34d548e5b8beb93beda1d1d8b7966ac9">llvm::symbolize::PlainPrinterBase::printError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#a865e83348693ae24ada91964c6da76e4">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

### Symbol {#a28fbc3b40283db46d112cdd6a4483c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::symbolize::Request::Symbol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/diprinter-h">DIPrinter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#a865e83348693ae24ada91964c6da76e4">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/diprinter-h">DIPrinter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
