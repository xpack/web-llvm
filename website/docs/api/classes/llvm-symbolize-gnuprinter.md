---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/symbolize/gnuprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GNUPrinter` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::symbolize::GNUPrinter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/diprinter-h">llvm/DebugInfo/Symbolize/DIPrinter.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase">PlainPrinterBase</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69dbcfadd20ce4148b46b572605c9cd">GNUPrinter</a> (raw_ostream &amp;OS, ErrorHandler EH, PrinterConfig &amp;Config)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f4354364f7489b99000a1c0395bf79">printSimpleLocation</a> (StringRef Filename, const DILineInfo &amp;Info) override</td>
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


<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/diprinter-h">DIPrinter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GNUPrinter() {#aa69dbcfadd20ce4148b46b572605c9cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::symbolize::GNUPrinter::GNUPrinter (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#ac67f275b2f972109d61404aa31a1e919">ErrorHandler</a> EH, <a href="/web-llvm/docs/api/structs/llvm/symbolize/printerconfig">PrinterConfig</a> &amp; Config)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/diprinter-h">DIPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#affbf9407a119ebebac9dbf9af8a40e84">llvm::symbolize::PlainPrinterBase::Config</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#afb39ae511d18027fef991ffa36451221">llvm::symbolize::PlainPrinterBase::OS</a> and <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#a3530621e53d751ebd7417db46a0d9c42">llvm::symbolize::PlainPrinterBase::PlainPrinterBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### printSimpleLocation() {#ab0f4354364f7489b99000a1c0395bf79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::symbolize::GNUPrinter::printSimpleLocation (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/diprinter-h">DIPrinter.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/diprinter-cpp">DIPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/diprinter-h">DIPrinter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/diprinter-cpp">DIPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
