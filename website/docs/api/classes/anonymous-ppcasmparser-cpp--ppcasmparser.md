---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCAsmParser` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{PPCAsmParser.cpp}::PPCAsmParser { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a> - Generic interface to target specific assembly parsers. <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0efcbd6994e6911e287aca986bc6dd99">Warning</a> (SMLoc L, const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac132d1b59f95f35834fe900c068e64d8">isPPC64</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af98fc5bd4f7561f307d3caab5ca943b2">matchRegisterName</a> (int64_t &amp;IntVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d3fba354ad3fc8ff4015c14231508d2">parseRegister</a> (MCRegister &amp;Reg, SMLoc &amp;StartLoc, SMLoc &amp;EndLoc) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35f540eead972b2ab328ab9242ee0c9">tryParseRegister</a> (MCRegister &amp;Reg, SMLoc &amp;StartLoc, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryParseRegister - parse one register if possible <a href="#ae35f540eead972b2ab328ab9242ee0c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af01962ed91d329e1cacb4c5339179952">extractModifierFromExpr</a> (const MCExpr *E, PPCMCExpr::VariantKind &amp;Variant)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract. <a href="#af01962ed91d329e1cacb4c5339179952">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633a16a1a6339e98c22828f014bcd2d1">fixupVariantKind</a> (const MCExpr *E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find all VK_TLSGD/VK_TLSLD symbol references in expression and replace them by VK_PPC_TLSGD/VK_PPC_TLSLD. <a href="#a633a16a1a6339e98c22828f014bcd2d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0929e68fcb925324e311b23bdda92c49">parseExpression</a> (const MCExpr *&amp;EVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This differs from the default "parseExpression" in that it handles modifiers. <a href="#a0929e68fcb925324e311b23bdda92c49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a369d5cc2dad8c37b3808d979556da89c">parseOperand</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This handles registers in the form 'NN', 'rNN' for <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> platforms and rNN for <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a>. <a href="#a369d5cc2dad8c37b3808d979556da89c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32d2b4d41389caa2fd9b0ff91a7d30d1">parseDirectiveWord</a> (unsigned Size, AsmToken ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>::= .word [ expression (, expression)* ] <a href="#a32d2b4d41389caa2fd9b0ff91a7d30d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a502c0ffbb3f63c8639c80e7771fd899f">parseDirectiveTC</a> (unsigned Size, AsmToken ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>::= .tc [ symbol (, expression)* ] <a href="#a502c0ffbb3f63c8639c80e7771fd899f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef5ef527ff7236b893e7004334082378">parseDirectiveMachine</a> (SMLoc L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> platforms. <a href="#aef5ef527ff7236b893e7004334082378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b88f00e90f625986c9737ee3ae32ba8">parseDirectiveAbiVersion</a> (SMLoc L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>::= .abiversion constant-expression <a href="#a3b88f00e90f625986c9737ee3ae32ba8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef2a7ec9f335c841540d92e9f954f9cc">parseDirectiveLocalEntry</a> (SMLoc L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>::= .localentry symbol, expression <a href="#aef2a7ec9f335c841540d92e9f954f9cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf0acc9dd2ac23d392fbb9984571d5f">parseGNUAttribute</a> (SMLoc L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56069b4441b91006c71e7b2394747611">matchAndEmitInstruction</a> (SMLoc IDLoc, unsigned &amp;Opcode, OperandVector &amp;Operands, MCStreamer &amp;Out, uint64_t &amp;ErrorInfo, bool MatchingInlineAsm) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recognize a series of operands of a parsed instruction as an actual MCInst and emit it to the specified MCStreamer. <a href="#a56069b4441b91006c71e7b2394747611">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a616aeaca312b7bd74f87bd81864fc9a4">processInstruction</a> (MCInst &amp;Inst, const OperandVector &amp;Ops)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79d43af706ab1701526379014ab75ce5">IsPPC64</a></td>
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

## Auto-generated Match Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2b6530e4b401fcf228743691fb0d918">PPCAsmParser</a> (const MCSubtargetInfo &amp;STI, MCAsmParser &amp;, const MCInstrInfo &amp;MII, const MCTargetOptions &amp;Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#ae2b6530e4b401fcf228743691fb0d918">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a8526125b46eeca9eb066fedddefa6f">parseInstruction</a> (ParseInstructionInfo &amp;Info, StringRef Name, SMLoc NameLoc, OperandVector &amp;Operands) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an instruction mnemonic followed by its operands. <a href="#a7a8526125b46eeca9eb066fedddefa6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e9209ef161dfa2b45ab9f122f2ada34">ParseDirective</a> (AsmToken DirectiveID) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses the <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> specific directives. <a href="#a0e9209ef161dfa2b45ab9f122f2ada34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8dd7af94a4ebc080910c6f8578eb848">validateTargetOperandClass</a> (MCParsedAsmOperand &amp;Op, unsigned Kind) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow a target to add special case operand matching for things that tblgen doesn't/can't handle effectively. <a href="#ad8dd7af94a4ebc080910c6f8578eb848">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b4948f02a577916d3f3e844f5bee16c">applyModifierToExpr</a> (const MCExpr *E, MCSymbolRefExpr::VariantKind, MCContext &amp;Ctx) override</td>
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


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Functions

### extractModifierFromExpr() {#af01962ed91d329e1cacb4c5339179952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * PPCAsmParser::extractModifierFromExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43ae">PPCMCExpr::VariantKind</a> &amp; Variant)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">@<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea2db95e8e1a9267b7a1188556b2013b33">l</a>/@ha </span></span></div>

</div>


<p>modifier from expression. Recursively scan the expression and check for VK_PPC_LO/HI/HA symbol variants. If all symbols with modifier use the same variant, return the corresponding <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43ae">PPCMCExpr::VariantKind</a>, and a modified expression using the default symbol variant. Otherwise, return NULL.</p>


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### fixupVariantKind() {#a633a16a1a6339e98c22828f014bcd2d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * PPCAsmParser::fixupVariantKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find all VK_TLSGD/VK_TLSLD symbol references in expression and replace them by VK_PPC_TLSGD/VK_PPC_TLSLD.</p>


<p>This is necessary to avoid having <em>GLOBAL_OFFSET_TABLE</em> created via ELFObjectWriter::RelocNeedsGOT. FIXME: This is a hack.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### isPPC64() {#ac132d1b59f95f35834fe900c068e64d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCAsmParser::isPPC64 ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### matchAndEmitInstruction() {#a56069b4441b91006c71e7b2394747611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmParser::matchAndEmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, unsigned &amp; Opcode, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, uint64_t &amp; ErrorInfo, bool MatchingInlineAsm)</td>
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

<p>Recognize a series of operands of a parsed instruction as an actual MCInst and emit it to the specified MCStreamer.</p>


<p>This returns false on success and returns true on failure to match.</p>


<p>On failure, the target parser is responsible for emitting a diagnostic explaining the match failure.</p>


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### matchRegisterName() {#af98fc5bd4f7561f307d3caab5ca943b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister PPCAsmParser::matchRegisterName (int64_t &amp; IntVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveAbiVersion() {#a3b88f00e90f625986c9737ee3ae32ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmParser::parseDirectiveAbiVersion (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>::= .abiversion constant-expression</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveLocalEntry() {#aef2a7ec9f335c841540d92e9f954f9cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmParser::parseDirectiveLocalEntry (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>::= .localentry symbol, expression</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveMachine() {#aef5ef527ff7236b893e7004334082378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmParser::parseDirectiveMachine (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> platforms.</p>


<p>::= .machine [ cpu | "push" | "pop" ]</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveTC() {#a502c0ffbb3f63c8639c80e7771fd899f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmParser::parseDirectiveTC (unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>::= .tc [ symbol (, expression)* ]</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveWord() {#a32d2b4d41389caa2fd9b0ff91a7d30d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmParser::parseDirectiveWord (unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>::= .word [ expression (, expression)* ]</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### parseExpression() {#a0929e68fcb925324e311b23bdda92c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmParser::parseExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; EVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This differs from the default "parseExpression" in that it handles modifiers.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### parseGNUAttribute() {#a4bf0acc9dd2ac23d392fbb9984571d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmParser::parseGNUAttribute (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### parseOperand() {#a369d5cc2dad8c37b3808d979556da89c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmParser::parseOperand (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This handles registers in the form 'NN', 'rNN' for <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> platforms and rNN for <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a>.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### parseRegister() {#a2d3fba354ad3fc8ff4015c14231508d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmParser::parseRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### processInstruction() {#a616aeaca312b7bd74f87bd81864fc9a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCAsmParser::processInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### tryParseRegister() {#ae35f540eead972b2ab328ab9242ee0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus PPCAsmParser::tryParseRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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

<p>tryParseRegister - parse one register if possible</p>


<p>Check whether a register specification can be parsed at the current location, without failing the entire parse if it can't. Must not consume tokens if the parse fails.</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### Warning() {#a0efcbd6994e6911e287aca986bc6dd99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCAsmParser::Warning (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsPPC64 {#a79d43af706ab1701526379014ab75ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{PPCAsmParser.cpp}::PPCAsmParser::IsPPC64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Auto-generated Match Functions



<p>{</p>


### applyModifierToExpr {#a7b4948f02a577916d3f3e844f5bee16c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * PPCAsmParser::applyModifierToExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985">MCSymbolRefExpr::VariantKind</a> Variant, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a8c6a84155fa8a775442739e6a11e5a95">llvm::PPCMCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a8b7bdf367ac57c04cfe5fc65738f8746">llvm::MCSymbolRefExpr::VK_PPC_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aead1c4a469bf794649572d583d82fb5298">llvm::PPCMCExpr::VK_PPC_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a48fe9f2486a3c190a9f1f32063d6c6bd">llvm::MCSymbolRefExpr::VK_PPC_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aeaeb7e6ae36702d248a38ef973670b1c72">llvm::PPCMCExpr::VK_PPC_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a91211d602833eef75759d4d8be28ef17">llvm::MCSymbolRefExpr::VK_PPC_HIGH</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aea03aeb8c55ac38ce58e6b2e5002544ab8">llvm::PPCMCExpr::VK_PPC_HIGH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a1b3b1911c7fcbf11d06e26da2a953c61">llvm::MCSymbolRefExpr::VK_PPC_HIGHA</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aeaa2d04a0ea8277a37914bc88bcb74a1fe">llvm::PPCMCExpr::VK_PPC_HIGHA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ae9c8307d1eb21a7958aa53353d5db45b">llvm::MCSymbolRefExpr::VK_PPC_HIGHER</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aea3222f18d25f03f5eae1ef158e6adc662">llvm::PPCMCExpr::VK_PPC_HIGHER</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a597d0a70484140ad41301e773a72f472">llvm::MCSymbolRefExpr::VK_PPC_HIGHERA</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aea582641ec46c5e9d10297757c85d52f1a">llvm::PPCMCExpr::VK_PPC_HIGHERA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a372aaaee0e711730b3bfba5d094da61c">llvm::MCSymbolRefExpr::VK_PPC_HIGHEST</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aea387e97ac9905a19c04eec775014d290e">llvm::PPCMCExpr::VK_PPC_HIGHEST</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a7a924adae900e08a5ab61485f50c49f1">llvm::MCSymbolRefExpr::VK_PPC_HIGHESTA</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aea1e58d5555819cc4524917eb5d6a8f9d9">llvm::PPCMCExpr::VK_PPC_HIGHESTA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2de16a7019f22064bed686092ccc8697">llvm::MCSymbolRefExpr::VK_PPC_LO</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aeabfdba0fefcc5a7d5598bbdf3d5ca50b2">llvm::PPCMCExpr::VK_PPC_LO</a>.</p>

</div>
</div>

### ParseDirective {#a0e9209ef161dfa2b45ab9f122f2ada34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmParser::ParseDirective (<a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> DirectiveID)</td>
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

<p>Parses the <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> specific directives.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#aefa517e84a358fccd59fb1815b87fa44">llvm::AsmToken::getIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a16611db1be4d04f03c570d9302504c04">llvm::AsmToken::getLoc</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a6480a22ac6ebd233e909aaaaf62b07c7">anonymous{PPCAsmParser.cpp}::PPCOperand::isPPC64</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>

</div>
</div>

### parseInstruction {#a7a8526125b46eeca9eb066fedddefa6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmParser::parseInstruction (<a href="/web-llvm/docs/api/structs/llvm/parseinstructioninfo">ParseInstructionInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
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

<p>Parse an instruction mnemonic followed by its operands.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ade80d23dae3697bbc7e8c429da708dc3">anonymous{PPCAsmParser.cpp}::PPCOperand::CreateToken</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ad4116a0530b455559f9a6472ab5ea9ea">anonymous{PPCAsmParser.cpp}::PPCOperand::CreateTokenWithStringCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a383385f08edecc84e33ca9d00e5ec56d">anonymous{PPCAsmParser.cpp}::PPCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a7428ebe08f75a705043e1bd005d0542d">llvm::SMLoc::getPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a6480a22ac6ebd233e909aaaaf62b07c7">anonymous{PPCAsmParser.cpp}::PPCOperand::isPPC64</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a5f7e780fcd1fca846da3453e80b9956b">anonymous{PPCAsmParser.cpp}::PPCOperand::isU1Imm</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a>, <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#ad0f54a163ac500b144590640c6f1eb6b">anonymous{Path.cpp}::StringRef::npos</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a0f14a9468b4224a3f7ab96eaef0b99ca">llvm::MCAsmParserExtension::parseOptionalToken</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a554ce8cd5542f0ad063a7b0b1b68a140">llvm::MCAsmParserExtension::parseToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac97d79769cee46bf3915460c278d5de6">llvm::AsmToken::Plus</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### PPCAsmParser {#ae2b6530e4b401fcf228743691fb0d918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCAsmParser.cpp}::PPCAsmParser::PPCAsmParser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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

<p>}</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a32cd9ae9007321c391a62dd4bd69d268">llvm::MCTargetAsmParser::MCTargetAsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a9bc309121dfab6b0c03a026eec7b2ab7">llvm::MCTargetAsmParser::setAvailableFeatures</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aff6afefbe685c9940c3e082c7f576df6">llvm::MCTargetAsmParser::STI</a>.</p>

</div>
</div>

### validateTargetOperandClass {#ad8dd7af94a4ebc080910c6f8578eb848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PPCAsmParser::validateTargetOperandClass (<a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">MCParsedAsmOperand</a> &amp; Op, unsigned Kind)</td>
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

<p>Allow a target to add special case operand matching for things that tblgen doesn't/can't handle effectively.</p>


<p>For example, literal immediates on ARM. TableGen expects a token operand, but the parser will recognize them as immediates.</p>


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a29cb086c359baadd9df6e5f101e41007a36e5dd518d3d92d2d6207a9ed03d6b48">llvm::MCTargetAsmParser::Match_InvalidOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a29cb086c359baadd9df6e5f101e41007a2d220d934e235f8d0ff1eb07adf2b483">llvm::MCTargetAsmParser::Match_Success</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
