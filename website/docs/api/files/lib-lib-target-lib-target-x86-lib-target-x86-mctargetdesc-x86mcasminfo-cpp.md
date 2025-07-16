---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mcasminfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `X86MCAsmInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mcasminfo-h">X86MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AsmWriterFlavorTy { <a href="#a4b03ac9ad021493fa239610fa246f195">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#a4b03ac9ad021493fa239610fa246f195">AsmWriterFlavorTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfcba1948fcf2b57dc5b2c7de1783018">X86AsmSyntax</a>("x86-asm-syntax", cl::init(ATT), cl::Hidden, cl::desc("Select the assembly style for input"), cl::values(clEnumValN(ATT, "att", "Emit AT&T-style assembly"), clEnumValN(Intel, "intel", "Emit Intel-style assembly")))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d4d245812841c4a9049ffebfcbd007e">MarkedJTDataRegions</a>("mark-data-regions", cl::init(true), cl::desc("Mark code section jump table data regions."), cl::Hidden)</td>
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

### AsmWriterFlavorTy {#a4b03ac9ad021493fa239610fa246f195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum AsmWriterFlavorTy </td>
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
<td class="doxyEnumItemName">ATT<a id="a4b03ac9ad021493fa239610fa246f195afa8c6c6fdc929db5eb1cab7e6693619f"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Intel<a id="a4b03ac9ad021493fa239610fa246f195a8bdd46a005182f6bb046e0e134efcb02"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mcasminfo-cpp">X86MCAsmInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### MarkedJTDataRegions {#a1d4d245812841c4a9049ffebfcbd007e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; MarkedJTDataRegions("mark-data-regions", cl::init(true), cl::desc("Mark code section jump table data regions."), cl::Hidden)</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mcasminfo-cpp">X86MCAsmInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86mcasminfodarwin/#a663f0b08ec61baaf51e6d1eec2b203f3">llvm::X86MCAsmInfoDarwin::X86MCAsmInfoDarwin</a>.</p>

</div>
</div>

### X86AsmSyntax {#abfcba1948fcf2b57dc5b2c7de1783018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; AsmWriterFlavorTy &gt; X86AsmSyntax("x86-asm-syntax", cl::init(ATT), cl::Hidden, cl::desc("Select the assembly style for input"), cl::values(clEnumValN(ATT, "att", "Emit AT&amp;T-style assembly"), clEnumValN(Intel, "intel", "Emit Intel-style assembly")))</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mcasminfo-cpp">X86MCAsmInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86elfmcasminfo/#a5f6bae7216b6b398d914b41530622c01">llvm::X86ELFMCAsmInfo::X86ELFMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86mcasminfodarwin/#a663f0b08ec61baaf51e6d1eec2b203f3">llvm::X86MCAsmInfoDarwin::X86MCAsmInfoDarwin</a>, <a href="/web-llvm/docs/api/classes/llvm/x86mcasminfognucoff/#a962aeeaf657c538ec248271056d017ec">llvm::X86MCAsmInfoGNUCOFF::X86MCAsmInfoGNUCOFF</a> and <a href="/web-llvm/docs/api/classes/llvm/x86mcasminfomicrosoft/#ac3d14e522888ac8ead6f614968a86899">llvm::X86MCAsmInfoMicrosoft::X86MCAsmInfoMicrosoft</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
