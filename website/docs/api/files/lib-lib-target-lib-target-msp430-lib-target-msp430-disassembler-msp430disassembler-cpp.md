---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MSP430Disassembler.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430mctargetdesc-h">MCTargetDesc/MSP430MCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430-h">MSP430.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/targetinfo/msp430targetinfo-h">TargetInfo/MSP430TargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdecoderops-h">llvm/MC/MCDecoderOps.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcdisassembler-h">llvm/MC/MCDisassembler/MCDisassembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include "MSP430GenDisassemblerTables.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-msp430disassembler-cpp-">anonymous{MSP430Disassembler.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-msp430disassembler-cpp-/msp430disassembler">MSP430Disassembler</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AddrMode { <a href="#abf132b4ad93f3557cd3956577592ba68">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d7192c2b8c0b26481cdc9cfa4410b7">createMSP430Disassembler</a> (const Target &amp;T, const MCSubtargetInfo &amp;STI, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d7efe5f6d2d6b3e091d245b621d4450">LLVMInitializeMSP430Disassembler</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb5083d3a9cb1e5815522d223c250a9">DecodeGR8RegisterClass</a> (MCInst &amp;MI, uint64_t RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af008c2190b43cc0f7b777e6efe35d894">DecodeGR16RegisterClass</a> (MCInst &amp;MI, uint64_t RegNo, uint64_t Address, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f423a151ce5211498829397377eb6c7">DecodeCGImm</a> (MCInst &amp;MI, uint64_t Bits, uint64_t Address, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7805e638ecb28d944b73a8227e16b323">DecodeMemOperand</a> (MCInst &amp;MI, uint64_t Bits, uint64_t Address, const MCDisassembler *Decoder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#abf132b4ad93f3557cd3956577592ba68">AddrMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa64e3a23a2e3eb172b3bdb4d97476389">DecodeSrcAddrMode</a> (unsigned Rs, unsigned As)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#abf132b4ad93f3557cd3956577592ba68">AddrMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6a2ae26f914b45d5d1e18c54692e566">DecodeSrcAddrModeI</a> (unsigned Insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#abf132b4ad93f3557cd3956577592ba68">AddrMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a857781b83f8088fb6abc1672c5600ec8">DecodeSrcAddrModeII</a> (unsigned Insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#abf132b4ad93f3557cd3956577592ba68">AddrMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9720d794b7199e7641e9934ba9c4ab7c">DecodeDstAddrMode</a> (unsigned Insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86a2c12332629ece06b7408340732354">getDecoderTable</a> (AddrMode SrcAM, unsigned Words)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/msp430cc/#a6555a8cd40e2bd0785c314612cca2f78">MSP430CC::CondCodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa07fe2265bce961279f7e11bb2f4408">getCondCode</a> (unsigned Cond)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba5482bf616cf2565be879e1a2573bb3">GR8DecoderTable</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b04a3cdc6d9bcd22e1e8cf23ac563d">GR16DecoderTable</a>[] = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"msp430-disassembler"</td>
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

### AddrMode {#abf132b4ad93f3557cd3956577592ba68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum AddrMode </td>
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
<td class="doxyEnumItemName">amInvalid<a id="abf132b4ad93f3557cd3956577592ba68a2c2f799b1e70916bc010e3607553b36b"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">amRegister<a id="abf132b4ad93f3557cd3956577592ba68a53ae14ce8494ae8c5ae189aefe98ceba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">amIndexed<a id="abf132b4ad93f3557cd3956577592ba68af40d4be22427edf9c1538cab1e5f5c27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">amIndirect<a id="abf132b4ad93f3557cd3956577592ba68a252fdde2b0bdd5a210e75522e0c3df54"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">amIndirectPost<a id="abf132b4ad93f3557cd3956577592ba68ad1b8f03c0d97fea3a30a19ce749ed5c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">amSymbolic<a id="abf132b4ad93f3557cd3956577592ba68a5995cb8c315953976b240dff6b13b781"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">amImmediate<a id="abf132b4ad93f3557cd3956577592ba68a628d780dcf96a57c09753cc3f7dd34ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">amAbsolute<a id="abf132b4ad93f3557cd3956577592ba68a678047745d0c19afc2051acaa6272ee5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">amConstant<a id="abf132b4ad93f3557cd3956577592ba68a1ff8ef51af9bc284e7cc4197c3a8d414"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### createMSP430Disassembler() {#a99d7192c2b8c0b26481cdc9cfa4410b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDisassembler * createMSP430Disassembler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-msp430disassembler-cpp-/msp430disassembler/#af9a1ec6a67013d3b43bd0dbfa70e2bfd">anonymous{MSP430Disassembler.cpp}::MSP430Disassembler::MSP430Disassembler</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a5d7efe5f6d2d6b3e091d245b621d4450">LLVMInitializeMSP430Disassembler</a>.</p>

</div>
</div>

### DecodeCGImm() {#a4f423a151ce5211498829397377eb6c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeCGImm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, uint64_t Bits, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeDstAddrMode() {#a9720d794b7199e7641e9934ba9c4ab7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrMode DecodeDstAddrMode (unsigned Insn)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>References <a href="#abf132b4ad93f3557cd3956577592ba68a678047745d0c19afc2051acaa6272ee5">amAbsolute</a>, <a href="#abf132b4ad93f3557cd3956577592ba68af40d4be22427edf9c1538cab1e5f5c27">amIndexed</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a53ae14ce8494ae8c5ae189aefe98ceba">amRegister</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a5995cb8c315953976b240dff6b13b781">amSymbolic</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>.</p>

</div>
</div>

### DecodeGR16RegisterClass() {#af008c2190b43cc0f7b777e6efe35d894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeGR16RegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, uint64_t RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="#a61b04a3cdc6d9bcd22e1e8cf23ac563d">GR16DecoderTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>


<p>Referenced by <a href="#a7805e638ecb28d944b73a8227e16b323">DecodeMemOperand</a>.</p>

</div>
</div>

### DecodeGR8RegisterClass() {#acfb5083d3a9cb1e5815522d223c250a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeGR8RegisterClass (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, uint64_t RegNo, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="#aba5482bf616cf2565be879e1a2573bb3">GR8DecoderTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeMemOperand() {#a7805e638ecb28d944b73a8227e16b323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus DecodeMemOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, uint64_t Bits, uint64_t Address, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#af008c2190b43cc0f7b777e6efe35d894">DecodeGR16RegisterClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### DecodeSrcAddrMode() {#aa64e3a23a2e3eb172b3bdb4d97476389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrMode DecodeSrcAddrMode (unsigned Rs, unsigned As)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>References <a href="#abf132b4ad93f3557cd3956577592ba68a678047745d0c19afc2051acaa6272ee5">amAbsolute</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a1ff8ef51af9bc284e7cc4197c3a8d414">amConstant</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a628d780dcf96a57c09753cc3f7dd34ba">amImmediate</a>, <a href="#abf132b4ad93f3557cd3956577592ba68af40d4be22427edf9c1538cab1e5f5c27">amIndexed</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a252fdde2b0bdd5a210e75522e0c3df54">amIndirect</a>, <a href="#abf132b4ad93f3557cd3956577592ba68ad1b8f03c0d97fea3a30a19ce749ed5c8">amIndirectPost</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a2c2f799b1e70916bc010e3607553b36b">amInvalid</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a53ae14ce8494ae8c5ae189aefe98ceba">amRegister</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a5995cb8c315953976b240dff6b13b781">amSymbolic</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#aa6a2ae26f914b45d5d1e18c54692e566">DecodeSrcAddrModeI</a> and <a href="#a857781b83f8088fb6abc1672c5600ec8">DecodeSrcAddrModeII</a>.</p>

</div>
</div>

### DecodeSrcAddrModeI() {#aa6a2ae26f914b45d5d1e18c54692e566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrMode DecodeSrcAddrModeI (unsigned Insn)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>References <a href="#aa64e3a23a2e3eb172b3bdb4d97476389">DecodeSrcAddrMode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>.</p>

</div>
</div>

### DecodeSrcAddrModeII() {#a857781b83f8088fb6abc1672c5600ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrMode DecodeSrcAddrModeII (unsigned Insn)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>References <a href="#aa64e3a23a2e3eb172b3bdb4d97476389">DecodeSrcAddrMode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>.</p>

</div>
</div>

### getCondCode() {#aaa07fe2265bce961279f7e11bb2f4408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MSP430CC::CondCodes getCondCode (unsigned Cond)</td>
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



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/msp430cc/#a6555a8cd40e2bd0785c314612cca2f78a9ab0abab4103760114641549115f27c7">MSP430CC::COND_E</a>, <a href="/web-llvm/docs/api/namespaces/msp430cc/#a6555a8cd40e2bd0785c314612cca2f78aa8b4478689447a25948aa540cd992e43">MSP430CC::COND_GE</a>, <a href="/web-llvm/docs/api/namespaces/msp430cc/#a6555a8cd40e2bd0785c314612cca2f78adbc0037549976cc5edb58dfa29063cf6">MSP430CC::COND_HS</a>, <a href="/web-llvm/docs/api/namespaces/msp430cc/#a6555a8cd40e2bd0785c314612cca2f78a332aebe24667c7f27b767cf8cba3c7a6">MSP430CC::COND_L</a>, <a href="/web-llvm/docs/api/namespaces/msp430cc/#a6555a8cd40e2bd0785c314612cca2f78a253097e246f7e0fa3b9ee88ff3187881">MSP430CC::COND_LO</a>, <a href="/web-llvm/docs/api/namespaces/msp430cc/#a6555a8cd40e2bd0785c314612cca2f78a2d53e16543176aaf230ddb4d70cf5c9c">MSP430CC::COND_N</a>, <a href="/web-llvm/docs/api/namespaces/msp430cc/#a6555a8cd40e2bd0785c314612cca2f78ad1e5320e97965e267a708091630eace9">MSP430CC::COND_NE</a>, <a href="/web-llvm/docs/api/namespaces/msp430cc/#a6555a8cd40e2bd0785c314612cca2f78ac95cf630328150be101412e9fcabff90">MSP430CC::COND_NONE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a5120ff8db5e8098a3f9551e139d8aeaf">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addCondCodeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a03e3b195e9ccc3d8c840e87f0cba6dbc">anonymous{ARMAsmParser.cpp}::ARMOperand::addCondCodeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad43d0a6a64bad5f305bb9ad845bd2096">anonymous{ARMAsmParser.cpp}::ARMOperand::addITCondCodeInvOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac5e2c8aff96996ab20507dab30f9299b">anonymous{ARMAsmParser.cpp}::ARMOperand::addITCondCodeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a111c25050e3c0c1dba99fcaf29d84548">anonymous{ARMAsmParser.cpp}::ARMOperand::isITCondCodeNoAL</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a583eba48a3ce26d4761b231cb04fb21d">anonymous{ARMAsmParser.cpp}::ARMOperand::isITCondCodeRestrictedFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a2768f15506a91371b0792bc42d27a5f0">anonymous{ARMAsmParser.cpp}::ARMOperand::isITCondCodeRestrictedI</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af46c5d82d13aa99acbc055d2cfaed520">anonymous{ARMAsmParser.cpp}::ARMOperand::isITCondCodeRestrictedS</a> and <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aae5fadabfe6372150b5eaeefba81ad83">anonymous{ARMAsmParser.cpp}::ARMOperand::isITCondCodeRestrictedU</a>.</p>

</div>
</div>

### getDecoderTable() {#a86a2c12332629ece06b7408340732354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t * getDecoderTable (<a href="#abf132b4ad93f3557cd3956577592ba68">AddrMode</a> SrcAM, unsigned Words)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>References <a href="#abf132b4ad93f3557cd3956577592ba68a678047745d0c19afc2051acaa6272ee5">amAbsolute</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a1ff8ef51af9bc284e7cc4197c3a8d414">amConstant</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a628d780dcf96a57c09753cc3f7dd34ba">amImmediate</a>, <a href="#abf132b4ad93f3557cd3956577592ba68af40d4be22427edf9c1538cab1e5f5c27">amIndexed</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a252fdde2b0bdd5a210e75522e0c3df54">amIndirect</a>, <a href="#abf132b4ad93f3557cd3956577592ba68ad1b8f03c0d97fea3a30a19ce749ed5c8">amIndirectPost</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a53ae14ce8494ae8c5ae189aefe98ceba">amRegister</a>, <a href="#abf132b4ad93f3557cd3956577592ba68a5995cb8c315953976b240dff6b13b781">amSymbolic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### LLVMInitializeMSP430Disassembler() {#a5d7efe5f6d2d6b3e091d245b621d4450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeMSP430Disassembler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>References <a href="#a99d7192c2b8c0b26481cdc9cfa4410b7">createMSP430Disassembler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a43b03fb0b78d611b08a2db402b6a659f">llvm::getTheMSP430Target</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> and <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a8d3c3e977776517a7c1a82060b16da9f">llvm::TargetRegistry::RegisterMCDisassembler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### GR16DecoderTable {#a61b04a3cdc6d9bcd22e1e8cf23ac563d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned GR16DecoderTable[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  MSP430::PC,  MSP430::SP,  MSP430::SR,  MSP430::CG,
  <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a166646d6a4037a236119b6e156051d90">MSP430::R4</a>,  MSP430::R5,  <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#ace331bebb5bd2780b8dfb7e6e97db7dd">MSP430::R6</a>,  MSP430::R7,
  MSP430::R8,  MSP430::R9,  MSP430::R10, MSP430::R11,
  MSP430::R12, MSP430::R13, MSP430::R14, MSP430::R15
}
</div>
</dd>
</dl>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>Referenced by <a href="#af008c2190b43cc0f7b777e6efe35d894">DecodeGR16RegisterClass</a>.</p>

</div>
</div>

### GR8DecoderTable {#aba5482bf616cf2565be879e1a2573bb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned GR8DecoderTable[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  MSP430::PCB,  MSP430::SPB,  MSP430::SRB,  MSP430::CGB,
  MSP430::R4B,  MSP430::R5B,  MSP430::R6B,  MSP430::R7B,
  MSP430::R8B,  MSP430::R9B,  MSP430::R10B, MSP430::R11B,
  MSP430::R12B, MSP430::R13B, MSP430::R14B, MSP430::R15B
}
</div>
</dd>
</dl>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>


<p>Referenced by <a href="#acfb5083d3a9cb1e5815522d223c250a9">DecodeGR8RegisterClass</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"msp430-disassembler"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp">MSP430Disassembler.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
