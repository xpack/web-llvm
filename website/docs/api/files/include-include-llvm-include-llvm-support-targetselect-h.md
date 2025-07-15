---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/support/targetselect-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `TargetSelect.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "llvm/Config/llvm-config.h"
#include "llvm/Config/Targets.def"
#include "llvm/Config/AsmPrinters.def"
#include "llvm/Config/AsmParsers.def"
#include "llvm/Config/Disassemblers.def"
#include "llvm/Config/TargetMCAs.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ebd56af9d9a81e25690bfb8f503bd5">LLVM_TARGET</a>(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##TargetInfo();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ebd56af9d9a81e25690bfb8f503bd5">LLVM_TARGET</a>(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##Target();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ebd56af9d9a81e25690bfb8f503bd5">LLVM_TARGET</a>(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##TargetMC();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1184b0ccd804ec381a8740ff580103b">LLVM_ASM_PRINTER</a>(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##AsmPrinter();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b8ec1332a57ea67e49ca9475785d829">LLVM_ASM_PARSER</a>(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##AsmParser();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc2ca2130e75e7cf2a0bb5884505fa39">LLVM_DISASSEMBLER</a>(TargetName)&nbsp;&nbsp;&nbsp;  void LLVMInitialize##TargetName##Disassembler();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab17838ffb753b1c97dfb412e10fa2036">LLVM_TARGETMCA</a>(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##TargetMCA();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ebd56af9d9a81e25690bfb8f503bd5">LLVM_TARGET</a>(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##TargetInfo();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ebd56af9d9a81e25690bfb8f503bd5">LLVM_TARGET</a>(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##Target();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ebd56af9d9a81e25690bfb8f503bd5">LLVM_TARGET</a>(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##TargetMC();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1184b0ccd804ec381a8740ff580103b">LLVM_ASM_PRINTER</a>(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##AsmPrinter();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b8ec1332a57ea67e49ca9475785d829">LLVM_ASM_PARSER</a>(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##AsmParser();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc2ca2130e75e7cf2a0bb5884505fa39">LLVM_DISASSEMBLER</a>(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##Disassembler();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab17838ffb753b1c97dfb412e10fa2036">LLVM_TARGETMCA</a>(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##TargetMCA();</td>
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

## Macro Definitions

### LLVM\_ASM\_PARSER {#a9b8ec1332a57ea67e49ca9475785d829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ASM_PARSER(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##AsmParser();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_ASM\_PARSER {#a9b8ec1332a57ea67e49ca9475785d829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ASM_PARSER(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##AsmParser();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_ASM\_PRINTER {#ad1184b0ccd804ec381a8740ff580103b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ASM_PRINTER(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##AsmPrinter();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_ASM\_PRINTER {#ad1184b0ccd804ec381a8740ff580103b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ASM_PRINTER(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##AsmPrinter();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_DISASSEMBLER {#abc2ca2130e75e7cf2a0bb5884505fa39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_DISASSEMBLER(TargetName)&nbsp;&nbsp;&nbsp;  void LLVMInitialize##TargetName##Disassembler();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_DISASSEMBLER {#abc2ca2130e75e7cf2a0bb5884505fa39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_DISASSEMBLER(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##Disassembler();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_TARGET {#a59ebd56af9d9a81e25690bfb8f503bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_TARGET(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##TargetInfo();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_TARGET {#a59ebd56af9d9a81e25690bfb8f503bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_TARGET(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##Target();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_TARGET {#a59ebd56af9d9a81e25690bfb8f503bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_TARGET(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##TargetMC();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_TARGET {#a59ebd56af9d9a81e25690bfb8f503bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_TARGET(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##TargetInfo();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_TARGET {#a59ebd56af9d9a81e25690bfb8f503bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_TARGET(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##Target();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_TARGET {#a59ebd56af9d9a81e25690bfb8f503bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_TARGET(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##TargetMC();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_TARGETMCA {#ab17838ffb753b1c97dfb412e10fa2036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_TARGETMCA(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##TargetMCA();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

### LLVM\_TARGETMCA {#ab17838ffb753b1c97dfb412e10fa2036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_TARGETMCA(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##TargetMCA();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">TargetSelect.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
