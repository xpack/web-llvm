---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcasminfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AArch64MCAsmInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcasminfo-h">AArch64MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AsmWriterVariantTy { <a href="#ad9974102ac4ab550bae0600eca728899">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#ad9974102ac4ab550bae0600eca728899">AsmWriterVariantTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa964c28fae9abfdf54ceee51655a8c80">AsmWriterVariant</a>("aarch64-neon-syntax", cl::init(Default), cl::desc("Choose style of NEON code to emit from AArch64 backend:"), cl::values(clEnumValN(Generic, "generic", "Emit generic NEON assembly"), clEnumValN(Apple, "apple", "Emit Apple-style NEON assembly")))</td>
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

### AsmWriterVariantTy {#ad9974102ac4ab550bae0600eca728899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum AsmWriterVariantTy </td>
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
<td class="doxyEnumItemName">Default<a id="ad9974102ac4ab550bae0600eca728899a79935518a3889663d8688b6b01fff051"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Generic<a id="ad9974102ac4ab550bae0600eca728899a9683fc965be285edded4502f972f9d19"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Apple<a id="ad9974102ac4ab550bae0600eca728899afa7ceceb64a6890f8421f695dc71a399"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcasminfo-cpp">AArch64MCAsmInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AsmWriterVariant {#aa964c28fae9abfdf54ceee51655a8c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; AsmWriterVariantTy &gt; AsmWriterVariant("aarch64-neon-syntax", cl::init(Default), cl::desc("Choose style of NEON code to emit from AArch64 backend:"), cl::values(clEnumValN(Generic, "generic", "Emit generic NEON assembly"), clEnumValN(Apple, "apple", "Emit Apple-style NEON assembly")))</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcasminfo-cpp">AArch64MCAsmInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aarch64mcasminfodarwin/#a6cb91eeac20ffd0f37f3c081aa2aae73">llvm::AArch64MCAsmInfoDarwin::AArch64MCAsmInfoDarwin</a> and <a href="/web-llvm/docs/api/structs/llvm/aarch64mcasminfoelf/#ae8fd55f5abc57f7095a727e9ae4b23ee">llvm::AArch64MCAsmInfoELF::AArch64MCAsmInfoELF</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
