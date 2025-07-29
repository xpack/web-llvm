---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinterdwarf-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AsmPrinterDwarf.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/asmprinter-h">llvm/CodeGen/AsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">llvm/CodeGen/DIE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">llvm/MC/MCSection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetloweringobjectfile-h">llvm/Target/TargetLoweringObjectFile.h</a>"
#include &lt;cstdint&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49c57cc9c3736b08ea2276ff9b38b4eb">DecodeDWARFEncoding</a> (unsigned Encoding)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"asm-printer"</td>
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

## Functions

### DecodeDWARFEncoding() {#a49c57cc9c3736b08ea2276ff9b38b4eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * DecodeDWARFEncoding (unsigned Encoding)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinterdwarf-cpp">AsmPrinterDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab8bb265a153372d87860f6a33d858f3e">llvm::dwarf::DW_EH_PE_absptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a0e91cc214494d9c9f9c8adcf03be6e51">llvm::dwarf::DW_EH_PE_datarel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ac859bd9ec26a2398dd13f4f9262f0595">llvm::dwarf::DW_EH_PE_indirect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255af88641d07cb5fdb688ad0d4e78314222">llvm::dwarf::DW_EH_PE_omit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a18cb02c6dc96569494f65b82ab70487b">llvm::dwarf::DW_EH_PE_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a68bcc7d64ea60cf76503e913360e0b01">llvm::dwarf::DW_EH_PE_sdata4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab4f228eae8e91cb5eb218c4372d2cd75">llvm::dwarf::DW_EH_PE_sdata8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255acdcf9e337d25fb5063bf168d12c0e9fd">llvm::dwarf::DW_EH_PE_sleb128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255abfafdba601fd5cab55113f2cdb96c033">llvm::dwarf::DW_EH_PE_udata4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ac75ce7ce2df1136a194d4cd1d889c06a">llvm::dwarf::DW_EH_PE_udata8</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ac78bfa2d0d61171586536bd55b3919f9">llvm::dwarf::DW_EH_PE_uleb128</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a7e3748343e023dd0c34b09ad64cf6377">llvm::AsmPrinter::emitEncodingByte</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"asm-printer"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinterdwarf-cpp">AsmPrinterDwarf.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
