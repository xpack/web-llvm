---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smloc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SMLoc` Class Reference

<p>Represents a location in source code. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SMLoc { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smloc-h">llvm/Support/SMLoc.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3a38b25ef8e21882535e4830b215b59">SMLoc</a> ()=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6465dd3014e97a8739501ddcd06f2f89">operator==</a> (const SMLoc &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a17794c513bafc6593c9bb77c9d76db">operator!=</a> (const SMLoc &amp;RHS) const</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb1e94b8fff61f549bcbd5a2780f6796">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7428ebe08f75a705043e1bd005d0542d">getPointer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b920c3608444186da7453030a6685d">Ptr</a> = nullptr</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ebb09610e55f63cfc55f28e3a56ad5">getFromPointer</a> (const char *Ptr)</td>
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

## Description {#details}

<p>Represents a location in source code.</p>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smloc-h">SMLoc.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SMLoc() {#af3a38b25ef8e21882535e4830b215b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SMLoc::SMLoc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smloc-h">SMLoc.h</a>.</p>


<p>Referenced by <a href="#a16ebb09610e55f63cfc55f28e3a56ad5">getFromPointer</a>, <a href="#a3a17794c513bafc6593c9bb77c9d76db">operator!=</a> and <a href="#a6465dd3014e97a8739501ddcd06f2f89">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a3a17794c513bafc6593c9bb77c9d76db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMLoc::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smloc-h">SMLoc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#af3a38b25ef8e21882535e4830b215b59">SMLoc</a>.</p>

</div>
</div>

### operator==() {#a6465dd3014e97a8739501ddcd06f2f89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMLoc::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smloc-h">SMLoc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#af3a38b25ef8e21882535e4830b215b59">SMLoc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPointer() {#a7428ebe08f75a705043e1bd005d0542d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::SMLoc::getPointer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smloc-h">SMLoc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp/#a596b6449296931e40cbfb38f8cb238c1">isAngleBracketString</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp/#a596b6449296931e40cbfb38f8cb238c1">isAngleBracketString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#a874fe455718e3ea10454347888391fc2">parseCC</a>, <a href="/web-llvm/docs/api/classes/llvm/llparser/#a2a854410b123568e0bb9824f0a3cb94c">llvm::LLParser::parseDIExpressionBodyAtBeginning</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#aa91d3c1b093e3561b948794724961f4b">anonymous{AsmParser.cpp}::AsmParser::parseIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#af6dea9845d70ac952115bdbe378dbea1">anonymous{MasmParser.cpp}::MasmParser::parseIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#adc0358b42d36242d132980b3fe8260de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a89eeee4c3ec5d281810e8ac7572ddee4">anonymous{ARMAsmParser.cpp}::ARMAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a7a8526125b46eeca9eb066fedddefa6f">anonymous{PPCAsmParser.cpp}::PPCAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a0cacf6ffb7a5ce2195bd33f0e9c0087c">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#ad81a87b3f8bbc548c08e343f068aab79">parseRD</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#a2a338087cbd108168ba920ad7906f6b8">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseShiftAmtImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#abdef83570b9c07195a0570f8744b2fc0">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseTailRelocSym</a>, <a href="/web-llvm/docs/api/classes/llvm/llparser/#a933523072cbd91ce32852b7b52a74d52">llvm::LLParser::parseTypeAtBeginning</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp/#ac27a97bbb42a7f0481f803251c65c237">rewritesSort</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp/#ac27a97bbb42a7f0481f803251c65c237">rewritesSort</a>.</p>

</div>
</div>

### isValid() {#abb1e94b8fff61f549bcbd5a2780f6796}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMLoc::isValid ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smloc-h">SMLoc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a1c3ac00eab4ed0328bc8c8942957c83b">anonymous{MasmParser.cpp}::MasmParser::parseRealValue</a> and <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a042b7e85ad239f80f6a079283a9faee6">llvm::SourceMgr::PrintMessage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ptr {#a07b920c3608444186da7453030a6685d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::SMLoc::Ptr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smloc-h">SMLoc.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getFromPointer() {#a16ebb09610e55f63cfc55f28e3a56ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::SMLoc::getFromPointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smloc-h">SMLoc.h</a>.</p>


<p>Reference <a href="#af3a38b25ef8e21882535e4830b215b59">SMLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/blockscalarnode/#a85f1cad503bb4c8ac78b28b75832d5b8">llvm::yaml::BlockScalarNode::BlockScalarNode</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ac71c43fb658be4df9989f55be8447e1d">llvm::FileCheckString::CheckDag</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#a36305f86aafd6d41b0c449eac6476efd">llvm::FileCheckString::CheckNext</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#a82944774d532e6adc41c92e29a00e2e9">llvm::FileCheckString::CheckSame</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#acde7256b4b06b4bd9b75088863c32265">llvm::X86Operand::CreateToken</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7d46d39efe0be42a72faf3e6db59de3f">anonymous{MIParser.cpp}::MIParser::error</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#aff3380c7e96d28b108876d8e7b66e341">llvm::SourceMgr::FindLocForLineAndColumn</a>, <a href="/web-llvm/docs/api/classes/llvm/errordiagnostic/#aef72f56d78c257c18bf803045c76eb19">llvm::ErrorDiagnostic::get</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a9e6496a765eb2a14512ca0d5f48185fa">llvm::AsmToken::getEndLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a16611db1be4d04f03c570d9302504c04">llvm::AsmToken::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/lllexer/#a81a6260afd03d49c34d264878ee536ec">llvm::LLLexer::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#a54bfbf3752a7a79c026b8ffe73308cb6">llvm::MCAsmLexer::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/tglexer/#ae6f58ed313b0cd532b86302fa6233296">llvm::TGLexer::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/tglexer/#a0764c89473b64b97aef3bb769eb3454e">llvm::TGLexer::getLocRange</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acdf08ebc749ce91001ea768a16da0605">llvm::SourceMgr::GetMessage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#aa17a6c6e72523074cf7ac54b52e7f304">incrementLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp/#a596b6449296931e40cbfb38f8cb238c1">isAngleBracketString</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp/#a596b6449296931e40cbfb38f8cb238c1">isAngleBracketString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#a874fe455718e3ea10454347888391fc2">parseCC</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a757668838f5767cbf28d9a5b1201a646">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#adc0358b42d36242d132980b3fe8260de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a89eeee4c3ec5d281810e8ac7572ddee4">anonymous{ARMAsmParser.cpp}::ARMAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a7a8526125b46eeca9eb066fedddefa6f">anonymous{PPCAsmParser.cpp}::PPCAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a0cacf6ffb7a5ce2195bd33f0e9c0087c">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a5c3abd5a0df4ec19738884622846a92b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpAttr</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#ad81a87b3f8bbc548c08e343f068aab79">parseRD</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#a2a338087cbd108168ba920ad7906f6b8">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseShiftAmtImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#abdef83570b9c07195a0570f8744b2fc0">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseTailRelocSym</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add17c7296500b889d12eb44d547a59ba">llvm::parseType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36921ed4710269eb17cd26f11e51a97f">llvm::PrintError</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a91f729b936911342abb6b606e0606cdc">llvm::Pattern::printVariableDefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1f879158cac2db013d4df1c1016930fc">llvm::PrintWarning</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#aa386d2cd704c6f1176a5aef1f0f178da">ProcessMatchResult</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/scalarnode/#a8cd838d3dcf1efd1367cbed9a0f8a69b">llvm::yaml::ScalarNode::ScalarNode</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/scanner/#a4406ec44082e06c99c2b7463dbf77b1c">llvm::yaml::Scanner::setError</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a246c8dfd4ca957b7da4d52cb7805650c">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseAdjImm0_63</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#ac9b49c99f803cb80be523228ede176e4">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseRegister</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smloc-h">SMLoc.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
