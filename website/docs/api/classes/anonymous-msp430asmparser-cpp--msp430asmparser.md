---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-msp430asmparser-cpp-/msp430asmparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MSP430AsmParser` Class

<p>Parses <a href="/web-llvm/docs/api/namespaces/llvm/msp430">MSP430</a> assembly from a stream. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MSP430AsmParser.cpp}::MSP430AsmParser { ... }
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeee2037cb1c814a1d922cdf2d498ff6">matchAndEmitInstruction</a> (SMLoc IDLoc, unsigned &amp;Opcode, OperandVector &amp;Operands, MCStreamer &amp;Out, uint64_t &amp;ErrorInfo, bool MatchingInlineAsm) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recognize a series of operands of a parsed instruction as an actual MCInst and emit it to the specified MCStreamer. <a href="#aaeee2037cb1c814a1d922cdf2d498ff6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5466f97d46f66de4bb22ce09c854c3">parseRegister</a> (MCRegister &amp;Reg, SMLoc &amp;StartLoc, SMLoc &amp;EndLoc) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6abb302b364e75af522ff2a94ad3538">tryParseRegister</a> (MCRegister &amp;Reg, SMLoc &amp;StartLoc, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryParseRegister - parse one register if possible <a href="#ad6abb302b364e75af522ff2a94ad3538">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799f0cb77085b4d2fbe3b1ac94f4bc16">parseInstruction</a> (ParseInstructionInfo &amp;Info, StringRef Name, SMLoc NameLoc, OperandVector &amp;Operands) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse one assembly instruction. <a href="#a799f0cb77085b4d2fbe3b1ac94f4bc16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85a615ad87812524943f9dd240869170">parseDirective</a> (AsmToken DirectiveID) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses a target-specific assembler directive. <a href="#a85a615ad87812524943f9dd240869170">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac48f707288fe9b8d0ba036df96e63a2a">ParseDirectiveRefSym</a> (AsmToken DirectiveID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bcb174ba42a690362c67450d0db607c">validateTargetOperandClass</a> (MCParsedAsmOperand &amp;Op, unsigned Kind) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow a target to add special case operand matching for things that tblgen doesn't/can't handle effectively. <a href="#a4bcb174ba42a690362c67450d0db607c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5b34079f565279d9747a054de474e6">parseJccInstruction</a> (ParseInstructionInfo &amp;Info, StringRef Name, SMLoc NameLoc, OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df95dfb5e1629a1f80b87159b0cea9d">ParseOperand</a> (OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa90a70740b93fcba55dcb23bb45555d5">ParseLiteralValues</a> (unsigned Size, SMLoc L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b5dff22e7ae1f12d0fe8c38847513b">getParser</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmlexer">MCAsmLexer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a293dcc699300ddd5810e10ecad9a2dcf">getLexer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e7a38f7df63cd284b0f9138fb211bcf">STI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbaea41664a3111abcabdc47da6887ef">Parser</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a905de8d08677adcd6e6ee703ab0d1a94">MRI</a></td>
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

## Auto-generated Matcher Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44cab0dfc08a36646230b29e9e61cf45">MSP430AsmParser</a> (const MCSubtargetInfo &amp;STI, MCAsmParser &amp;Parser, const MCInstrInfo &amp;MII, const MCTargetOptions &amp;Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a44cab0dfc08a36646230b29e9e61cf45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Parses <a href="/web-llvm/docs/api/namespaces/llvm/msp430">MSP430</a> assembly from a stream.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Functions

### getLexer() {#a293dcc699300ddd5810e10ecad9a2dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmLexer &amp; anonymous{MSP430AsmParser.cpp}::MSP430AsmParser::getLexer ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### getParser() {#a44b5dff22e7ae1f12d0fe8c38847513b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmParser &amp; anonymous{MSP430AsmParser.cpp}::MSP430AsmParser::getParser ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### matchAndEmitInstruction() {#aaeee2037cb1c814a1d922cdf2d498ff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MSP430AsmParser::matchAndEmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, unsigned &amp; Opcode, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, uint64_t &amp; ErrorInfo, bool MatchingInlineAsm)</td>
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


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirective() {#a85a615ad87812524943f9dd240869170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus MSP430AsmParser::parseDirective (<a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> DirectiveID)</td>
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

<p>Parses a target-specific assembler directive.</p>


<p>The parser is positioned following the directive name. The target-specific directive parser should parse the entire directive doing or recording any target-specific work, or emit an error. On success, the entire line should be parsed up to and including the end-of-statement token. On failure, the parser is not required to read to the end of the line. If the directive is not target-specific, no tokens should be consumed and NoMatch is returned.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DirectiveID</td>
<td class="doxyParamItemDescription"><p>- The token identifying the directive.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### ParseDirectiveRefSym() {#ac48f707288fe9b8d0ba036df96e63a2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MSP430AsmParser::ParseDirectiveRefSym (<a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> DirectiveID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### parseInstruction() {#a799f0cb77085b4d2fbe3b1ac94f4bc16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MSP430AsmParser::parseInstruction (<a href="/web-llvm/docs/api/structs/llvm/parseinstructioninfo">ParseInstructionInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
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

<p>Parse one assembly instruction.</p>


<p>The parser is positioned following the instruction name. The target specific instruction parser should parse the entire instruction and construct the appropriate MCInst, or emit an error. On success, the entire line should be parsed up to and including the end-of-statement token. On failure, the parser is not required to read to the end of the line.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>- The instruction name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLoc</td>
<td class="doxyParamItemDescription"><p>- The source location of the name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Operands</td>
<td class="doxyParamItemDescription"><p>[out] - The list of parsed operands, this returns ownership of them to the caller.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on failure.</p></dd>
</dl>


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### parseJccInstruction() {#afd5b34079f565279d9747a054de474e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MSP430AsmParser::parseJccInstruction (<a href="/web-llvm/docs/api/structs/llvm/parseinstructioninfo">ParseInstructionInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### ParseLiteralValues() {#aa90a70740b93fcba55dcb23bb45555d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MSP430AsmParser::ParseLiteralValues (unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### ParseOperand() {#a1df95dfb5e1629a1f80b87159b0cea9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MSP430AsmParser::ParseOperand (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### parseRegister() {#afd5466f97d46f66de4bb22ce09c854c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MSP430AsmParser::parseRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### tryParseRegister() {#ad6abb302b364e75af522ff2a94ad3538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus MSP430AsmParser::tryParseRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### validateTargetOperandClass() {#a4bcb174ba42a690362c67450d0db607c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MSP430AsmParser::validateTargetOperandClass (<a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">MCParsedAsmOperand</a> &amp; Op, unsigned Kind)</td>
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


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MRI {#a905de8d08677adcd6e6ee703ab0d1a94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo* anonymous{MSP430AsmParser.cpp}::MSP430AsmParser::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### Parser {#acbaea41664a3111abcabdc47da6887ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmParser&amp; anonymous{MSP430AsmParser.cpp}::MSP430AsmParser::Parser</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### STI {#a3e7a38f7df63cd284b0f9138fb211bcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo&amp; anonymous{MSP430AsmParser.cpp}::MSP430AsmParser::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Auto-generated Matcher Functions



<p>{</p>


### MSP430AsmParser {#a44cab0dfc08a36646230b29e9e61cf45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MSP430AsmParser.cpp}::MSP430AsmParser::MSP430AsmParser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp; Parser, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a77a335167c72ea8bc771501825f81696">llvm::MCAsmParserExtension::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a32cd9ae9007321c391a62dd4bd69d268">llvm::MCTargetAsmParser::MCTargetAsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a9bc309121dfab6b0c03a026eec7b2ab7">llvm::MCTargetAsmParser::setAvailableFeatures</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
