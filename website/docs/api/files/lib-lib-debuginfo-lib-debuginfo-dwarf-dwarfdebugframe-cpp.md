---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DWARFDebugFrame.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">llvm/DebugInfo/DWARF/DWARFDebugFrame.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">llvm/DebugInfo/DIContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">llvm/DebugInfo/DWARF/DWARFDataExtractor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">llvm/Support/DataExtractor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cinttypes&gt;
#include &lt;cstdint&gt;
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5658f96977b9cb1730425f3ca3cb305c">printRegister</a> (raw_ostream &amp;OS, DIDumpOptions DumpOpts, unsigned RegNum)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace5b584bcb0d5aaf091c8f1e0997d32e">getCIEId</a> (bool IsDWARF64, bool IsEH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e25fc51f7806df57464873f1323c074">dumpDataAux</a> (DataExtractor Data, uint64_t Offset, int Length)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082def4defe01bb3252978d8397e55cb">DWARF_CFI_PRIMARY_OPCODE_MASK</a> = 0xc0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64a1cab6149761d626c59f02bb40cff8">DWARF_CFI_PRIMARY_OPERAND_MASK</a> = 0x3f</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3910c994235e84cbacbe9e41e74b50f">ENUM_TO_CSTR</a>(e)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82065d491250f10c7cd4be1e1c946362">DECLARE_OP3</a>(OP, OPTYPE0, OPTYPE1, OPTYPE2)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a857a787a2b181a8ef0b7378d3acfb9b7">DECLARE_OP2</a>(OP, OPTYPE0, OPTYPE1)&nbsp;&nbsp;&nbsp;  <a href="#a82065d491250f10c7cd4be1e1c946362">DECLARE_OP3</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, OPTYPE0, OPTYPE1, OT_None)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf79ae72558434658c4de2fb888ca300">DECLARE_OP1</a>(OP, OPTYPE0)&nbsp;&nbsp;&nbsp;<a href="#a857a787a2b181a8ef0b7378d3acfb9b7">DECLARE_OP2</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, OPTYPE0, OT_None)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ddf7d4f4ce481d7ecba948362b9837e">DECLARE_OP0</a>(OP)&nbsp;&nbsp;&nbsp;<a href="#abf79ae72558434658c4de2fb888ca300">DECLARE_OP1</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, OT_None)</td>
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

### dumpDataAux() {#a0e25fc51f7806df57464873f1323c074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVM_ATTRIBUTE_UNUSED dumpDataAux (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> Data, uint64_t Offset, int Length)</td>
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



<p>Definition at line 1058 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a37b5dd8a8b82f2818e0f4ea9699d8ae5">llvm::raw_ostream::write_hex</a>.</p>

</div>
</div>

### getCIEId() {#ace5b584bcb0d5aaf091c8f1e0997d32e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getCIEId (bool IsDWARF64, bool IsEH)</td>
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



<p>Definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a2d5ea8ed8f8ff79c7b1844d329b22ebe">llvm::dwarf::DW64_CIE_ID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a0a2cfb047bef74739998077d46fb6ccb">llvm::dwarf::DW_CIE_ID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie/#ad37449ab3df9cdf881d320defb0a9c20">llvm::dwarf::CIE::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe/#a4f2d81fc8d21674863d5a753df3eed54">llvm::DWARFDebugFrame::parse</a>.</p>

</div>
</div>

### printRegister() {#a5658f96977b9cb1730425f3ca3cb305c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printRegister (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts, unsigned RegNum)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#abcc02a97a7033bc1db45cd841ed4fc4e">llvm::DIDumpOptions::GetNameForDWARFReg</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a2673e3b3e2b201c2afe1fdcf192d2df8">llvm::DIDumpOptions::IsEH</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf/registerlocations/#a9c39cfdfa887c321e9214515c8654867">llvm::dwarf::RegisterLocations::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation/#a9122a6af9ddf36a3a65346fe19ff520c">llvm::dwarf::UnwindLocation::dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DWARF\_CFI\_PRIMARY\_OPCODE\_MASK {#a082def4defe01bb3252978d8397e55cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t DWARF_CFI_PRIMARY_OPCODE_MASK = 0xc0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf/cfiprogram/#a631c5e6e71bc6c396be7fab58d959bf1">llvm::dwarf::CFIProgram::parse</a>.</p>

</div>
</div>

### DWARF\_CFI\_PRIMARY\_OPERAND\_MASK {#a64a1cab6149761d626c59f02bb40cff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t DWARF_CFI_PRIMARY_OPERAND_MASK = 0x3f</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf/cfiprogram/#a631c5e6e71bc6c396be7fab58d959bf1">llvm::dwarf::CFIProgram::parse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DECLARE\_OP0 {#a9ddf7d4f4ce481d7ecba948362b9837e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECLARE_OP0(OP)&nbsp;&nbsp;&nbsp;<a href="#abf79ae72558434658c4de2fb888ca300">DECLARE_OP1</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, OT_None)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>

</div>
</div>

### DECLARE\_OP1 {#abf79ae72558434658c4de2fb888ca300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECLARE_OP1(OP, OPTYPE0)&nbsp;&nbsp;&nbsp;<a href="#a857a787a2b181a8ef0b7378d3acfb9b7">DECLARE_OP2</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, OPTYPE0, OT_None)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>

</div>
</div>

### DECLARE\_OP2 {#a857a787a2b181a8ef0b7378d3acfb9b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECLARE_OP2(OP, OPTYPE0, OPTYPE1)&nbsp;&nbsp;&nbsp;  <a href="#a82065d491250f10c7cd4be1e1c946362">DECLARE_OP3</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, OPTYPE0, OPTYPE1, OT_None)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 836 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>

</div>
</div>

### DECLARE\_OP3 {#a82065d491250f10c7cd4be1e1c946362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECLARE_OP3(OP, OPTYPE0, OPTYPE1, OPTYPE2)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
    OpTypes[<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>][0] = OPTYPE0;                                                  \
    OpTypes[<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>][1] = OPTYPE1;                                                  \
    OpTypes[<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>][2] = OPTYPE2;                                                  \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (false)
</div>
</dd>
</dl>

<p>Definition at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>

</div>
</div>

### ENUM\_TO\_CSTR {#ab3910c994235e84cbacbe9e41e74b50f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENUM_TO_CSTR(e)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case e:                                                                      \
    return #e;
</div>
</dd>
</dl>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
