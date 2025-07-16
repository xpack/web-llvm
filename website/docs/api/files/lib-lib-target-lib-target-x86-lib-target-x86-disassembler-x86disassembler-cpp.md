---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `X86Disassembler.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">MCTargetDesc/X86BaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">MCTargetDesc/X86MCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/targetinfo/x86targetinfo-h">TargetInfo/X86TargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcdisassembler-h">llvm/MC/MCDisassembler/MCDisassembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "X86GenDisassemblerTables.inc"
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Define some predicates that are used for node matching. <a href="/web-llvm/docs/api/namespaces/llvm/x86/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86disassembler-cpp-">anonymous{X86Disassembler.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/modrmdecision">ModRMDecision</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/opcodedecision">OpcodeDecision</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/contextdecision">ContextDecision</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86disassembler-cpp-/x86genericdisassembler">X86GenericDisassembler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic disassembler for all <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> platforms. <a href="/web-llvm/docs/api/classes/anonymous-x86disassembler-cpp-/x86genericdisassembler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a48739e7e428e4607c5699d7417498956">InstrUID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3686bdd912c0d40035aa66dcffb36da">decode</a> (OpcodeType type, InstructionContext insnContext, uint8_t opcode, uint8_t modRM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef79c7512f86471adf8452b0cf8e2f58">peek</a> (struct InternalInstruction *insn, uint8_t &amp;byte)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f02c7d98f9ea50a2abb5c2741c54f23">consume</a> (InternalInstruction *insn, T &amp;ptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ebe73b94309617db446535957bb7f50">isREX</a> (struct InternalInstruction *insn, uint8_t prefix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a111a978f64da66a01c6cfcb7c6374397">isREX2</a> (struct InternalInstruction *insn, uint8_t prefix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a> (struct InternalInstruction *insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d9a3ce3081e918d80b9770b584009a3">readSIB</a> (struct InternalInstruction *insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe4017d5eac03b4caf08ca7a36ba2723">readDisplacement</a> (struct InternalInstruction *insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a> (struct InternalInstruction *insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb1fcba65d61d145b053ee0217b3dee7">fixupReg</a> (struct InternalInstruction *insn, const struct OperandSpecifier *op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22cc5e803fedae95c7e1d22ffdb71cda">readOpcode</a> (struct InternalInstruction *insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e300d312f93aeb723f33f06e50673e">is16BitEquivalent</a> (const char *orig, const char *equiv)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a> (const char *name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a> (uint16_t *instructionID, struct InternalInstruction *insn, uint16_t attrMask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0572c45b7c999d1ef69cece322f0e1c">isCCMPOrCTEST</a> (InternalInstruction *insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bfeb1239d117ffbcde8064ef6fcc5a5">isNF</a> (InternalInstruction *insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a> (struct InternalInstruction *insn, const MCInstrInfo *mii)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab536506d0058cd6baa803890e9d648dd">readOpcodeRegister</a> (struct InternalInstruction *insn, uint8_t size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a771c0394a5e25fb07aaca2764eff8370">readImmediate</a> (struct InternalInstruction *insn, uint8_t size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8514fc80a87b940b85536ef125c05350">readVVVV</a> (struct InternalInstruction *insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7089b50e7c7846d5b312d0148c30b5f">readMaskRegister</a> (struct InternalInstruction *insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42be988af3ae0e352befa7189bd50936">readOperands</a> (struct InternalInstruction *insn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae99d82425a463a5dd5413112fda5ed17">translateInstruction</a> (MCInst &amp;mcInst, InternalInstruction &amp;insn, const MCDisassembler *Dis)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateInstruction - Translates an internal instruction and all its operands to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#ae99d82425a463a5dd5413112fda5ed17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06e3b1499180a2b92acc66f9203ac920">translateRegister</a> (MCInst &amp;mcInst, Reg reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateRegister - Translates an internal register to the appropriate LLVM register, and appends it as an operand to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#a06e3b1499180a2b92acc66f9203ac920">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a972b23f3658215b06333703a6099eeb1">translateSrcIndex</a> (MCInst &amp;mcInst, InternalInstruction &amp;insn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateSrcIndex - Appends a source index operand to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#a972b23f3658215b06333703a6099eeb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4094775b51be5196cd6a6a5254530d6c">translateDstIndex</a> (MCInst &amp;mcInst, InternalInstruction &amp;insn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateDstIndex - Appends a destination index operand to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#a4094775b51be5196cd6a6a5254530d6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409baefdf6be89e38deebefb129c1978">translateImmediate</a> (MCInst &amp;mcInst, uint64_t immediate, const OperandSpecifier &amp;operand, InternalInstruction &amp;insn, const MCDisassembler *Dis)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateImmediate - Appends an immediate operand to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#a409baefdf6be89e38deebefb129c1978">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea1e232218bf327acf353b1f07db2f86">translateRMRegister</a> (MCInst &amp;mcInst, InternalInstruction &amp;insn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateRMRegister - Translates a register stored in the R/M field of the ModR/M byte to its LLVM equivalent and appends it to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#aea1e232218bf327acf353b1f07db2f86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a> (MCInst &amp;mcInst, InternalInstruction &amp;insn, const MCDisassembler *Dis, bool ForceSIB=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateRMMemory - Translates a memory operand stored in the Mod and R/M fields of an internal instruction (and possibly its SIB byte) to a memory operand in LLVM's format, and appends it to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#ae82674c41a00b35f36f9ecf81932512e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aace6b74b8ffb4a67a94c8720813f18c2">translateRM</a> (MCInst &amp;mcInst, const OperandSpecifier &amp;operand, InternalInstruction &amp;insn, const MCDisassembler *Dis)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateRM - Translates an operand stored in the R/M (and possibly SIB) byte of an instruction to LLVM form, and appends it to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#aace6b74b8ffb4a67a94c8720813f18c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4baeecd8498cfd4ba890951058393621">translateFPRegister</a> (MCInst &amp;mcInst, uint8_t stackPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateFPRegister - Translates a stack position on the FPU stack to its LLVM form, and appends it to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#a4baeecd8498cfd4ba890951058393621">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a264ff5629dff4dc2a278f3848b4df">translateMaskRegister</a> (MCInst &amp;mcInst, uint8_t maskRegNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateMaskRegister - Translates a 3-bit mask register number to LLVM form, and appends it to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#a39a264ff5629dff4dc2a278f3848b4df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a> (MCInst &amp;mcInst, const OperandSpecifier &amp;operand, InternalInstruction &amp;insn, const MCDisassembler *Dis)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateOperand - Translates an operand stored in an internal instruction to LLVM's format and appends it to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#aeb806eaaca65c1a593f5af3078798819">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299465c500c452a6ee8ec8f87fec4200">createX86Disassembler</a> (const Target &amp;T, const MCSubtargetInfo &amp;STI, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a9a971b1d09709d73cab58157eaaf0637">LLVM_C_ABI</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad94a7ec0e2ddf818814c86ab2eca39f0">LLVMInitializeX86Disassembler</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a698bcd15212d3270393b6e3912b874f1">segmentRegnums</a>[SEG_OVERRIDE_max] = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"x86-disassembler"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0228f36529f75f692753ef96d725012">debug</a>(s)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>(dbgs() &lt;&lt; __LINE__ &lt;&lt; ": " &lt;&lt; s);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a556ad6d7ad3eb7fe546bb644b2ba41">GENERIC_FIXUP_FUNC</a>(name, base, prefix)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168a41dfc8e956c6180862aeca885db1">ENTRY</a>(x)&nbsp;&nbsp;&nbsp;X86::x,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dbab080ad769a5f716ded6e9f272748">ENTRY</a>(x)&nbsp;&nbsp;&nbsp;case EA_BASE_##x:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7afd582f1c8713d60dbff8569cb6f0b">ENTRY</a>(x)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2201f841c4c6a1aec7f1e04fb00b0cab">ENTRY</a>(x)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f201612cb32816265e25b6101b1f1e7">ENTRY</a>(x)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef1fa1f9600408331f991a35c71e628d">ENTRY</a>(x)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec82111a7fbe4a315c1177a90ccc5a3e">ENTRY</a>(x)&nbsp;&nbsp;&nbsp;case EA_REG_##x:</td>
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

### consume() {#a5f02c7d98f9ea50a2abb5c2741c54f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool consume (<a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn, T &amp; ptr)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a74bf20266f9a07d572e4ef494c29faf4">llvm::X86Disassembler::InternalInstruction::bytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#acfdf941f45bc58470ed8423b98862486">llvm::support::endian::read</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aa3b2f84ae751780dd417d7d59f235f3f">llvm::X86Disassembler::InternalInstruction::readerCursor</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a9c4b81107e8000eb718b029773322245">llvm::X86Disassembler::InternalInstruction::startLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a> and <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#ab3cc1c2c83fddd665c43fdc006f419f9">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePositiveInteger</a>.</p>

</div>
</div>

### createX86Disassembler() {#a299465c500c452a6ee8ec8f87fec4200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDisassembler * createX86Disassembler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ad94a7ec0e2ddf818814c86ab2eca39f0">LLVMInitializeX86Disassembler</a>.</p>

</div>
</div>

### decode() {#ab3686bdd912c0d40035aa66dcffb36da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrUID decode (<a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8e">OpcodeType</a> type, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a9624616e08932c8bf5b3a987e939f968">InstructionContext</a> insnContext, uint8_t opcode, uint8_t modRM)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/modrmdecision/#af6e56ed975e6969eb1baaf67e1119519">ModRMDecision::instructionIDs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea7c46af55213eba7d7104354bf073cbbe">llvm::X86Disassembler::MAP4</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a220b2f46f604cad58d418fb355d78865">MAP4_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea6934a4600c92849aec9b177ba29b95f7">llvm::X86Disassembler::MAP5</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#aeae838bb5a1c81d099c811f6348ca9df">MAP5_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea3168b0000bb711c5f33b0bc976272952">llvm::X86Disassembler::MAP6</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#ab695124c0e0dbddc8f1dbe567ee211de">MAP6_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea632479f320c04b5fc5d78d25d507b434">llvm::X86Disassembler::MAP7</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#aca2f331e9ce69df8e258199ea9c1f951">MAP7_SYM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a4bce531c2ed18d569a316029616e82f0">modFromModRM</a>, <a href="/web-llvm/docs/api/structs/modrmdecision/#a6c4ec8014e5927c67c5a0c9f0b9315aa">ModRMDecision::modrm_type</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eaf9d21d7b85f3134f59025667d1a87901">llvm::X86Disassembler::ONEBYTE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#ae053f9e80d644f47a6ee19185739162b">ONEBYTE_SYM</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a892daf9647ea098765cb833eb8596234">THREEBYTE38_SYM</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a6a9bb5a76c1dd6a02bb96ef407a6cb7d">THREEBYTE3A_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea326a3b9aff421046aeed72135f644612">llvm::X86Disassembler::THREEBYTE_38</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eaee435c44f7c8fb5577d8e247d86fe47f">llvm::X86Disassembler::THREEBYTE_3A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea0275a2adeb2bee7333ebddd77bc2dbe2">llvm::X86Disassembler::THREEDNOW_MAP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a4856eb908bad869295dd7568a8d735c1">THREEDNOW_MAP_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea4a57a751955088217dbec4ddde73a0d9">llvm::X86Disassembler::TWOBYTE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a0bfb472dc63adf5ea8919f054d4450e2">TWOBYTE_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eae2591c94eee2f2450337a7f76f0c4f35">llvm::X86Disassembler::XOP8_MAP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a73a6f64aec6a805d641a17c87a9d00b9">XOP8_MAP_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eaaf4fbb23ce6ffcb23876627445eb119c">llvm::X86Disassembler::XOP9_MAP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a349d73e2f39af064d9999d7780f9897d">XOP9_MAP_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea3fc124ba62a6f907eaa9253a4b0aa183">llvm::X86Disassembler::XOPA_MAP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a9df14d49cac592bc2e51794ad434e9b2">XOPA_MAP_SYM</a>.</p>


<p>Referenced by <a href="#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

### fixupReg() {#adb1fcba65d61d145b053ee0217b3dee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int fixupReg (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier">OperandSpecifier</a> * op)</td>
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



<p>Definition at line 868 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a3fd192bea7092fa66a95e4ca0cf236fe">CASE_ENCODING_RM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ae0228f36529f75f692753ef96d725012">debug</a>, <a href="#adb1fcba65d61d145b053ee0217b3dee7">fixupReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a0a0a664b4e04945bb7338a796271eaf7">llvm::X86Disassembler::MODE_64BIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a4bce531c2ed18d569a316029616e82f0">modFromModRM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78afd8e9c8ad31d8d77fbde6adfa808f8d4">llvm::X86Disassembler::TYPE_EVEX</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#acc1e56049a41a736160b7ed348bc7709">xFromEVEX2of4</a>.</p>


<p>Referenced by <a href="#adb1fcba65d61d145b053ee0217b3dee7">fixupReg</a> and <a href="#a42be988af3ae0e352befa7189bd50936">readOperands</a>.</p>

</div>
</div>

### getInstructionID() {#a201a8b01dbfadf977a0b7b16b14bcb29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getInstructionID (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> * mii)</td>
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



<p>Definition at line 1197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#abd318ed530c8fc71af093848beb0e2a9">aaaFromEVEX4of4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761a2cc98ac6cfff9525a9c517d58203abee">llvm::X86Disassembler::ATTR_64BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761ae76db82f3abbd861fe788a368d902e43">llvm::X86Disassembler::ATTR_ADSIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761a68d1c0efd3c5566345791f2e44a43874">llvm::X86Disassembler::ATTR_EVEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761abb2f873faafb26778dd88f53a8b0e3a3">llvm::X86Disassembler::ATTR_EVEXB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761ab0cfe5f1f7bae377cd3801519ca647a6">llvm::X86Disassembler::ATTR_EVEXK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761a195fabd1f33778497ed05370718fe0d9">llvm::X86Disassembler::ATTR_EVEXKZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761a95b4afd8b259682602966fa5c8206bbf">llvm::X86Disassembler::ATTR_EVEXL2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761ac4e663a6ca5c2fef0a020c592995391e">llvm::X86Disassembler::ATTR_EVEXNF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761a46799a13899b611916f13c2d157f6855">llvm::X86Disassembler::ATTR_EVEXU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761a521817f03b22ca3e9b694bbeb40ffc13">llvm::X86Disassembler::ATTR_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761a05118adcbdc4f3ebee3866375280e240">llvm::X86Disassembler::ATTR_OPSIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761a3fb7e2387d06f224bc1910dd8f34e5a3">llvm::X86Disassembler::ATTR_REX2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761ac4f7746f0e0278f882f6496bc332a0a7">llvm::X86Disassembler::ATTR_REXW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761aad13de5e7b76aca8e7d8dc6f737087ab">llvm::X86Disassembler::ATTR_VEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761ae9c5b2d19120317db54112e3d0af53f0">llvm::X86Disassembler::ATTR_VEXL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761ae7eba06f9636876052509d9c5f518daf">llvm::X86Disassembler::ATTR_XD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a6417cabaf5514433877aa0592985e761adbeb757d43fe751b0f290a3d49a549a2">llvm::X86Disassembler::ATTR_XS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a4521a330feb2823d5f0a83db8233186a">bFromEVEX4of4</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#abdbb44946a6951b5d90dd5313023156f">llvm::MCInstrInfo::getName</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a55cba166daaaf8da5569f173c900d5aa">llvm::X86Disassembler::InternalInstruction::hasAdSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a55fd804164f59f102d9cf3bec2bdec5c">llvm::X86Disassembler::InternalInstruction::hasOpSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#acc4b989b9e4750eeb9787809e0159054">llvm::X86Disassembler::InternalInstruction::instructionID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a62a3fc430e98f080dc7e39325d2b9e54">INSTRUCTIONS_SYM</a>, <a href="#ae4e300d312f93aeb723f33f06e50673e">is16BitEquivalent</a>, <a href="#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>, <a href="#ac0572c45b7c999d1ef69cece322f0e1c">isCCMPOrCTEST</a>, <a href="#a8bfeb1239d117ffbcde8064ef6fcc5a5">isNF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a05d1ee61cb5494166e335ff64d2cffa8">l2FromEVEX4of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a057966fda096251466bbdfda0b801081">lFromEVEX4of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a6886436df5f38bbed7d036a5d8cb44bf">lFromVEX2of2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#abf2fe87228fa8c1419f2a5f86baaa597">lFromVEX3of3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a63266a63baf54bef487061a728d12908">lFromXOP3of3</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#afc5dad7cd1e49271d0a0436b4fec0ab1">llvm::X86Disassembler::InternalInstruction::mandatoryPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea7c46af55213eba7d7104354bf073cbbe">llvm::X86Disassembler::MAP4</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#acec6e7f968f004123e55e6b2c04859f7">llvm::X86Disassembler::InternalInstruction::mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a92735b4f723ce305b1b618c0bafae971">llvm::X86Disassembler::MODE_16BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a0a0a664b4e04945bb7338a796271eaf7">llvm::X86Disassembler::MODE_64BIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a4bce531c2ed18d569a316029616e82f0">modFromModRM</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a10db75d3ff8f4c4f1d6ac8bcf960a585">llvm::X86Disassembler::InternalInstruction::modRM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eaf9d21d7b85f3134f59025667d1a87901">llvm::X86Disassembler::ONEBYTE</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a48eaa97ba6df31c9e0d5b60057b26cb3">llvm::X86Disassembler::InternalInstruction::opcode</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#af87363b191e81d22b3dfa0618628ed3e">llvm::X86Disassembler::InternalInstruction::opcodeType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a4a08eb3991a81513d973c4d1d70fd81b">ppFromEVEX3of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#adba38d038bb20114ef792961068aebd9">ppFromVEX2of2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#ac85472ee64d389babbd2c32deef16d89">ppFromVEX3of3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a91bdeef85650fa60106450fb24d9c500">ppFromXOP3of3</a>, <a href="#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#adc143cf4b45ac2f3084ad2481cd7856a">llvm::X86Disassembler::InternalInstruction::repeatPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a41d0e9e47665dc38d829804afd7f71e7">llvm::X86Disassembler::InternalInstruction::rex2ExtensionPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a800a1b50115e92e6d7762fab50cb5fd7">llvm::X86Disassembler::InternalInstruction::rexPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aac2dea60075f209cbef6ccf11f9829ba">llvm::X86Disassembler::InternalInstruction::spec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea326a3b9aff421046aeed72135f644612">llvm::X86Disassembler::THREEBYTE_38</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea4a57a751955088217dbec4ddde73a0d9">llvm::X86Disassembler::TWOBYTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78afd8e9c8ad31d8d77fbde6adfa808f8d4">llvm::X86Disassembler::TYPE_EVEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78ab831cfec071b3ebe687235b3ef5b96f9">llvm::X86Disassembler::TYPE_NO_VEX_XOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78a594bf13c39d9785f9603aad71559006b">llvm::X86Disassembler::TYPE_VEX_2B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78ad63c6ef1f04c8aa18d74c2700d1f559e">llvm::X86Disassembler::TYPE_VEX_3B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78a526cd04f63e6634ccad1e962577e59b8">llvm::X86Disassembler::TYPE_XOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a9de03b32789ed02aae9e8a4f881ef0c0">uFromEVEX3of4</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a4dfc5f5e7de8a290fb42d12a7e1b26dc">llvm::X86Disassembler::InternalInstruction::vectorExtensionPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aec1dd627d95bd0f134d90d538d728cac">llvm::X86Disassembler::InternalInstruction::vectorExtensionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#addd2d05002ebd2dc83a9d353a3d0231aa00dabef1990963986326bf8a846de59c">llvm::X86Disassembler::VEX_PREFIX_66</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#addd2d05002ebd2dc83a9d353a3d0231aaae1ab4d6adc50b57d220950665786ac1">llvm::X86Disassembler::VEX_PREFIX_F2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#addd2d05002ebd2dc83a9d353a3d0231aa4017792b6132c73f0635b09eb5af1c78">llvm::X86Disassembler::VEX_PREFIX_F3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#aaa9036cb371f65ab0c9aa3d7f2abb5f3">wFromEVEX3of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#ab11339ee1e5b8aaa4a706693c51041ae">wFromVEX3of3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#aea420e27120dd9f790849c9090b42256">wFromXOP3of3</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a0f317d7fd1a55926bed30febed7606da">zFromEVEX4of4</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86disassembler-cpp-/x86genericdisassembler/#a5872d463242e5872d4df00b5862e403f">anonymous{X86Disassembler.cpp}::X86GenericDisassembler::getInstruction</a>.</p>

</div>
</div>

### getInstructionIDWithAttrMask() {#a77b7a7d41251f651fae4a8f7cf8b8311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getInstructionIDWithAttrMask (uint16_t * instructionID, struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn, uint16_t attrMask)</td>
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



<p>Definition at line 1096 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="#ab3686bdd912c0d40035aa66dcffb36da">decode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea7c46af55213eba7d7104354bf073cbbe">llvm::X86Disassembler::MAP4</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a220b2f46f604cad58d418fb355d78865">MAP4_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea6934a4600c92849aec9b177ba29b95f7">llvm::X86Disassembler::MAP5</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#aeae838bb5a1c81d099c811f6348ca9df">MAP5_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea3168b0000bb711c5f33b0bc976272952">llvm::X86Disassembler::MAP6</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#ab695124c0e0dbddc8f1dbe567ee211de">MAP6_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea632479f320c04b5fc5d78d25d507b434">llvm::X86Disassembler::MAP7</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#aca2f331e9ce69df8e258199ea9c1f951">MAP7_SYM</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a10db75d3ff8f4c4f1d6ac8bcf960a585">llvm::X86Disassembler::InternalInstruction::modRM</a>, <a href="/web-llvm/docs/api/structs/modrmdecision/#a6c4ec8014e5927c67c5a0c9f0b9315aa">ModRMDecision::modrm_type</a>, <a href="/web-llvm/docs/api/structs/opcodedecision/#a7e7afd813c7cf7d606384fbbf5724c80">OpcodeDecision::modRMDecisions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eaf9d21d7b85f3134f59025667d1a87901">llvm::X86Disassembler::ONEBYTE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#ae053f9e80d644f47a6ee19185739162b">ONEBYTE_SYM</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a48eaa97ba6df31c9e0d5b60057b26cb3">llvm::X86Disassembler::InternalInstruction::opcode</a>, <a href="/web-llvm/docs/api/structs/contextdecision/#a1b98b9546e8a7df8cd4c894a0f33e5de">ContextDecision::opcodeDecisions</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#af87363b191e81d22b3dfa0618628ed3e">llvm::X86Disassembler::InternalInstruction::opcodeType</a>, <a href="#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a892daf9647ea098765cb833eb8596234">THREEBYTE38_SYM</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a6a9bb5a76c1dd6a02bb96ef407a6cb7d">THREEBYTE3A_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea326a3b9aff421046aeed72135f644612">llvm::X86Disassembler::THREEBYTE_38</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eaee435c44f7c8fb5577d8e247d86fe47f">llvm::X86Disassembler::THREEBYTE_3A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea0275a2adeb2bee7333ebddd77bc2dbe2">llvm::X86Disassembler::THREEDNOW_MAP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a4856eb908bad869295dd7568a8d735c1">THREEDNOW_MAP_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea4a57a751955088217dbec4ddde73a0d9">llvm::X86Disassembler::TWOBYTE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a0bfb472dc63adf5ea8919f054d4450e2">TWOBYTE_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eae2591c94eee2f2450337a7f76f0c4f35">llvm::X86Disassembler::XOP8_MAP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a73a6f64aec6a805d641a17c87a9d00b9">XOP8_MAP_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eaaf4fbb23ce6ffcb23876627445eb119c">llvm::X86Disassembler::XOP9_MAP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a349d73e2f39af064d9999d7780f9897d">XOP9_MAP_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea3fc124ba62a6f907eaa9253a4b0aa183">llvm::X86Disassembler::XOPA_MAP</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a9df14d49cac592bc2e51794ad434e9b2">XOPA_MAP_SYM</a>.</p>


<p>Referenced by <a href="#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>.</p>

</div>
</div>

### is16BitEquivalent() {#ae4e300d312f93aeb723f33f06e50673e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool is16BitEquivalent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * orig, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * equiv)</td>
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



<p>Definition at line 1066 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>Referenced by <a href="#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>.</p>

</div>
</div>

### is64Bit() {#a652270ec0bdb03b5a7f934524412aa7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool is64Bit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * name)</td>
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



<p>Definition at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#a53450ad670aacb536d17a6fd3804d649">llvm::X86Subtarget::canUseCMOV</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#a9c7ad87fb852c60ac35ad47163fd4d3d">llvm::X86Subtarget::canUseCMPXCHG16B</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#a1bfd70435724d5f229e3002834826384">llvm::X86Subtarget::canUseLAHFSAHF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a7ee234a7eddb790513041e995ed66158">CC_X86_Intr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#afa6cb69d74a302b1314319c28d9435ec">llvm::X86Subtarget::classifyGlobalFunctionReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#a9d5115303da1531a159c9527a549e6b5">llvm::X86Subtarget::classifyGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#abfc9f5d963c447cbe28355bc7887d1bd">llvm::X86Subtarget::classifyLocalReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp/#a03fd21ce7844c99b4568424e7c7214dc">computeDataLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparctargetmachine-cpp/#ac6cefd924da5608be33231d2caf12f91">computeDataLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp/#a003ab8893ba4df3a28468f7dfea5745a">ComputeLinkerOptionsLoadCommandSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#aeafb06413605da840d52ad76655540e8">createX86MCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a63c498f1fcb62301a44ad58e2dc8e7fc">llvm::PPCFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">llvm::PPCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetmachine-cpp/#aafa20a40f66280a3a22ecddfe821e5c0">getDataLayoutString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp/#ad69fce977b3fb471fd30747a11b59bc1">getEffectiveRelocModel</a>, <a href="#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#abb68cddc1b5010571d488b639eb9d561">llvm::object::XCOFFSymbolRef::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a7a7237cd5cb35f9159b32a96f4b14541">llvm::X86TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a046c53b9366f602644b022ee6e86c57e">llvm::object::XCOFFSymbolRef::getXCOFFCsectAuxRef</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#a32dde0aac78b3e4532a7c45f84968ede">llvm::X86Subtarget::hasBitScanPassThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#ae9d692c4fd80b7a6f84ed49916c12a6f">llvm::X86Subtarget::hasCLFLUSH</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#a4179ec80a26c269d437302d534689bdb">llvm::X86Subtarget::hasMFence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a98bec313edd88412de74ae369ce47005">llvm::X86::isCalleePop</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#abf2cf4c321484181eb952b13cba8ccb7">llvm::X86Subtarget::isTargetNaCl32</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#ae6ea07c18750ab2b37189cef9a99914a">llvm::X86Subtarget::isTargetNaCl64</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#a1e912c68c8255755a0d8b713a66e7740">llvm::X86Subtarget::isXRaySupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#aa4e01dc958f21a55df83d4fc9b811999">LowerBR_CC</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a4b9f5c287ed918ba764f534b79876702">llvm::PPCRegisterInfo::lowerDynamicAreaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#af92646d30b3f15471c866cd83fadfb62">llvm::SparcTargetLowering::LowerF128Compare</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ae64cc4af32654deb89d3073cc5ef4290">llvm::SparcTargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#ad6539bf0f1a9d3264ca7797741a5fbe6">LowerSELECT_CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7092b8371f80f3acf826e7bfc1e00d92">LowerToTLSExecModel</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machobindentry/#a7f570c7e9eb2d4585ab39f3f77a2f96d">llvm::object::MachOBindEntry::MachOBindEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machorebaseentry/#a67c25f4bf26947ca983e5f9a88d227b1">llvm::object::MachORebaseEntry::MachORebaseEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcelfmcasminfo/#a463a7c03ba11e950bd438542028a2a20">llvm::PPCELFMCAsmInfo::PPCELFMCAsmInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/ldtlscleanup/#aeb9ef6c06b2069f01ba55e3fd2af7b0f">anonymous{X86InstrInfo.cpp}::LDTLSCleanup::ReplaceTLSBaseAddrCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/ldtlscleanup/#a3c575506b0048149beea9d1f222fdc32">anonymous{X86InstrInfo.cpp}::LDTLSCleanup::SetRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#a0a9f6fd159806d59edd643ff11cb06f0">anonymous{SparcAsmParser.cpp}::SparcAsmParser::SparcAsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a3c201ce8a8de970fb4bd3542df8d0ab9">llvm::SparcFrameLowering::SparcFrameLowering</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/windowsx86asmbackend/#a62674954f25682a018d96d0c7c6b2df2">anonymous{X86AsmBackend.cpp}::WindowsX86AsmBackend::WindowsX86AsmBackend</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#adb9a99f53363b940f4690f42f1c2978e">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeWord</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoffobjectwriter-cpp-/xcoffwriter/#aba20d7d48fbb17155fa17029e3475835">anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::writeWord</a>, <a href="/web-llvm/docs/api/classes/llvm/x86elfmcasminfo/#a5f6bae7216b6b398d914b41530622c01">llvm::X86ELFMCAsmInfo::X86ELFMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a116242916a44a6d4f5301270c6c4f05e">llvm::X86FrameLowering::X86FrameLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5a4eef9d22e5039b95e52892c6656f95">llvm::X86InstrInfo::X86InstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86mcasminfodarwin/#a663f0b08ec61baaf51e6d1eec2b203f3">llvm::X86MCAsmInfoDarwin::X86MCAsmInfoDarwin</a> and <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#ad2cbbe27b5133a99b43e0b50eee2fe41">llvm::X86Subtarget::X86Subtarget</a>.</p>

</div>
</div>

### isCCMPOrCTEST() {#ac0572c45b7c999d1ef69cece322f0e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCCMPOrCTEST (<a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn)</td>
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



<p>Definition at line 1154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea7c46af55213eba7d7104354bf073cbbe">llvm::X86Disassembler::MAP4</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a10db75d3ff8f4c4f1d6ac8bcf960a585">llvm::X86Disassembler::InternalInstruction::modRM</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a48eaa97ba6df31c9e0d5b60057b26cb3">llvm::X86Disassembler::InternalInstruction::opcode</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#af87363b191e81d22b3dfa0618628ed3e">llvm::X86Disassembler::InternalInstruction::opcodeType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a8386ddf05ce05f470ca10679a78973bd">regFromModRM</a>.</p>


<p>Referenced by <a href="#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>, <a href="#a42be988af3ae0e352befa7189bd50936">readOperands</a> and <a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>.</p>

</div>
</div>

### isNF() {#a8bfeb1239d117ffbcde8064ef6fcc5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNF (<a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn)</td>
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



<p>Definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea7c46af55213eba7d7104354bf073cbbe">llvm::X86Disassembler::MAP4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a8e79075da5fbb18e84861838e5f60871">nfFromEVEX4of4</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a48eaa97ba6df31c9e0d5b60057b26cb3">llvm::X86Disassembler::InternalInstruction::opcode</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#af87363b191e81d22b3dfa0618628ed3e">llvm::X86Disassembler::InternalInstruction::opcodeType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a4a08eb3991a81513d973c4d1d70fd81b">ppFromEVEX3of4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea326a3b9aff421046aeed72135f644612">llvm::X86Disassembler::THREEBYTE_38</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a4dfc5f5e7de8a290fb42d12a7e1b26dc">llvm::X86Disassembler::InternalInstruction::vectorExtensionPrefix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#addd2d05002ebd2dc83a9d353a3d0231aa543616853caed3a04d81fc0790f9c9c8">llvm::X86Disassembler::VEX_PREFIX_NONE</a>.</p>


<p>Referenced by <a href="#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>.</p>

</div>
</div>

### isREX() {#a7ebe73b94309617db446535957bb7f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isREX (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn, uint8_t prefix)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#acec6e7f968f004123e55e6b2c04859f7">llvm::X86Disassembler::InternalInstruction::mode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a0a0a664b4e04945bb7338a796271eaf7">llvm::X86Disassembler::MODE_64BIT</a>.</p>


<p>Referenced by <a href="#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### isREX2() {#a111a978f64da66a01c6cfcb7c6374397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isREX2 (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn, uint8_t prefix)</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#acec6e7f968f004123e55e6b2c04859f7">llvm::X86Disassembler::InternalInstruction::mode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a0a0a664b4e04945bb7338a796271eaf7">llvm::X86Disassembler::MODE_64BIT</a>.</p>


<p>Referenced by <a href="#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### LLVMInitializeX86Disassembler() {#ad94a7ec0e2ddf818814c86ab2eca39f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_C_ABI void LLVMInitializeX86Disassembler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2485 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="#a299465c500c452a6ee8ec8f87fec4200">createX86Disassembler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35832c1b6a34093b01da33c2501a22ed">llvm::getTheX86_32Target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6431492d4966df0bafe4680216f76b7">llvm::getTheX86_64Target</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a9a971b1d09709d73cab58157eaaf0637">LLVM_C_ABI</a> and <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a8d3c3e977776517a7c1a82060b16da9f">llvm::TargetRegistry::RegisterMCDisassembler</a>.</p>

</div>
</div>

### peek() {#aef79c7512f86471adf8452b0cf8e2f58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool peek (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn, uint8_t &amp; byte)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a74bf20266f9a07d572e4ef494c29faf4">llvm::X86Disassembler::InternalInstruction::bytes</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aa3b2f84ae751780dd417d7d59f235f3f">llvm::X86Disassembler::InternalInstruction::readerCursor</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a9c4b81107e8000eb718b029773322245">llvm::X86Disassembler::InternalInstruction::startLocation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/json/anonymous-json-cpp-/parser/#ad370f0d761ba9d42ef133bbf4c817619">llvm::json::anonymous{JSON.cpp}::Parser::parseValue</a> and <a href="#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### readDisplacement() {#abe4017d5eac03b4caf08ca7a36ba2723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int readDisplacement (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn)</td>
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



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9af0ef8c72418989a4bb20243ccb61eeb0">llvm::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a7ebbb42b8992130aeeeb050a8c53f41e">llvm::X86Disassembler::InternalInstruction::displacement</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#afa82013a499392699bc9999514fb6977">llvm::X86Disassembler::InternalInstruction::displacementOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae01fc319973355e6cd69eb9224ce6cafac5a5b3bdf65b29024eb8126150657538">llvm::X86Disassembler::EA_DISP_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae01fc319973355e6cd69eb9224ce6cafa05caf1ba85c551141bdd17f67c404812">llvm::X86Disassembler::EA_DISP_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae01fc319973355e6cd69eb9224ce6cafa896daef79c9641dee49c81683b68ea92">llvm::X86Disassembler::EA_DISP_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae01fc319973355e6cd69eb9224ce6cafa6a4d6cb5da191b70c6888d28b52bb179">llvm::X86Disassembler::EA_DISP_NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a3ef5968bc28801c57bcf2d34b37c560e">llvm::X86Disassembler::InternalInstruction::eaDisplacement</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aa3b2f84ae751780dd417d7d59f235f3f">llvm::X86Disassembler::InternalInstruction::readerCursor</a> and <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a9c4b81107e8000eb718b029773322245">llvm::X86Disassembler::InternalInstruction::startLocation</a>.</p>


<p>Referenced by <a href="#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a>.</p>

</div>
</div>

### readImmediate() {#a771c0394a5e25fb07aaca2764eff8370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int readImmediate (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn, uint8_t size)</td>
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



<p>Definition at line 1551 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9af0ef8c72418989a4bb20243ccb61eeb0">llvm::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#afca447a485e325201cd7d0716787f52b">llvm::X86Disassembler::InternalInstruction::immediateOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#af4b85104515226212f307f5dfa14b772">llvm::X86Disassembler::InternalInstruction::immediates</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a55c7491f7bf1d1c1ad3693eb7d169164">llvm::X86Disassembler::InternalInstruction::immediateSize</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a5439803f50e569973762a82cb53f9a70">llvm::X86Disassembler::InternalInstruction::numImmediatesConsumed</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aa3b2f84ae751780dd417d7d59f235f3f">llvm::X86Disassembler::InternalInstruction::readerCursor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a> and <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a9c4b81107e8000eb718b029773322245">llvm::X86Disassembler::InternalInstruction::startLocation</a>.</p>


<p>Referenced by <a href="#a42be988af3ae0e352befa7189bd50936">readOperands</a>.</p>

</div>
</div>

### readMaskRegister() {#aa7089b50e7c7846d5b312d0148c30b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int readMaskRegister (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn)</td>
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



<p>Definition at line 1622 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#abd318ed530c8fc71af093848beb0e2a9">aaaFromEVEX4of4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78afd8e9c8ad31d8d77fbde6adfa808f8d4">llvm::X86Disassembler::TYPE_EVEX</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a4dfc5f5e7de8a290fb42d12a7e1b26dc">llvm::X86Disassembler::InternalInstruction::vectorExtensionPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aec1dd627d95bd0f134d90d538d728cac">llvm::X86Disassembler::InternalInstruction::vectorExtensionType</a> and <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a470c2d5240e9910df12140a2a4e78b73">llvm::X86Disassembler::InternalInstruction::writemask</a>.</p>


<p>Referenced by <a href="#a42be988af3ae0e352befa7189bd50936">readOperands</a>.</p>

</div>
</div>

### readModRM() {#ae354b93b59d4f78cddbb50869bd5ef6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int readModRM (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn)</td>
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



<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a57c6d8557589bdf4eb27c7cd616b5250">llvm::X86Disassembler::InternalInstruction::addressSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a89ead465c9b455052cc64ac9e270f9ec">b2FromREX2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#af112ae874f4cca98ba15a30f5743e5e1">bFromREX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9af0ef8c72418989a4bb20243ccb61eeb0">llvm::consume</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a8359bc7d916af10d61370e8d67cc645e">llvm::X86Disassembler::InternalInstruction::consumedModRM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#abc567fd2f4900dd81032863b0a5736ba">llvm::X86Disassembler::InternalInstruction::displacementSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a0dd85da44c5f9e9cb2bc1901a2e40d2cab34ee88b4e6eef0b907540f0fcbe7b5d">llvm::X86Disassembler::EA_BASE_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae01fc319973355e6cd69eb9224ce6cafac5a5b3bdf65b29024eb8126150657538">llvm::X86Disassembler::EA_DISP_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae01fc319973355e6cd69eb9224ce6cafa05caf1ba85c551141bdd17f67c404812">llvm::X86Disassembler::EA_DISP_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae01fc319973355e6cd69eb9224ce6cafa896daef79c9641dee49c81683b68ea92">llvm::X86Disassembler::EA_DISP_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae01fc319973355e6cd69eb9224ce6cafa6a4d6cb5da191b70c6888d28b52bb179">llvm::X86Disassembler::EA_DISP_NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a0f2fd34bb6c71514e8e82cdbd6c1db8b">llvm::X86Disassembler::InternalInstruction::eaBase</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a3ef5968bc28801c57bcf2d34b37c560e">llvm::X86Disassembler::InternalInstruction::eaDisplacement</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a3f3aa87cb7be22553d05f4f11e9169fc">llvm::X86Disassembler::InternalInstruction::eaRegBase</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d395e15e1920dad77c6f0a168a4d132">llvm::mod</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#acec6e7f968f004123e55e6b2c04859f7">llvm::X86Disassembler::InternalInstruction::mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a0a0a664b4e04945bb7338a796271eaf7">llvm::X86Disassembler::MODE_64BIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a4bce531c2ed18d569a316029616e82f0">modFromModRM</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a10db75d3ff8f4c4f1d6ac8bcf960a585">llvm::X86Disassembler::InternalInstruction::modRM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a9c7da8bddc41cbd0fdd48dd75309cc9d">r2FromEVEX2of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#aeb05c44e83d328ff61f3e6d95d9d098d">r2FromREX2</a>, <a href="#abe4017d5eac03b4caf08ca7a36ba2723">readDisplacement</a>, <a href="#a7d9a3ce3081e918d80b9770b584009a3">readSIB</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a0869d511c69dbc7ca0d257b16c93b0c6">llvm::X86Disassembler::InternalInstruction::reg</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a28d4304ea02db3c8195079ad7f385646">llvm::X86Disassembler::InternalInstruction::regBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a8386ddf05ce05f470ca10679a78973bd">regFromModRM</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aa5f56dce77be16a72930ac037453b391">llvm::X86Disassembler::InternalInstruction::registerSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a41d0e9e47665dc38d829804afd7f71e7">llvm::X86Disassembler::InternalInstruction::rex2ExtensionPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a800a1b50115e92e6d7762fab50cb5fd7">llvm::X86Disassembler::InternalInstruction::rexPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a1c2e931225f964b581ab025f86a39872">rFromREX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a384089e78b51b1b5773e879ed1d4e672">rmFromModRM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78afd8e9c8ad31d8d77fbde6adfa808f8d4">llvm::X86Disassembler::TYPE_EVEX</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a4dfc5f5e7de8a290fb42d12a7e1b26dc">llvm::X86Disassembler::InternalInstruction::vectorExtensionPrefix</a> and <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aec1dd627d95bd0f134d90d538d728cac">llvm::X86Disassembler::InternalInstruction::vectorExtensionType</a>.</p>


<p>Referenced by <a href="#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>, <a href="#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>, <a href="#a22cc5e803fedae95c7e1d22ffdb71cda">readOpcode</a> and <a href="#a42be988af3ae0e352befa7189bd50936">readOperands</a>.</p>

</div>
</div>

### readOpcode() {#a22cc5e803fedae95c7e1d22ffdb71cda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool readOpcode (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn)</td>
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



<p>Definition at line 928 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9af0ef8c72418989a4bb20243ccb61eeb0">llvm::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#afc5dad7cd1e49271d0a0436b4fec0ab1">llvm::X86Disassembler::InternalInstruction::mandatoryPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea7c46af55213eba7d7104354bf073cbbe">llvm::X86Disassembler::MAP4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea6934a4600c92849aec9b177ba29b95f7">llvm::X86Disassembler::MAP5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea3168b0000bb711c5f33b0bc976272952">llvm::X86Disassembler::MAP6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea632479f320c04b5fc5d78d25d507b434">llvm::X86Disassembler::MAP7</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#ae3d641e102f527d081672914da33f917">mFromREX2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#ac092c6a008116e099366148975855711">mmmFromEVEX2of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a30e003e4461758b6dba2c70f339ed6c3">mmmmmFromVEX2of3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#abbed9da0e0dde67954fe9e97f6befcc5">mmmmmFromXOP2of3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eaf9d21d7b85f3134f59025667d1a87901">llvm::X86Disassembler::ONEBYTE</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a48eaa97ba6df31c9e0d5b60057b26cb3">llvm::X86Disassembler::InternalInstruction::opcode</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#af87363b191e81d22b3dfa0618628ed3e">llvm::X86Disassembler::InternalInstruction::opcodeType</a>, <a href="#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a41d0e9e47665dc38d829804afd7f71e7">llvm::X86Disassembler::InternalInstruction::rex2ExtensionPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea326a3b9aff421046aeed72135f644612">llvm::X86Disassembler::THREEBYTE_38</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eaee435c44f7c8fb5577d8e247d86fe47f">llvm::X86Disassembler::THREEBYTE_3A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea0275a2adeb2bee7333ebddd77bc2dbe2">llvm::X86Disassembler::THREEDNOW_MAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea4a57a751955088217dbec4ddde73a0d9">llvm::X86Disassembler::TWOBYTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78afd8e9c8ad31d8d77fbde6adfa808f8d4">llvm::X86Disassembler::TYPE_EVEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78a594bf13c39d9785f9603aad71559006b">llvm::X86Disassembler::TYPE_VEX_2B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78ad63c6ef1f04c8aa18d74c2700d1f559e">llvm::X86Disassembler::TYPE_VEX_3B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78a526cd04f63e6634ccad1e962577e59b8">llvm::X86Disassembler::TYPE_XOP</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a4dfc5f5e7de8a290fb42d12a7e1b26dc">llvm::X86Disassembler::InternalInstruction::vectorExtensionPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aec1dd627d95bd0f134d90d538d728cac">llvm::X86Disassembler::InternalInstruction::vectorExtensionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a1394fd7f59cd599a2a6adda29e6778c1a93f5f8f993e9a66fc0aec7fd5ea2cef3">llvm::X86Disassembler::VEX_LOB_0F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a1394fd7f59cd599a2a6adda29e6778c1ad65b6581c00cd9c364212601abce3425">llvm::X86Disassembler::VEX_LOB_0F38</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a1394fd7f59cd599a2a6adda29e6778c1ab15ddc5f81ae3bda7a9a37f3ba0f1ad0">llvm::X86Disassembler::VEX_LOB_0F3A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a1394fd7f59cd599a2a6adda29e6778c1a3be852f1723249739425f72103b16cb8">llvm::X86Disassembler::VEX_LOB_MAP4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a1394fd7f59cd599a2a6adda29e6778c1aa89162786f0b4410592313133ff4abe8">llvm::X86Disassembler::VEX_LOB_MAP5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a1394fd7f59cd599a2a6adda29e6778c1a43eeebcc793cebba4c0af0aaa0061075">llvm::X86Disassembler::VEX_LOB_MAP6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a1394fd7f59cd599a2a6adda29e6778c1aba0ff20e0515edd91a78fee4a63c3ec4">llvm::X86Disassembler::VEX_LOB_MAP7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eae2591c94eee2f2450337a7f76f0c4f35">llvm::X86Disassembler::XOP8_MAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8eaaf4fbb23ce6ffcb23876627445eb119c">llvm::X86Disassembler::XOP9_MAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aed5529bc9c207a9ecdc6a2a93fe0ab97a2c36789f4611c843ffa073d50cc4c851">llvm::X86Disassembler::XOP_MAP_SELECT_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aed5529bc9c207a9ecdc6a2a93fe0ab97ac2c3119b84ccd3e86fee2daa73f0217b">llvm::X86Disassembler::XOP_MAP_SELECT_9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aed5529bc9c207a9ecdc6a2a93fe0ab97acb45a816f871c105bdc85dba0b29acb1">llvm::X86Disassembler::XOP_MAP_SELECT_A</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaab12f79117070dc035099f1daed2b8ea3fc124ba62a6f907eaa9253a4b0aa183">llvm::X86Disassembler::XOPA_MAP</a>.</p>

</div>
</div>

### readOpcodeRegister() {#ab536506d0058cd6baa803890e9d648dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int readOpcodeRegister (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn, uint8_t size)</td>
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



<p>Definition at line 1507 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a89ead465c9b455052cc64ac9e270f9ec">b2FromREX2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#af112ae874f4cca98ba15a30f5743e5e1">bFromREX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a48eaa97ba6df31c9e0d5b60057b26cb3">llvm::X86Disassembler::InternalInstruction::opcode</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a11bba4757345c8248aa05c3526779d50">llvm::X86Disassembler::InternalInstruction::opcodeRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aa5f56dce77be16a72930ac037453b391">llvm::X86Disassembler::InternalInstruction::registerSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a41d0e9e47665dc38d829804afd7f71e7">llvm::X86Disassembler::InternalInstruction::rex2ExtensionPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a800a1b50115e92e6d7762fab50cb5fd7">llvm::X86Disassembler::InternalInstruction::rexPrefix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="#a42be988af3ae0e352befa7189bd50936">readOperands</a>.</p>

</div>
</div>

### readOperands() {#a42be988af3ae0e352befa7189bd50936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int readOperands (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn)</td>
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



<p>Definition at line 1635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a57c6d8557589bdf4eb27c7cd616b5250">llvm::X86Disassembler::InternalInstruction::addressSize</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a3fd192bea7092fa66a95e4ca0cf236fe">CASE_ENCODING_RM</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2a7d2bc3ef8e759126222de6b4d440fe">CASE_ENCODING_VSIB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ae0228f36529f75f692753ef96d725012">debug</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a7ebbb42b8992130aeeeb050a8c53f41e">llvm::X86Disassembler::InternalInstruction::displacement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae01fc319973355e6cd69eb9224ce6cafa896daef79c9641dee49c81683b68ea92">llvm::X86Disassembler::EA_DISP_8</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a0f2fd34bb6c71514e8e82cdbd6c1db8b">llvm::X86Disassembler::InternalInstruction::eaBase</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a3ef5968bc28801c57bcf2d34b37c560e">llvm::X86Disassembler::InternalInstruction::eaDisplacement</a>, <a href="#adb1fcba65d61d145b053ee0217b3dee7">fixupReg</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#af4b85104515226212f307f5dfa14b772">llvm::X86Disassembler::InternalInstruction::immediates</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a55c7491f7bf1d1c1ad3693eb7d169164">llvm::X86Disassembler::InternalInstruction::immediateSize</a>, <a href="#ac0572c45b7c999d1ef69cece322f0e1c">isCCMPOrCTEST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a05d1ee61cb5494166e335ff64d2cffa8">l2FromEVEX4of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a057966fda096251466bbdfda0b801081">lFromEVEX4of4</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#acec6e7f968f004123e55e6b2c04859f7">llvm::X86Disassembler::InternalInstruction::mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a0a0a664b4e04945bb7338a796271eaf7">llvm::X86Disassembler::MODE_64BIT</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a5439803f50e569973762a82cb53f9a70">llvm::X86Disassembler::InternalInstruction::numImmediatesConsumed</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a48eaa97ba6df31c9e0d5b60057b26cb3">llvm::X86Disassembler::InternalInstruction::opcode</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/instructionspecifier/#a5c97487808484796284b76623db83810">llvm::X86Disassembler::InstructionSpecifier::operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#aec9a3936dedbb738365b55da9fa780f8">oszcFromEVEX3of4</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a1fb6f49de943aa22baa9a9ce75cbcf35">llvm::X86Disassembler::InternalInstruction::RC</a>, <a href="#a771c0394a5e25fb07aaca2764eff8370">readImmediate</a>, <a href="#aa7089b50e7c7846d5b312d0148c30b5f">readMaskRegister</a>, <a href="#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a>, <a href="#ab536506d0058cd6baa803890e9d648dd">readOpcodeRegister</a>, <a href="#a8514fc80a87b940b85536ef125c05350">readVVVV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a7201603cc366bc19401cb3973b8ce209">scFromEVEX4of4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae905569d5e7d96d9e1f4150c289660b6a6f17dadc7b55217d06e4a20efeb747ee">llvm::X86Disassembler::SIB_INDEX_NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aa4e016b484881a9be4576ae14b12481e">llvm::X86Disassembler::InternalInstruction::sibIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a5dd72bf92591d08bd4ae712541461b24">llvm::X86Disassembler::InternalInstruction::sibIndexBase</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aac2dea60075f209cbef6ccf11f9829ba">llvm::X86Disassembler::InternalInstruction::spec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78afd8e9c8ad31d8d77fbde6adfa808f8d4">llvm::X86Disassembler::TYPE_EVEX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a4b4847dc5b2960b63e97e71da1d802a4">v2FromEVEX4of4</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a4dfc5f5e7de8a290fb42d12a7e1b26dc">llvm::X86Disassembler::InternalInstruction::vectorExtensionPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aec1dd627d95bd0f134d90d538d728cac">llvm::X86Disassembler::InternalInstruction::vectorExtensionType</a> and <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aef9fa9afc0f128a5541cdc1944ebc076">llvm::X86Disassembler::InternalInstruction::vvvv</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86disassembler-cpp-/x86genericdisassembler/#a5872d463242e5872d4df00b5862e403f">anonymous{X86Disassembler.cpp}::X86GenericDisassembler::getInstruction</a>.</p>

</div>
</div>

### readPrefixes() {#aef1a8136ca4df8d11829c1aa2b708f5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int readPrefixes (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a57c6d8557589bdf4eb27c7cd616b5250">llvm::X86Disassembler::InternalInstruction::addressSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a8940512bc6cf3af7ed8ba1f885f18f81">b2FromEVEX2of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#ac938494c24cf099544f7e9a4075454c1">bFromEVEX2of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a3b86d4baef893d56800b61fb8a936b50">bFromREX2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#aabfc6f7a66e0c44fd2145dddeaa88497">bFromVEX2of3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a215ec2d9ebe8a9be78a3cd8eabaeed71">bFromXOP2of3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9af0ef8c72418989a4bb20243ccb61eeb0">llvm::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#abc567fd2f4900dd81032863b0a5736ba">llvm::X86Disassembler::InternalInstruction::displacementSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a55cba166daaaf8da5569f173c900d5aa">llvm::X86Disassembler::InternalInstruction::hasAdSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a8e637fa4393e9c7d4cc2a52147d82893">llvm::X86Disassembler::InternalInstruction::hasLockPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a55fd804164f59f102d9cf3bec2bdec5c">llvm::X86Disassembler::InternalInstruction::hasOpSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a55c7491f7bf1d1c1ad3693eb7d169164">llvm::X86Disassembler::InternalInstruction::immediateSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#ad30c0dba88d2e5f9cc2a9e74fd1e1078">isPrefix</a>, <a href="#a7ebe73b94309617db446535957bb7f50">isREX</a>, <a href="#a111a978f64da66a01c6cfcb7c6374397">isREX2</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#afc5dad7cd1e49271d0a0436b4fec0ab1">llvm::X86Disassembler::InternalInstruction::mandatoryPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#acec6e7f968f004123e55e6b2c04859f7">llvm::X86Disassembler::InternalInstruction::mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a92735b4f723ce305b1b618c0bafae971">llvm::X86Disassembler::MODE_16BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8ae4207458cc887c4e1b45709cc318113e">llvm::X86Disassembler::MODE_32BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a0a0a664b4e04945bb7338a796271eaf7">llvm::X86Disassembler::MODE_64BIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/disassembler/webassemblydisassembler-cpp/#a3af3220ede6cc99137a661c057fb4042">nextByte</a>, <a href="#aef79c7512f86471adf8452b0cf8e2f58">peek</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#adba38d038bb20114ef792961068aebd9">ppFromVEX2of2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a91bdeef85650fa60106450fb24d9c500">ppFromXOP3of3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a9c7da8bddc41cbd0fdd48dd75309cc9d">r2FromEVEX2of4</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aa3b2f84ae751780dd417d7d59f235f3f">llvm::X86Disassembler::InternalInstruction::readerCursor</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aa5f56dce77be16a72930ac037453b391">llvm::X86Disassembler::InternalInstruction::registerSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#adc143cf4b45ac2f3084ad2481cd7856a">llvm::X86Disassembler::InternalInstruction::repeatPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a41d0e9e47665dc38d829804afd7f71e7">llvm::X86Disassembler::InternalInstruction::rex2ExtensionPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a800a1b50115e92e6d7762fab50cb5fd7">llvm::X86Disassembler::InternalInstruction::rexPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a02d842bd0f45034a398eecc59d65c805">rFromEVEX2of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a7fb25ff22b437983d21e368c64374334">rFromREX2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a4543a64655e2abfbf25bc206c9219150">rFromVEX2of2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a0eb17652126644a237528e0153ee96b1">rFromVEX2of3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a5297b8410eeadfd658404a6cf3958c07">rFromXOP2of3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#afcacc827be10451e9900946844350afead5a5b066d5cf1c312135a98292843022">llvm::X86Disassembler::SEG_OVERRIDE_CS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#afcacc827be10451e9900946844350afeaff8f03b6101c7edf8dbcd94da14eb929">llvm::X86Disassembler::SEG_OVERRIDE_DS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#afcacc827be10451e9900946844350afeaf13dc03e7f4ce19d67915d5f718c3cc1">llvm::X86Disassembler::SEG_OVERRIDE_ES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#afcacc827be10451e9900946844350afea55a575ffdef756ea97c0b82f93a27035">llvm::X86Disassembler::SEG_OVERRIDE_FS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#afcacc827be10451e9900946844350afeab788e7576e087f48bad3f1bc41b37bf9">llvm::X86Disassembler::SEG_OVERRIDE_GS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#afcacc827be10451e9900946844350afea5fa4e0d53239f1adf986ae2b0e51293c">llvm::X86Disassembler::SEG_OVERRIDE_SS</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a502d8f02d88de14dd4630514d487c4b7">llvm::X86Disassembler::InternalInstruction::segmentOverride</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a9c4b81107e8000eb718b029773322245">llvm::X86Disassembler::InternalInstruction::startLocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78afd8e9c8ad31d8d77fbde6adfa808f8d4">llvm::X86Disassembler::TYPE_EVEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78ab831cfec071b3ebe687235b3ef5b96f9">llvm::X86Disassembler::TYPE_NO_VEX_XOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78a594bf13c39d9785f9603aad71559006b">llvm::X86Disassembler::TYPE_VEX_2B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78ad63c6ef1f04c8aa18d74c2700d1f559e">llvm::X86Disassembler::TYPE_VEX_3B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78a526cd04f63e6634ccad1e962577e59b8">llvm::X86Disassembler::TYPE_XOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a9de03b32789ed02aae9e8a4f881ef0c0">uFromEVEX3of4</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a4dfc5f5e7de8a290fb42d12a7e1b26dc">llvm::X86Disassembler::InternalInstruction::vectorExtensionPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aec1dd627d95bd0f134d90d538d728cac">llvm::X86Disassembler::InternalInstruction::vectorExtensionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#addd2d05002ebd2dc83a9d353a3d0231aa00dabef1990963986326bf8a846de59c">llvm::X86Disassembler::VEX_PREFIX_66</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#aaa9036cb371f65ab0c9aa3d7f2abb5f3">wFromEVEX3of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a567f29a688d316f9d1e149753d4d77da">wFromREX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a1082da2cd24fb0eaf8c38ab381934c02">wFromREX2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#ab11339ee1e5b8aaa4a706693c51041ae">wFromVEX3of3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#aea420e27120dd9f790849c9090b42256">wFromXOP3of3</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a74edea7cfe143661776a30d6767598af">llvm::X86Disassembler::InternalInstruction::xAcquireRelease</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#acc1e56049a41a736160b7ed348bc7709">xFromEVEX2of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#aa3e731942caa7fdb6384f15a4af2a665">xFromREX2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a2702d55c4b2a40989bd2b9cc8a71596e">xFromVEX2of3</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#aa76783b724faa5f93e249184af820b9e">xFromXOP2of3</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86disassembler-cpp-/x86genericdisassembler/#a5872d463242e5872d4df00b5862e403f">anonymous{X86Disassembler.cpp}::X86GenericDisassembler::getInstruction</a>.</p>

</div>
</div>

### readSIB() {#a7d9a3ce3081e918d80b9770b584009a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int readSIB (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn)</td>
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



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a57c6d8557589bdf4eb27c7cd616b5250">llvm::X86Disassembler::InternalInstruction::addressSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a89ead465c9b455052cc64ac9e270f9ec">b2FromREX2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a439f21b8d5ea58ea5fe17d11d1547986">baseFromSIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#af112ae874f4cca98ba15a30f5743e5e1">bFromREX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9af0ef8c72418989a4bb20243ccb61eeb0">llvm::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae01fc319973355e6cd69eb9224ce6cafa05caf1ba85c551141bdd17f67c404812">llvm::X86Disassembler::EA_DISP_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae01fc319973355e6cd69eb9224ce6cafa896daef79c9641dee49c81683b68ea92">llvm::X86Disassembler::EA_DISP_8</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a3ef5968bc28801c57bcf2d34b37c560e">llvm::X86Disassembler::InternalInstruction::eaDisplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#adc11bcb515676078c7c25441c03bddbc">indexFromSIB</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a4bce531c2ed18d569a316029616e82f0">modFromModRM</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a10db75d3ff8f4c4f1d6ac8bcf960a585">llvm::X86Disassembler::InternalInstruction::modRM</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a41d0e9e47665dc38d829804afd7f71e7">llvm::X86Disassembler::InternalInstruction::rex2ExtensionPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a800a1b50115e92e6d7762fab50cb5fd7">llvm::X86Disassembler::InternalInstruction::rexPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a7b5f49eafdca9d6be0464fccb94a4f33">scaleFromSIB</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a7c02a6677c4ebfdb4269bf24ca10bdc0">llvm::X86Disassembler::InternalInstruction::sib</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaefe05b2150554a84b796b4bca71f706a7cea6ea4847ad1bfdcfa78ec0f2d4a6c">llvm::X86Disassembler::SIB_BASE_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae905569d5e7d96d9e1f4150c289660b6a6f17dadc7b55217d06e4a20efeb747ee">llvm::X86Disassembler::SIB_INDEX_NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#ad0d7a34add9ff161d0c10f219a890bfc">llvm::X86Disassembler::InternalInstruction::sibBase</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aa4e016b484881a9be4576ae14b12481e">llvm::X86Disassembler::InternalInstruction::sibIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a5dd72bf92591d08bd4ae712541461b24">llvm::X86Disassembler::InternalInstruction::sibIndexBase</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a85eb1bfec569b970d44a12aad0488634">llvm::X86Disassembler::InternalInstruction::sibScale</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a7181fa976e053d8a8a696f381df284c8">x2FromREX2</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#af00d764f04a2d7143d9de59ea213f148">xFromREX</a>.</p>


<p>Referenced by <a href="#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a>.</p>

</div>
</div>

### readVVVV() {#a8514fc80a87b940b85536ef125c05350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int readVVVV (struct <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> * insn)</td>
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



<p>Definition at line 1595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#acec6e7f968f004123e55e6b2c04859f7">llvm::X86Disassembler::InternalInstruction::mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a0a0a664b4e04945bb7338a796271eaf7">llvm::X86Disassembler::MODE_64BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78afd8e9c8ad31d8d77fbde6adfa808f8d4">llvm::X86Disassembler::TYPE_EVEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78a594bf13c39d9785f9603aad71559006b">llvm::X86Disassembler::TYPE_VEX_2B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78ad63c6ef1f04c8aa18d74c2700d1f559e">llvm::X86Disassembler::TYPE_VEX_3B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a88730ad84a956ffad5205b3b79a93b78a526cd04f63e6634ccad1e962577e59b8">llvm::X86Disassembler::TYPE_XOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a4b4847dc5b2960b63e97e71da1d802a4">v2FromEVEX4of4</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a4dfc5f5e7de8a290fb42d12a7e1b26dc">llvm::X86Disassembler::InternalInstruction::vectorExtensionPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aec1dd627d95bd0f134d90d538d728cac">llvm::X86Disassembler::InternalInstruction::vectorExtensionType</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aef9fa9afc0f128a5541cdc1944ebc076">llvm::X86Disassembler::InternalInstruction::vvvv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#aefa5ea2a9230c9f8dba9efa4d4e226b4">vvvvFromEVEX3of4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a8dc9745657ce1382ca803e1e3e62a049">vvvvFromVEX2of2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a9b5608175fb4bc57fd5e6bcd7f5efed2">vvvvFromVEX3of3</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#ae5714cb8f59b79c1938dca548bfb61f9">vvvvFromXOP3of3</a>.</p>


<p>Referenced by <a href="#a42be988af3ae0e352befa7189bd50936">readOperands</a>.</p>

</div>
</div>

### translateDstIndex() {#a4094775b51be5196cd6a6a5254530d6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool translateDstIndex (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; mcInst, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> &amp; insn)</td>
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

<p>translateDstIndex - Appends a destination index operand to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mcInst</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">insn</td>
<td class="doxyParamItemDescription"><p>- The internal instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1978 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a55cba166daaaf8da5569f173c900d5aa">llvm::X86Disassembler::InternalInstruction::hasAdSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#acec6e7f968f004123e55e6b2c04859f7">llvm::X86Disassembler::InternalInstruction::mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a92735b4f723ce305b1b618c0bafae971">llvm::X86Disassembler::MODE_16BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8ae4207458cc887c4e1b45709cc318113e">llvm::X86Disassembler::MODE_32BIT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a0a0a664b4e04945bb7338a796271eaf7">llvm::X86Disassembler::MODE_64BIT</a>.</p>


<p>Referenced by <a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>.</p>

</div>
</div>

### translateFPRegister() {#a4baeecd8498cfd4ba890951058393621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void translateFPRegister (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; mcInst, uint8_t stackPos)</td>
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

<p>translateFPRegister - Translates a stack position on the FPU stack to its LLVM form, and appends it to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mcInst</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">stackPos</td>
<td class="doxyParamItemDescription"><p>- The stack position to translate.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>.</p>


<p>Referenced by <a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>.</p>

</div>
</div>

### translateImmediate() {#a409baefdf6be89e38deebefb129c1978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void translateImmediate (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; mcInst, uint64_t immediate, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier">OperandSpecifier</a> &amp; operand, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> &amp; insn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Dis)</td>
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

<p>translateImmediate - Appends an immediate operand to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mcInst</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">immediate</td>
<td class="doxyParamItemDescription"><p>- The immediate value to append.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">operand</td>
<td class="doxyParamItemDescription"><p>- The operand, as stored in the descriptor table.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">insn</td>
<td class="doxyParamItemDescription"><p>- The internal instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2000 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#abc567fd2f4900dd81032863b0a5736ba">llvm::X86Disassembler::InternalInstruction::displacementSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier/#ab0367c642b33d93facb7e1df39b5f9e5">llvm::X86Disassembler::OperandSpecifier::encoding</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#afca447a485e325201cd7d0716787f52b">llvm::X86Disassembler::InternalInstruction::immediateOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a55c7491f7bf1d1c1ad3693eb7d169164">llvm::X86Disassembler::InternalInstruction::immediateSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#a54d7439b3555f2971b6fe775ae65fc13">isBranch</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#afd1103179df17f2e9eee0d79997cf1fc">llvm::X86Disassembler::InternalInstruction::length</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a502d8f02d88de14dd4630514d487c4b7">llvm::X86Disassembler::InternalInstruction::segmentOverride</a>, <a href="#a698bcd15212d3270393b6e3912b874f1">segmentRegnums</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a9c4b81107e8000eb718b029773322245">llvm::X86Disassembler::InternalInstruction::startLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a495c1c01a620a4f59ff21e667a90c35d">llvm::MCDisassembler::tryAddingSymbolicOperand</a> and <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier/#ac8faf439db1a327881e373130e4fcd4d">llvm::X86Disassembler::OperandSpecifier::type</a>.</p>


<p>Referenced by <a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>.</p>

</div>
</div>

### translateInstruction() {#ae99d82425a463a5dd5413112fda5ed17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool translateInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; mcInst, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> &amp; insn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Dis)</td>
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

<p>translateInstruction - Translates an internal instruction and all its operands to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mcInst</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to populate with the instruction's data.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">insn</td>
<td class="doxyParamItemDescription"><p>- The internal instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- false on success; true otherwise.</p></dd>
</dl>


<p>Definition at line 2445 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aecd4e9369c30b88c8e528489f69e0c8e">llvm::MCInst::clear</a>, <a href="#ae0228f36529f75f692753ef96d725012">debug</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#acc4b989b9e4750eeb9787809e0159054">llvm::X86Disassembler::InternalInstruction::instructionID</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a868d56868e1ef47e4232797924657b46">llvm::X86Disassembler::InternalInstruction::numImmediatesTranslated</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a363bc8e0050d89c461be91e81229edef">llvm::X86Disassembler::InternalInstruction::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aac2dea60075f209cbef6ccf11f9829ba">llvm::X86Disassembler::InternalInstruction::spec</a>, <a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a> and <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a74edea7cfe143661776a30d6767598af">llvm::X86Disassembler::InternalInstruction::xAcquireRelease</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86disassembler-cpp-/x86genericdisassembler/#a5872d463242e5872d4df00b5862e403f">anonymous{X86Disassembler.cpp}::X86GenericDisassembler::getInstruction</a>.</p>

</div>
</div>

### translateMaskRegister() {#a39a264ff5629dff4dc2a278f3848b4df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool translateMaskRegister (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; mcInst, uint8_t maskRegNum)</td>
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

<p>translateMaskRegister - Translates a 3-bit mask register number to LLVM form, and appends it to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mcInst</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">maskRegNum</td>
<td class="doxyParamItemDescription"><p>- Number of mask register from 0 to 7.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- false on success; true otherwise.</p></dd>
</dl>


<p>Definition at line 2358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a> and <a href="#ae0228f36529f75f692753ef96d725012">debug</a>.</p>


<p>Referenced by <a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>.</p>

</div>
</div>

### translateOperand() {#aeb806eaaca65c1a593f5af3078798819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool translateOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; mcInst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier">OperandSpecifier</a> &amp; operand, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> &amp; insn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Dis)</td>
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

<p>translateOperand - Translates an operand stored in an internal instruction to LLVM's format and appends it to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mcInst</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">operand</td>
<td class="doxyParamItemDescription"><p>- The operand, as stored in the descriptor table.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">insn</td>
<td class="doxyParamItemDescription"><p>- The internal instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- false on success; true otherwise.</p></dd>
</dl>


<p>Definition at line 2376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a3fd192bea7092fa66a95e4ca0cf236fe">CASE_ENCODING_RM</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h/#a2a7d2bc3ef8e759126222de6b4d440fe">CASE_ENCODING_VSIB</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#ae0228f36529f75f692753ef96d725012">debug</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier/#ab0367c642b33d93facb7e1df39b5f9e5">llvm::X86Disassembler::OperandSpecifier::encoding</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#af4b85104515226212f307f5dfa14b772">llvm::X86Disassembler::InternalInstruction::immediates</a>, <a href="#ac0572c45b7c999d1ef69cece322f0e1c">isCCMPOrCTEST</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a10db75d3ff8f4c4f1d6ac8bcf960a585">llvm::X86Disassembler::InternalInstruction::modRM</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a868d56868e1ef47e4232797924657b46">llvm::X86Disassembler::InternalInstruction::numImmediatesTranslated</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a11bba4757345c8248aa05c3526779d50">llvm::X86Disassembler::InternalInstruction::opcodeRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a363bc8e0050d89c461be91e81229edef">llvm::X86Disassembler::InternalInstruction::operands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a1fb6f49de943aa22baa9a9ce75cbcf35">llvm::X86Disassembler::InternalInstruction::RC</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a0869d511c69dbc7ca0d257b16c93b0c6">llvm::X86Disassembler::InternalInstruction::reg</a>, <a href="#a4094775b51be5196cd6a6a5254530d6c">translateDstIndex</a>, <a href="#a4baeecd8498cfd4ba890951058393621">translateFPRegister</a>, <a href="#a409baefdf6be89e38deebefb129c1978">translateImmediate</a>, <a href="#a39a264ff5629dff4dc2a278f3848b4df">translateMaskRegister</a>, <a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>, <a href="#a06e3b1499180a2b92acc66f9203ac920">translateRegister</a>, <a href="#aace6b74b8ffb4a67a94c8720813f18c2">translateRM</a>, <a href="#a972b23f3658215b06333703a6099eeb1">translateSrcIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier/#ac8faf439db1a327881e373130e4fcd4d">llvm::X86Disassembler::OperandSpecifier::type</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aef9fa9afc0f128a5541cdc1944ebc076">llvm::X86Disassembler::InternalInstruction::vvvv</a> and <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a470c2d5240e9910df12140a2a4e78b73">llvm::X86Disassembler::InternalInstruction::writemask</a>.</p>


<p>Referenced by <a href="#ae99d82425a463a5dd5413112fda5ed17">translateInstruction</a> and <a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>.</p>

</div>
</div>

### translateRegister() {#a06e3b1499180a2b92acc66f9203ac920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void translateRegister (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; mcInst, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a1e59b79e1d09149912cad9c0ef2809ad">Reg</a> reg)</td>
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

<p>translateRegister - Translates an internal register to the appropriate LLVM register, and appends it as an operand to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mcInst</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">reg</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a1e59b79e1d09149912cad9c0ef2809ad">Reg</a> to append.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1930 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a8f4c518929a964ae54a9d42780670cd2">ALL_REGS</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>.</p>


<p>Referenced by <a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>.</p>

</div>
</div>

### translateRM() {#aace6b74b8ffb4a67a94c8720813f18c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool translateRM (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; mcInst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier">OperandSpecifier</a> &amp; operand, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> &amp; insn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Dis)</td>
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

<p>translateRM - Translates an operand stored in the R/M (and possibly SIB) byte of an instruction to LLVM form, and appends it to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mcInst</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">operand</td>
<td class="doxyParamItemDescription"><p>- The operand, as stored in the descriptor table.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">insn</td>
<td class="doxyParamItemDescription"><p>- The instruction to extract Mod, R/M, and SIB fields from.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- 0 on success; nonzero otherwise</p></dd>
</dl>


<p>Definition at line 2309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="#ae0228f36529f75f692753ef96d725012">debug</a>, <a href="#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a>, <a href="#aea1e232218bf327acf353b1f07db2f86">translateRMRegister</a> and <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier/#ac8faf439db1a327881e373130e4fcd4d">llvm::X86Disassembler::OperandSpecifier::type</a>.</p>


<p>Referenced by <a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>.</p>

</div>
</div>

### translateRMMemory() {#ae82674c41a00b35f36f9ecf81932512e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool translateRMMemory (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; mcInst, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> &amp; insn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Dis, bool ForceSIB=false)</td>
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

<p>translateRMMemory - Translates a memory operand stored in the Mod and R/M fields of an internal instruction (and possibly its SIB byte) to a memory operand in LLVM's format, and appends it to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mcInst</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">insn</td>
<td class="doxyParamItemDescription"><p>- The instruction to extract Mod, R/M, and SIB fields from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ForceSIB</td>
<td class="doxyParamItemDescription"><p>- The instruction must use SIB.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- 0 on success; nonzero otherwise</p></dd>
</dl>


<p>Definition at line 2144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a57c6d8557589bdf4eb27c7cd616b5250">llvm::X86Disassembler::InternalInstruction::addressSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#ae1c2d19d6110a95f79a5e8cbe1f6e007">ALL_EA_BASES</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a8f4c518929a964ae54a9d42780670cd2">ALL_REGS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a967004f254ec4b0e36dca9b2db27f139">ALL_SIB_BASES</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#ae0228f36529f75f692753ef96d725012">debug</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a7ebbb42b8992130aeeeb050a8c53f41e">llvm::X86Disassembler::InternalInstruction::displacement</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#afa82013a499392699bc9999514fb6977">llvm::X86Disassembler::InternalInstruction::displacementOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#abc567fd2f4900dd81032863b0a5736ba">llvm::X86Disassembler::InternalInstruction::displacementSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a0dd85da44c5f9e9cb2bc1901a2e40d2cab34ee88b4e6eef0b907540f0fcbe7b5d">llvm::X86Disassembler::EA_BASE_NONE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#aa49626340dd008810da4c2f48358f4e5">EA_BASES_32BIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a67e6e1688bcff4c9ea17a36f5cd8b8b0">EA_BASES_64BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae01fc319973355e6cd69eb9224ce6cafa6a4d6cb5da191b70c6888d28b52bb179">llvm::X86Disassembler::EA_DISP_NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a0f2fd34bb6c71514e8e82cdbd6c1db8b">llvm::X86Disassembler::InternalInstruction::eaBase</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a3ef5968bc28801c57bcf2d34b37c560e">llvm::X86Disassembler::InternalInstruction::eaDisplacement</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#afd1103179df17f2e9eee0d79997cf1fc">llvm::X86Disassembler::InternalInstruction::length</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#acec6e7f968f004123e55e6b2c04859f7">llvm::X86Disassembler::InternalInstruction::mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a0a0a664b4e04945bb7338a796271eaf7">llvm::X86Disassembler::MODE_64BIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a7c194da583ffb0dd2fab50331e4cbc41">REGS_XMM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a6fc6928518e9a8c348d985bec97d382e">REGS_YMM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#acffec50bf53b6bde81c96e0951d577eb">REGS_ZMM</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a502d8f02d88de14dd4630514d487c4b7">llvm::X86Disassembler::InternalInstruction::segmentOverride</a>, <a href="#a698bcd15212d3270393b6e3912b874f1">segmentRegnums</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#aaefe05b2150554a84b796b4bca71f706a7cea6ea4847ad1bfdcfa78ec0f2d4a6c">llvm::X86Disassembler::SIB_BASE_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#ae905569d5e7d96d9e1f4150c289660b6a6f17dadc7b55217d06e4a20efeb747ee">llvm::X86Disassembler::SIB_INDEX_NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#ad0d7a34add9ff161d0c10f219a890bfc">llvm::X86Disassembler::InternalInstruction::sibBase</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#aa4e016b484881a9be4576ae14b12481e">llvm::X86Disassembler::InternalInstruction::sibIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a85eb1bfec569b970d44a12aad0488634">llvm::X86Disassembler::InternalInstruction::sibScale</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a9c4b81107e8000eb718b029773322245">llvm::X86Disassembler::InternalInstruction::startLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a7b3f2feec2e2452107a197b7e0d2907b">llvm::MCDisassembler::tryAddingPcLoadReferenceComment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a495c1c01a620a4f59ff21e667a90c35d">llvm::MCDisassembler::tryAddingSymbolicOperand</a>.</p>


<p>Referenced by <a href="#aace6b74b8ffb4a67a94c8720813f18c2">translateRM</a>.</p>

</div>
</div>

### translateRMRegister() {#aea1e232218bf327acf353b1f07db2f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool translateRMRegister (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; mcInst, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> &amp; insn)</td>
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

<p>translateRMRegister - Translates a register stored in the R/M field of the ModR/M byte to its LLVM equivalent and appends it to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mcInst</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">insn</td>
<td class="doxyParamItemDescription"><p>- The internal instruction to extract the R/M field from.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- 0 on success; -1 otherwise</p></dd>
</dl>


<p>Definition at line 2105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#ae1c2d19d6110a95f79a5e8cbe1f6e007">ALL_EA_BASES</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h/#a8f4c518929a964ae54a9d42780670cd2">ALL_REGS</a>, <a href="#ae0228f36529f75f692753ef96d725012">debug</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a0dd85da44c5f9e9cb2bc1901a2e40d2cab34ee88b4e6eef0b907540f0fcbe7b5d">llvm::X86Disassembler::EA_BASE_NONE</a> and <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a0f2fd34bb6c71514e8e82cdbd6c1db8b">llvm::X86Disassembler::InternalInstruction::eaBase</a>.</p>


<p>Referenced by <a href="#aace6b74b8ffb4a67a94c8720813f18c2">translateRM</a>.</p>

</div>
</div>

### translateSrcIndex() {#a972b23f3658215b06333703a6099eeb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool translateSrcIndex (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; mcInst, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a> &amp; insn)</td>
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

<p>translateSrcIndex - Appends a source index operand to an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mcInst</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">insn</td>
<td class="doxyParamItemDescription"><p>- The internal instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1953 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a55cba166daaaf8da5569f173c900d5aa">llvm::X86Disassembler::InternalInstruction::hasAdSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#acec6e7f968f004123e55e6b2c04859f7">llvm::X86Disassembler::InternalInstruction::mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a92735b4f723ce305b1b618c0bafae971">llvm::X86Disassembler::MODE_16BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8ae4207458cc887c4e1b45709cc318113e">llvm::X86Disassembler::MODE_32BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler/#a2770a7b5455f322436ac3d7723979ab8a0a0a664b4e04945bb7338a796271eaf7">llvm::X86Disassembler::MODE_64BIT</a>, <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#a502d8f02d88de14dd4630514d487c4b7">llvm::X86Disassembler::InternalInstruction::segmentOverride</a> and <a href="#a698bcd15212d3270393b6e3912b874f1">segmentRegnums</a>.</p>


<p>Referenced by <a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### segmentRegnums {#a698bcd15212d3270393b6e3912b874f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t segmentRegnums[SEG_OVERRIDE_max]</td>
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
  0,        
  X86::CS,
  X86::SS,
  X86::DS,
  X86::ES,
  X86::FS,
  X86::GS
}
</div>
</dd>
</dl>

<p>Definition at line 1939 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>Referenced by <a href="#a409baefdf6be89e38deebefb129c1978">translateImmediate</a>, <a href="#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a> and <a href="#a972b23f3658215b06333703a6099eeb1">translateSrcIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### debug {#ae0228f36529f75f692753ef96d725012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define debug(s)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>(dbgs() &lt;&lt; __LINE__ &lt;&lt; ": " &lt;&lt; s);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>


<p>Referenced by <a href="#adb1fcba65d61d145b053ee0217b3dee7">fixupReg</a>, <a href="#a42be988af3ae0e352befa7189bd50936">readOperands</a>, <a href="#ae99d82425a463a5dd5413112fda5ed17">translateInstruction</a>, <a href="#a39a264ff5629dff4dc2a278f3848b4df">translateMaskRegister</a>, <a href="#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>, <a href="#aace6b74b8ffb4a67a94c8720813f18c2">translateRM</a>, <a href="#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a> and <a href="#aea1e232218bf327acf353b1f07db2f86">translateRMRegister</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"x86-disassembler"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>

</div>
</div>

### ENTRY {#a168a41dfc8e956c6180862aeca885db1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(x)&nbsp;&nbsp;&nbsp;X86::x,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1931 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>

</div>
</div>

### ENTRY {#a4dbab080ad769a5f716ded6e9f272748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(x)&nbsp;&nbsp;&nbsp;case EA_BASE_##x:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>

</div>
</div>

### ENTRY {#ab7afd582f1c8713d60dbff8569cb6f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(x)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case EA_REG_##x:                                                    \
    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a9fafc367cabbdce17ed971f70373c7c9">mcInst.addOperand</a>(MCOperand::createReg(X86::x)); break;
</div>
</dd>
</dl>

<p>Definition at line 2125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>

</div>
</div>

### ENTRY {#a2201f841c4c6a1aec7f1e04fb00b0cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(x)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">      case SIB_BASE_##x:                                  \
        baseReg = MCOperand::createReg(X86::x); break;
</div>
</dd>
</dl>

<p>Definition at line 2172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>

</div>
</div>

### ENTRY {#a9f201612cb32816265e25b6101b1f1e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(x)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">      case SIB_INDEX_##x:                                 \
        indexReg = MCOperand::createReg(X86::x); break;
</div>
</dd>
</dl>

<p>Definition at line 2187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>

</div>
</div>

### ENTRY {#aef1fa1f9600408331f991a35c71e628d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(x)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">      case EA_BASE_##x:                                 \
        baseReg = MCOperand::createReg(X86::x); break;
</div>
</dd>
</dl>

<p>Definition at line 2265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>

</div>
</div>

### ENTRY {#aec82111a7fbe4a315c1177a90ccc5a3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(x)&nbsp;&nbsp;&nbsp;case EA_REG_##x:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>

</div>
</div>

### GENERIC\_FIXUP\_FUNC {#a9a556ad6d7ad3eb7fe546bb644b2ba41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GENERIC_FIXUP_FUNC(name, base, prefix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
