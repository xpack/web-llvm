---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcasmparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCAsmParser` Class Reference

<p>Generic assembler parser interface, for use by target specific assembly parsers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCAsmParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">llvm/MC/MCParser/MCAsmParser.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser">AsmParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The concrete assembly parser instance. <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser">MasmParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The concrete assembly parser instance. <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ecac29af2004375ccba91a8527a251">DirectiveHandler</a> = bool(*)(<a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension">MCAsmParserExtension</a> *, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ce3532c090e7b66928ff9a42dae508c">ExtensionDirectiveHandler</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension">MCAsmParserExtension</a> *, <a href="#aa8ecac29af2004375ccba91a8527a251">DirectiveHandler</a> &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cafc2281e28c0a263e484d4ed280d36">MCAsmParser</a> (const MCAsmParser &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b89d03df4325baa998c69d6ae8c95a">MCAsmParser</a> ()</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4ec749397fb66602fd7feadc0a444bf">~MCAsmParser</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74666f4edd91bcb2d1d86e222d53ba23">operator=</a> (const MCAsmParser &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd887f0964a96c5e02314deac1ac584f">addDirectiveHandler</a> (StringRef Directive, ExtensionDirectiveHandler Handler)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd600bd726e3f0dc6745757b8ff99322">addAliasForDirective</a> (StringRef Directive, StringRef Alias)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592091f24541a576ac6294b097a4061d">getSourceManager</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4e7ba9b1dd10c4262ff498f9a7dd397">getLexer</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer">MCAsmLexer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace7ef596d65729ae610db919be806113">getLexer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5501a0543911b575ec50e456ee228ae">getContext</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40ca835fddf3ca47f6b9a7bd43d929f0">getStreamer</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the output streamer for the assembler. <a href="#a40ca835fddf3ca47f6b9a7bd43d929f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6c7d84cb78a0d8586215b53b7bee33">getTargetParser</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af473082d59d84b25a63d18be49ecb271">setTargetParser</a> (MCTargetAsmParser &amp;P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97e3b31312d2e3411622872cb2ac6109">getAssemblerDialect</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3cf81a517d41f1357dfbdaa6607940a">setAssemblerDialect</a> (unsigned i)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e4af5e4d650f5bec85b99dfe0fc4d04">getShowParsedOperands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3cdd92e164e2004543e4a56811cbb2b">setShowParsedOperands</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1b2fb0acb2550076d5dcab1039b2bb8">Run</a> (bool NoInitialTextSection, bool NoFinalize=false)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the parser on the input source buffer. <a href="#ab1b2fb0acb2550076d5dcab1039b2bb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af57aeac4a24de62226147e49b62f34b5">setParsingMSInlineAsm</a> (bool V)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81bd71316fbce01f2e8055dcc8fdb062">isParsingMSInlineAsm</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fa72434836eef7654ebee54ca467945">discardLTOSymbol</a> (StringRef) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67ead6c5858726cf466bfa5ded2b5ab7">isParsingMasm</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30603fa16428eeb671da88714c6ef874">defineMacro</a> (StringRef Name, StringRef Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add0e53028d15679b96b8f66849b4e971">lookUpField</a> (StringRef Name, AsmFieldInfo &amp;Info) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad75338a56ab81e83583aafaf2f2f1246">lookUpField</a> (StringRef Base, StringRef Member, AsmFieldInfo &amp;Info) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9dea6fd0f51f338ae588d9cef3fa6e8">lookUpType</a> (StringRef Name, AsmTypeInfo &amp;Info) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc2a0f9ef9ceee382a5644dedf7e7d7d">parseMSInlineAsm</a> (std::string &amp;AsmString, unsigned &amp;NumOutputs, unsigned &amp;NumInputs, SmallVectorImpl&lt; std::pair&lt; void *, bool &gt; &gt; &amp;OpDecls, SmallVectorImpl&lt; std::string &gt; &amp;Constraints, SmallVectorImpl&lt; std::string &gt; &amp;Clobbers, const MCInstrInfo *MII, MCInstPrinter *IP, MCAsmParserSemaCallback &amp;SI)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse MS-style inline assembly. <a href="#afc2a0f9ef9ceee382a5644dedf7e7d7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51860cb8160776d84628d48f53e26a62">Note</a> (SMLoc L, const Twine &amp;Msg, SMRange Range=std::nullopt)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a note at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>. <a href="#a51860cb8160776d84628d48f53e26a62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0573f4b31f141fba5ffffe9b0a53688">Warning</a> (SMLoc L, const Twine &amp;Msg, SMRange Range=std::nullopt)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a warning at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>. <a href="#ab0573f4b31f141fba5ffffe9b0a53688">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe58695435b93e0599ed2f77e877a0aa">Error</a> (SMLoc L, const Twine &amp;Msg, SMRange Range=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an error at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>. <a href="#afe58695435b93e0599ed2f77e877a0aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198ec1b8458ce38de9ad18a6f483c278">printError</a> (SMLoc L, const Twine &amp;Msg, SMRange Range=std::nullopt)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an error at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>. <a href="#a198ec1b8458ce38de9ad18a6f483c278">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4947313871f8935468ae02f6621260c8">hasPendingError</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25158c234ca9e60f3976a36d7d6ef271">printPendingErrors</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47420f87b1401934de51a165550a7481">clearPendingErrors</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a189e6cc46ddc7ca69bddd7f1a757a736">addErrorSuffix</a> (const Twine &amp;Suffix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a922370d34654382dd4ff2b8a1a9c50d6">Lex</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the next <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> in the stream, possibly handling file inclusion first. <a href="#a922370d34654382dd4ff2b8a1a9c50d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a607ccd51956df621f1f5ea07c5d3b2c6">getTok</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> from the stream. <a href="#a607ccd51956df621f1f5ea07c5d3b2c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca3b32b0f673fcda41b604540f49a4f9">TokError</a> (const Twine &amp;Msg, SMRange Range=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report an error at the current lexer location. <a href="#aca3b32b0f673fcda41b604540f49a4f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe743277c072b490a3f6bfc7dd593d1">parseTokenLoc</a> (SMLoc &amp;Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137818cb489ba17770a17ee9eb6f269e">parseToken</a> (AsmToken::TokenKind T, const Twine &amp;Msg="unexpected token")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fe5bbdb7d87187478d77f3a1d5a2a93">parseOptionalToken</a> (AsmToken::TokenKind T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to parse and consume token, returning true on success. <a href="#a7fe5bbdb7d87187478d77f3a1d5a2a93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad264107ceef36c0f353085894c7c0c76">parseComma</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a709fe7ec3803940386b0588e9a1c6f02">parseRParen</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b442abcc8f942ce12304975367e1fa2">parseEOL</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf0064a97b1ecde598fee1ed3d8cf52">parseEOL</a> (const Twine &amp;ErrMsg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0796f036e832b4b5e10f6e31e77ca7c8">parseMany</a> (function_ref&lt; bool()&gt; parseOne, bool hasComma=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d9acbc65c25f0330cd2d8d6baded980">parseIntToken</a> (int64_t &amp;V, const Twine &amp;ErrMsg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3030316a1ebebb07ea5bfef630daa790">check</a> (bool P, const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dc060fdfce77b45a20dbf3d6dd22129">check</a> (bool P, SMLoc Loc, const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a9de5bc4280ee403d0f61304e5fe4fa">parseIdentifier</a> (StringRef &amp;Res)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an identifier or string (as a quoted identifier) and set <span class="doxyComputerOutput">Res</span> to the identifier contents. <a href="#a6a9de5bc4280ee403d0f61304e5fe4fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5530d71c3414b44f2205d3a3b3026d82">parseStringToEndOfStatement</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse up to the end of statement and return the contents from the current token until the end of the statement; the current token on exit will be either the EndOfStatement or EOF. <a href="#a5530d71c3414b44f2205d3a3b3026d82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d3280ac9b0dc7d25571a60d39a88db4">parseEscapedString</a> (std::string &amp;Data)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the current token as a string which may include escaped characters and return the string contents. <a href="#a2d3280ac9b0dc7d25571a60d39a88db4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe40caf4aef5f3308433afaa025cfe34">parseAngleBracketString</a> (std::string &amp;Data)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an angle-bracket delimited string at the current position if one is present, returning the string contents. <a href="#abe40caf4aef5f3308433afaa025cfe34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b67ddc02c5708bb4654fc721b0658d">eatToEndOfStatement</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip to the end of the current statement, for error recovery. <a href="#a05b67ddc02c5708bb4654fc721b0658d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582bb95a08ad05ff3bd5de25a92edd4a">parseExpression</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an arbitrary expression. <a href="#a582bb95a08ad05ff3bd5de25a92edd4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83b5779cb89b1af4150d7022b7f751c9">parseExpression</a> (const MCExpr *&amp;Res)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e3a1b10f62aa9225cec49f8f6195282">parsePrimaryExpr</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc, AsmTypeInfo *TypeInfo)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a primary expression. <a href="#a5e3a1b10f62aa9225cec49f8f6195282">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d85402d1158f9d97c9c35897b90d786">parseParenExpression</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an arbitrary expression, assuming that an initial '(' has already been consumed. <a href="#a7d85402d1158f9d97c9c35897b90d786">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8413e05e0522dff8eb604bcd891d0aa">parseAbsoluteExpression</a> (int64_t &amp;Res)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an expression which must evaluate to an absolute value. <a href="#ad8413e05e0522dff8eb604bcd891d0aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62ed88c59f6b7e53e099069e0b948db2">checkForValidSection</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure that we have a valid section set in the streamer. <a href="#a62ed88c59f6b7e53e099069e0b948db2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93423cf3a4d1e6c6ab8e473305a44cd5">parseParenExprOfDepth</a> (unsigned ParenDepth, const MCExpr *&amp;Res, SMLoc &amp;EndLoc)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse an arbitrary expression of a specified parenthesis depth, assuming that the initial '(' characters have already been consumed. <a href="#a93423cf3a4d1e6c6ab8e473305a44cd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae70fbaacac6a12bfc3904b3e1af622bb">parseGNUAttribute</a> (SMLoc L, int64_t &amp;Tag, int64_t &amp;IntegerValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a .gnu_attribute. <a href="#ae70fbaacac6a12bfc3904b3e1af622bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcasmparser/mcpendingerror">MCPendingError</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cdbb86564e6641120ab773fac6a62d4">PendingErrors</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afad5b9aac74030a159903f3cf64c481c">HadError</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag tracking whether any errors have been encountered. <a href="#afad5b9aac74030a159903f3cf64c481c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a256770fb45edae64541efa7f31ea1d18">ShowParsedOperands</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae53fc77de81f2e5b009b61c2b625f82d">TargetParser</a> = nullptr</td>
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

<p>Generic assembler parser interface, for use by target specific assembly parsers.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### DirectiveHandler {#aa8ecac29af2004375ccba91a8527a251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MCAsmParser::DirectiveHandler =  bool (*)(MCAsmParserExtension*, StringRef, SMLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### ExtensionDirectiveHandler {#a9ce3532c090e7b66928ff9a42dae508c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MCAsmParser::ExtensionDirectiveHandler = 
      std::pair&lt;MCAsmParserExtension*, DirectiveHandler&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCAsmParser() {#a6cafc2281e28c0a263e484d4ed280d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCAsmParser::MCAsmParser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="#af7b89d03df4325baa998c69d6ae8c95a">MCAsmParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### MCAsmParser() {#af7b89d03df4325baa998c69d6ae8c95a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmParser::MCAsmParser ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="#ace7ef596d65729ae610db919be806113">getLexer</a>, <a href="#a6cafc2281e28c0a263e484d4ed280d36">MCAsmParser</a> and <a href="#a74666f4edd91bcb2d1d86e222d53ba23">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MCAsmParser() {#ac4ec749397fb66602fd7feadc0a444bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmParser::~MCAsmParser ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a74666f4edd91bcb2d1d86e222d53ba23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmParser &amp; llvm::MCAsmParser::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="#af7b89d03df4325baa998c69d6ae8c95a">MCAsmParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAliasForDirective() {#abd600bd726e3f0dc6745757b8ff99322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCAsmParser::addAliasForDirective (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Alias)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsasmparser/#a96cded7294d54537fbb8eb5a6148448a">anonymous{MipsAsmParser.cpp}::MipsAsmParser::MipsAsmParser</a> and <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a25dceb5ece7a0cba343ac8f7341ce4f2">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::SystemZAsmParser</a>.</p>

</div>
</div>

### addDirectiveHandler() {#afd887f0964a96c5e02314deac1ac584f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCAsmParser::addDirectiveHandler (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="#a9ce3532c090e7b66928ff9a42dae508c">ExtensionDirectiveHandler</a> Handler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### addErrorSuffix() {#a189e6cc46ddc7ca69bddd7f1a757a736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::addErrorSuffix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Suffix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012">llvm::AsmToken::Error</a>, <a href="#a607ccd51956df621f1f5ea07c5d3b2c6">getTok</a>, <a href="#a922370d34654382dd4ff2b8a1a9c50d6">Lex</a>, <a href="#a7cdbb86564e6641120ab773fac6a62d4">PendingErrors</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#ae2cc7378ca67e19c45648f7800686933">llvm::Twine::toVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a3fa87f63e16161bde91f88f7d4484c8a">llvm::MCAsmParserExtension::addErrorSuffix</a>.</p>

</div>
</div>

### check() {#a3030316a1ebebb07ea5bfef630daa790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::check (bool P, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="#a3030316a1ebebb07ea5bfef630daa790">check</a>, <a href="#a607ccd51956df621f1f5ea07c5d3b2c6">getTok</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a3030316a1ebebb07ea5bfef630daa790">check</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a9996e014bb8433cf33e137f0a3f21194">llvm::MCAsmParserExtension::check</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ac5cfb11304bab346d56939a2de5f97bd">llvm::MCAsmParserExtension::check</a>.</p>

</div>
</div>

### check() {#a6dc060fdfce77b45a20dbf3d6dd22129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::check (bool P, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### checkForValidSection() {#a62ed88c59f6b7e53e099069e0b948db2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::checkForValidSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Ensure that we have a valid section set in the streamer.</p>


<p>Otherwise, report an error and switch to .text.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- False on success.</p></dd>
</dl>


<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### clearPendingErrors() {#a47420f87b1401934de51a165550a7481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmParser::clearPendingErrors ()</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="#a7cdbb86564e6641120ab773fac6a62d4">PendingErrors</a>.</p>

</div>
</div>

### defineMacro() {#a30603fa16428eeb671da88714c6ef874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::defineMacro (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### discardLTOSymbol() {#a6fa72434836eef7654ebee54ca467945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::discardLTOSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### eatToEndOfStatement() {#a05b67ddc02c5708bb4654fc721b0658d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCAsmParser::eatToEndOfStatement ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skip to the end of the current statement, for error recovery.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### Error() {#afe58695435b93e0599ed2f77e877a0aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::Error (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an error at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>.</p>


<p>This may be modified before being emitted.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The return value is always true, as an idiomatic convenience to clients.</p></dd>
</dl>


<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012">llvm::AsmToken::Error</a>, <a href="#aa4e7ba9b1dd10c4262ff498f9a7dd397">getLexer</a>, <a href="#a607ccd51956df621f1f5ea07c5d3b2c6">getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#ac53eb41641168379037fde8952d5f01e">llvm::MCAsmLexer::Lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mcasmparser/mcpendingerror/#a1def4a048e32d16864473e0f6fe82dec">llvm::MCAsmParser::MCPendingError::Loc</a>, <a href="/web-llvm/docs/api/structs/llvm/mcasmparser/mcpendingerror/#a99b6f8e4fcb44f2bd4017e71685fbca0">llvm::MCAsmParser::MCPendingError::Msg</a>, <a href="#a7cdbb86564e6641120ab773fac6a62d4">PendingErrors</a>, <a href="/web-llvm/docs/api/structs/llvm/mcasmparser/mcpendingerror/#ad6be755a547950c83558d03f02993795">llvm::MCAsmParser::MCPendingError::Range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#ae2cc7378ca67e19c45648f7800686933">llvm::Twine::toVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ab34712e7b8a90ef1894fd6a3b483179f">llvm::MCAsmParserExtension::Error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>.</p>

</div>
</div>

### getAssemblerDialect() {#a97e3b31312d2e3411622872cb2ac6109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::MCAsmParser::getAssemblerDialect ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### getContext() {#af5501a0543911b575ec50e456ee228ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MCContext &amp; llvm::MCAsmParser::getContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>.</p>

</div>
</div>

### getLexer() {#aa4e7ba9b1dd10c4262ff498f9a7dd397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MCAsmLexer &amp; llvm::MCAsmParser::getLexer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="#afe58695435b93e0599ed2f77e877a0aa">Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#a6c0aead93728457ceebf342312b92807">expectAbsExpression</a>, <a href="#ace7ef596d65729ae610db919be806113">getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="#a607ccd51956df621f1f5ea07c5d3b2c6">getTok</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#a7a374b13bc9d10c9298dd591ee50fc82">parseExpr</a> and <a href="#aca3b32b0f673fcda41b604540f49a4f9">TokError</a>.</p>

</div>
</div>

### getLexer() {#ace7ef596d65729ae610db919be806113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmLexer &amp; llvm::MCAsmParser::getLexer ()</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>References <a href="#aa4e7ba9b1dd10c4262ff498f9a7dd397">getLexer</a> and <a href="#af7b89d03df4325baa998c69d6ae8c95a">MCAsmParser</a>.</p>

</div>
</div>

### getShowParsedOperands() {#a6e4af5e4d650f5bec85b99dfe0fc4d04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmParser::getShowParsedOperands ()</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="#a256770fb45edae64541efa7f31ea1d18">ShowParsedOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#afaaaf7da6379fe3994da86bf71024ddc">anonymous{AsmParser.cpp}::AsmParser::parseAndMatchAndEmitTargetInstruction</a>.</p>

</div>
</div>

### getSourceManager() {#a592091f24541a576ac6294b097a4061d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SourceMgr &amp; llvm::MCAsmParser::getSourceManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a0401ba9b53470dbdefa8e78d8b344e5d">llvm::MCAsmParserExtension::getSourceManager</a>.</p>

</div>
</div>

### getStreamer() {#a40ca835fddf3ca47f6b9a7bd43d929f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MCStreamer &amp; llvm::MCAsmParser::getStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the output streamer for the assembler.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>.</p>

</div>
</div>

### getTargetParser() {#afc6c7d84cb78a0d8586215b53b7bee33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCTargetAsmParser &amp; llvm::MCAsmParser::getTargetParser ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a252ed0bb8924351d3e4a6a6cd6dd938f">anonymous{AsmParser.cpp}::AsmParser::checkForValidSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a10d982772a36fe8255164eced5dd71bf">anonymous{MasmParser.cpp}::MasmParser::checkForValidSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#afaaaf7da6379fe3994da86bf71024ddc">anonymous{AsmParser.cpp}::AsmParser::parseAndMatchAndEmitTargetInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#ac7fc5af218d2f17280c5b443dbe20838">anonymous{AsmParser.cpp}::AsmParser::parseExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46e587fd477a44bb0b3c9e3689ff2f92">anonymous{MasmParser.cpp}::MasmParser::parseExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a57a5adf3db1aba1fc30809f73fc05c08">anonymous{AsmParser.cpp}::AsmParser::Warning</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a08f88c883adc92a0b9eacbc5a4064d2b">anonymous{MasmParser.cpp}::MasmParser::Warning</a>.</p>

</div>
</div>

### getTok() {#a607ccd51956df621f1f5ea07c5d3b2c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AsmToken &amp; MCAsmParser::getTok ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the current <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> from the stream.</p>

<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="#aa4e7ba9b1dd10c4262ff498f9a7dd397">getLexer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#aacd3bad41979d112344478f44007a551">llvm::MCAsmLexer::getTok</a>.</p>


<p>Referenced by <a href="#a189e6cc46ddc7ca69bddd7f1a757a736">addErrorSuffix</a>, <a href="#a3030316a1ebebb07ea5bfef630daa790">check</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a252ed0bb8924351d3e4a6a6cd6dd938f">anonymous{AsmParser.cpp}::AsmParser::checkForValidSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a10d982772a36fe8255164eced5dd71bf">anonymous{MasmParser.cpp}::MasmParser::checkForValidSection</a>, <a href="#afe58695435b93e0599ed2f77e877a0aa">Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a4235d087dc899291be41be9db4d811a9">llvm::MCAsmParserExtension::getTok</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#af3d4af20be9f94cbdad904d45cafbefa">anonymous{AsmParser.cpp}::AsmParser::Lex</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#afa801ffa70e7cd238829a01fa92d71c4">anonymous{MasmParser.cpp}::MasmParser::Lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>, <a href="#a7b442abcc8f942ce12304975367e1fa2">parseEOL</a>, <a href="#adbf0064a97b1ecde598fee1ed3d8cf52">parseEOL</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#ac7fc5af218d2f17280c5b443dbe20838">anonymous{AsmParser.cpp}::AsmParser::parseExpression</a>, <a href="#ae70fbaacac6a12bfc3904b3e1af622bb">parseGNUAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#aa91d3c1b093e3561b948794724961f4b">anonymous{AsmParser.cpp}::AsmParser::parseIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#af6dea9845d70ac952115bdbe378dbea1">anonymous{MasmParser.cpp}::MasmParser::parseIdentifier</a>, <a href="#a8d9acbc65c25f0330cd2d8d6baded980">parseIntToken</a>, <a href="#a7fe5bbdb7d87187478d77f3a1d5a2a93">parseOptionalToken</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1c8f1c479ef06f41b1f2010afd80b43a">anonymous{AsmParser.cpp}::AsmParser::parseParenExprOfDepth</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a61115ff1360e15d4f0eb3f12d757d7c1">anonymous{MasmParser.cpp}::MasmParser::parseParenExprOfDepth</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#abdaa8ae9b3e01099946066f89a8e10ad">anonymous{AsmParser.cpp}::AsmParser::parseRealValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a1c3ac00eab4ed0328bc8c8942957c83b">anonymous{MasmParser.cpp}::MasmParser::parseRealValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/hlasmasmparser/#a7ab8a603879e4abd860791912451799c">anonymous{AsmParser.cpp}::HLASMAsmParser::parseStatement</a>, <a href="#a137818cb489ba17770a17ee9eb6f269e">parseToken</a>, <a href="#adfe743277c072b490a3f6bfc7dd593d1">parseTokenLoc</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>.</p>

</div>
</div>

### hasPendingError() {#a4947313871f8935468ae02f6621260c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmParser::hasPendingError ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="#a7cdbb86564e6641120ab773fac6a62d4">PendingErrors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#afaaaf7da6379fe3994da86bf71024ddc">anonymous{AsmParser.cpp}::AsmParser::parseAndMatchAndEmitTargetInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/hlasmasmparser/#a7ab8a603879e4abd860791912451799c">anonymous{AsmParser.cpp}::HLASMAsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>.</p>

</div>
</div>

### isParsingMasm() {#a67ead6c5858726cf466bfa5ded2b5ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::isParsingMasm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### isParsingMSInlineAsm() {#a81bd71316fbce01f2e8055dcc8fdb062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::isParsingMSInlineAsm ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### Lex() {#a922370d34654382dd4ff2b8a1a9c50d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const AsmToken &amp; llvm::MCAsmParser::Lex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the next <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> in the stream, possibly handling file inclusion first.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a189e6cc46ddc7ca69bddd7f1a757a736">addErrorSuffix</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a38ed901577d3ad8c434939bb49fbf342">llvm::MCAsmParserExtension::Lex</a>, <a href="#a7b442abcc8f942ce12304975367e1fa2">parseEOL</a>, <a href="#adbf0064a97b1ecde598fee1ed3d8cf52">parseEOL</a>, <a href="#ae70fbaacac6a12bfc3904b3e1af622bb">parseGNUAttribute</a>, <a href="#a8d9acbc65c25f0330cd2d8d6baded980">parseIntToken</a> and <a href="#a137818cb489ba17770a17ee9eb6f269e">parseToken</a>.</p>

</div>
</div>

### lookUpField() {#add0e53028d15679b96b8f66849b4e971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::lookUpField (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/structs/llvm/asmfieldinfo">AsmFieldInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

### lookUpField() {#ad75338a56ab81e83583aafaf2f2f1246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::lookUpField (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Base, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Member, <a href="/web-llvm/docs/api/structs/llvm/asmfieldinfo">AsmFieldInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

### lookUpType() {#ac9dea6fd0f51f338ae588d9cef3fa6e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::lookUpType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/structs/llvm/asmtypeinfo">AsmTypeInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

### Note() {#a51860cb8160776d84628d48f53e26a62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCAsmParser::Note (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a note at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa825e0d4496e84cdd4b6d8efac571952">llvm::MCAsmParserExtension::Note</a>.</p>

</div>
</div>

### parseAbsoluteExpression() {#ad8413e05e0522dff8eb604bcd891d0aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::parseAbsoluteExpression (int64_t &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse an expression which must evaluate to an absolute value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Res</td>
<td class="doxyParamItemDescription"><p>- The value of the absolute expression. The result is undefined on error.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- False on success.</p></dd>
</dl>


<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#a6c0aead93728457ceebf342312b92807">expectAbsExpression</a>.</p>

</div>
</div>

### parseAngleBracketString() {#abe40caf4aef5f3308433afaa025cfe34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::parseAngleBracketString (std::string &amp; Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse an angle-bracket delimited string at the current position if one is present, returning the string contents.</p>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>

</div>
</div>

### parseComma() {#ad264107ceef36c0f353085894c7c0c76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmParser::parseComma ()</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a> and <a href="#a137818cb489ba17770a17ee9eb6f269e">parseToken</a>.</p>

</div>
</div>

### parseEOL() {#a7b442abcc8f942ce12304975367e1fa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::parseEOL ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#a607ccd51956df621f1f5ea07c5d3b2c6">getTok</a> and <a href="#a922370d34654382dd4ff2b8a1a9c50d6">Lex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a2c0ffc86a3d3e895b526e036cf1aa4d3">llvm::MCAsmParserExtension::parseEOL</a> and <a href="#a137818cb489ba17770a17ee9eb6f269e">parseToken</a>.</p>

</div>
</div>

### parseEOL() {#adbf0064a97b1ecde598fee1ed3d8cf52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::parseEOL (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; ErrMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#a607ccd51956df621f1f5ea07c5d3b2c6">getTok</a> and <a href="#a922370d34654382dd4ff2b8a1a9c50d6">Lex</a>.</p>

</div>
</div>

### parseEscapedString() {#a2d3280ac9b0dc7d25571a60d39a88db4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::parseEscapedString (std::string &amp; Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the current token as a string which may include escaped characters and return the string contents.</p>

<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>

</div>
</div>

### parseExpression() {#a582bb95a08ad05ff3bd5de25a92edd4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::parseExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse an arbitrary expression.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Res</td>
<td class="doxyParamItemDescription"><p>- The value of the expression. The result is undefined on error.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- False on success.</p></dd>
</dl>


<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#a7a374b13bc9d10c9298dd591ee50fc82">parseExpr</a> and <a href="#a83b5779cb89b1af4150d7022b7f751c9">parseExpression</a>.</p>

</div>
</div>

### parseExpression() {#a83b5779cb89b1af4150d7022b7f751c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::parseExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>Reference <a href="#a582bb95a08ad05ff3bd5de25a92edd4a">parseExpression</a>.</p>

</div>
</div>

### parseGNUAttribute() {#ae70fbaacac6a12bfc3904b3e1af622bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::parseGNUAttribute (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, int64_t &amp; Tag, int64_t &amp; IntegerValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a .gnu_attribute.</p>

<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a270e1171db01008f862ffbc34f8476fc">llvm::AsmToken::getIntVal</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a16611db1be4d04f03c570d9302504c04">llvm::AsmToken::getLoc</a>, <a href="#a607ccd51956df621f1f5ea07c5d3b2c6">getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a2f492d3c8c226803c571528284a95d36">llvm::AsmToken::isNot</a>, <a href="#a922370d34654382dd4ff2b8a1a9c50d6">Lex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### parseIdentifier() {#a6a9de5bc4280ee403d0f61304e5fe4fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::parseIdentifier (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse an identifier or string (as a quoted identifier) and set <span class="doxyComputerOutput">Res</span> to the identifier contents.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### parseIntToken() {#a8d9acbc65c25f0330cd2d8d6baded980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::parseIntToken (int64_t &amp; V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; ErrMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a270e1171db01008f862ffbc34f8476fc">llvm::AsmToken::getIntVal</a>, <a href="#a607ccd51956df621f1f5ea07c5d3b2c6">getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a>, <a href="#a922370d34654382dd4ff2b8a1a9c50d6">Lex</a> and <a href="#aca3b32b0f673fcda41b604540f49a4f9">TokError</a>.</p>

</div>
</div>

### parseMany() {#a0796f036e832b4b5e10f6e31e77ca7c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::parseMany (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool()&gt; parseOne, bool hasComma=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="#a7fe5bbdb7d87187478d77f3a1d5a2a93">parseOptionalToken</a> and <a href="#a137818cb489ba17770a17ee9eb6f269e">parseToken</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a5114033053c722506e59e9899a62afe3">llvm::MCAsmParserExtension::parseMany</a>.</p>

</div>
</div>

### parseMSInlineAsm() {#afc2a0f9ef9ceee382a5644dedf7e7d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::parseMSInlineAsm (std::string &amp; AsmString, unsigned &amp; NumOutputs, unsigned &amp; NumInputs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; void *, bool &gt; &gt; &amp; OpDecls, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::string &gt; &amp; Constraints, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::string &gt; &amp; Clobbers, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> * MII, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> * IP, <a href="/web-llvm/docs/api/classes/llvm/mcasmparsersemacallback">MCAsmParserSemaCallback</a> &amp; SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse MS-style inline assembly.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### parseOptionalToken() {#a7fe5bbdb7d87187478d77f3a1d5a2a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::parseOptionalToken (<a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to parse and consume token, returning true on success.</p>

<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a792392c4dfe6e57615554204b0c51a2e">llvm::AsmToken::getKind</a>, <a href="#a607ccd51956df621f1f5ea07c5d3b2c6">getTok</a>, <a href="#a137818cb489ba17770a17ee9eb6f269e">parseToken</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#ac7fc5af218d2f17280c5b443dbe20838">anonymous{AsmParser.cpp}::AsmParser::parseExpression</a>, <a href="#a0796f036e832b4b5e10f6e31e77ca7c8">parseMany</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a0f14a9468b4224a3f7ab96eaef0b99ca">llvm::MCAsmParserExtension::parseOptionalToken</a>.</p>

</div>
</div>

### parseParenExpression() {#a7d85402d1158f9d97c9c35897b90d786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::parseParenExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse an arbitrary expression, assuming that an initial '(' has already been consumed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Res</td>
<td class="doxyParamItemDescription"><p>- The value of the expression. The result is undefined on error.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- False on success.</p></dd>
</dl>


<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### parseParenExprOfDepth() {#a93423cf3a4d1e6c6ab8e473305a44cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::parseParenExprOfDepth (unsigned ParenDepth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse an arbitrary expression of a specified parenthesis depth, assuming that the initial '(' characters have already been consumed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ParenDepth</td>
<td class="doxyParamItemDescription"><p>- Specifies how many trailing expressions outside the current parentheses we have to parse.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Res</td>
<td class="doxyParamItemDescription"><p>- The value of the expression. The result is undefined on error.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- False on success.</p></dd>
</dl>


<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### parsePrimaryExpr() {#a5e3a1b10f62aa9225cec49f8f6195282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::parsePrimaryExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc, <a href="/web-llvm/docs/api/structs/llvm/asmtypeinfo">AsmTypeInfo</a> * TypeInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a primary expression.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Res</td>
<td class="doxyParamItemDescription"><p>- The value of the expression. The result is undefined on error.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- False on success.</p></dd>
</dl>


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a482f6bc5e30d633bc6e911fa006434c1">llvm::MCTargetAsmParser::parsePrimaryExpr</a>.</p>

</div>
</div>

### parseRParen() {#a709fe7ec3803940386b0588e9a1c6f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmParser::parseRParen ()</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>References <a href="#a137818cb489ba17770a17ee9eb6f269e">parseToken</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322">llvm::AsmToken::RParen</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1c8f1c479ef06f41b1f2010afd80b43a">anonymous{AsmParser.cpp}::AsmParser::parseParenExprOfDepth</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a61115ff1360e15d4f0eb3f12d757d7c1">anonymous{MasmParser.cpp}::MasmParser::parseParenExprOfDepth</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>.</p>

</div>
</div>

### parseStringToEndOfStatement() {#a5530d71c3414b44f2205d3a3b3026d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringRef llvm::MCAsmParser::parseStringToEndOfStatement ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse up to the end of statement and return the contents from the current token until the end of the statement; the current token on exit will be either the EndOfStatement or EOF.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>.</p>

</div>
</div>

### parseToken() {#a137818cb489ba17770a17ee9eb6f269e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::parseToken (<a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg="unexpected token")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#a607ccd51956df621f1f5ea07c5d3b2c6">getTok</a>, <a href="#a922370d34654382dd4ff2b8a1a9c50d6">Lex</a>, <a href="#a7b442abcc8f942ce12304975367e1fa2">parseEOL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ad264107ceef36c0f353085894c7c0c76">parseComma</a>, <a href="#a0796f036e832b4b5e10f6e31e77ca7c8">parseMany</a>, <a href="#a7fe5bbdb7d87187478d77f3a1d5a2a93">parseOptionalToken</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="#a709fe7ec3803940386b0588e9a1c6f02">parseRParen</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a554ce8cd5542f0ad063a7b0b1b68a140">llvm::MCAsmParserExtension::parseToken</a>.</p>

</div>
</div>

### parseTokenLoc() {#adfe743277c072b490a3f6bfc7dd593d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::parseTokenLoc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a16611db1be4d04f03c570d9302504c04">llvm::AsmToken::getLoc</a> and <a href="#a607ccd51956df621f1f5ea07c5d3b2c6">getTok</a>.</p>

</div>
</div>

### printError() {#a198ec1b8458ce38de9ad18a6f483c278}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::printError (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an error at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The return value is always true, as an idiomatic convenience to clients.</p></dd>
</dl>


<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="#a25158c234ca9e60f3976a36d7d6ef271">printPendingErrors</a>.</p>

</div>
</div>

### printPendingErrors() {#a25158c234ca9e60f3976a36d7d6ef271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmParser::printPendingErrors ()</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>References <a href="#a7cdbb86564e6641120ab773fac6a62d4">PendingErrors</a> and <a href="#a198ec1b8458ce38de9ad18a6f483c278">printError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#afd8b63a81cb9bf1891795b81d34b6972">anonymous{AsmParser.cpp}::AsmParser::Note</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a9203278cccf22c7dafdfe75efa742ff4">anonymous{MasmParser.cpp}::MasmParser::Note</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>.</p>

</div>
</div>

### Run() {#ab1b2fb0acb2550076d5dcab1039b2bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::Run (bool NoInitialTextSection, bool NoFinalize=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run the parser on the input source buffer.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### setAssemblerDialect() {#af3cf81a517d41f1357dfbdaa6607940a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCAsmParser::setAssemblerDialect (unsigned i)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### setParsingMSInlineAsm() {#af57aeac4a24de62226147e49b62f34b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCAsmParser::setParsingMSInlineAsm (bool V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### setShowParsedOperands() {#aa3cdd92e164e2004543e4a56811cbb2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmParser::setShowParsedOperands (bool Value)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="#a256770fb45edae64541efa7f31ea1d18">ShowParsedOperands</a>.</p>

</div>
</div>

### setTargetParser() {#af473082d59d84b25a63d18be49ecb271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmParser::setTargetParser (<a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a> &amp; P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### TokError() {#aca3b32b0f673fcda41b604540f49a4f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmParser::TokError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Report an error at the current lexer location.</p>

<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#aa4e7ba9b1dd10c4262ff498f9a7dd397">getLexer</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#ac7fc5af218d2f17280c5b443dbe20838">anonymous{AsmParser.cpp}::AsmParser::parseExpression</a>, <a href="#a8d9acbc65c25f0330cd2d8d6baded980">parseIntToken</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#abdaa8ae9b3e01099946066f89a8e10ad">anonymous{AsmParser.cpp}::AsmParser::parseRealValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a1c3ac00eab4ed0328bc8c8942957c83b">anonymous{MasmParser.cpp}::MasmParser::parseRealValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a>.</p>

</div>
</div>

### Warning() {#ab0573f4b31f141fba5ffffe9b0a53688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCAsmParser::Warning (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a warning at the location <span class="doxyComputerOutput">L</span>, with the message <span class="doxyComputerOutput">Msg</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The return value is true, if warnings are fatal.</p></dd>
</dl>


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a693fb5fe74d5bc374102bba3a1dc6431">llvm::MCAsmParserExtension::Warning</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### HadError {#afad5b9aac74030a159903f3cf64c481c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmParser::HadError = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag tracking whether any errors have been encountered.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a66d1a7fb69c6ee8e272ede2e29448a50">anonymous{AsmParser.cpp}::AsmParser::AsmParser</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a314e31f13f6e31ef75cced99a4e946c2">anonymous{MasmParser.cpp}::MasmParser::MasmParser</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a307a44ebfb83c5c16d6a0af1861547c1">anonymous{AsmParser.cpp}::AsmParser::printError</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ac54c7247683fdbcce5c47cf186227d00">anonymous{MasmParser.cpp}::MasmParser::printError</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a47ed0042b8e6c36abcf883ba9efb975d">anonymous{AsmParser.cpp}::AsmParser::~AsmParser</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a3b475bb30badf7d39f82d088bc7e45aa">anonymous{MasmParser.cpp}::MasmParser::~MasmParser</a>.</p>

</div>
</div>

### PendingErrors {#a7cdbb86564e6641120ab773fac6a62d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MCPendingError, 0&gt; llvm::MCAsmParser::PendingErrors</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="#a189e6cc46ddc7ca69bddd7f1a757a736">addErrorSuffix</a>, <a href="#a47420f87b1401934de51a165550a7481">clearPendingErrors</a>, <a href="#afe58695435b93e0599ed2f77e877a0aa">Error</a>, <a href="#a4947313871f8935468ae02f6621260c8">hasPendingError</a> and <a href="#a25158c234ca9e60f3976a36d7d6ef271">printPendingErrors</a>.</p>

</div>
</div>

### ShowParsedOperands {#a256770fb45edae64541efa7f31ea1d18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmParser::ShowParsedOperands = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="#a6e4af5e4d650f5bec85b99dfe0fc4d04">getShowParsedOperands</a> and <a href="#aa3cdd92e164e2004543e4a56811cbb2b">setShowParsedOperands</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TargetParser {#ae53fc77de81f2e5b009b61c2b625f82d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCTargetAsmParser* llvm::MCAsmParser::TargetParser = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmparser-cpp">MCAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
