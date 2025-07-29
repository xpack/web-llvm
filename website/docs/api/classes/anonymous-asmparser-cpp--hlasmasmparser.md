---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-asmparser-cpp-/hlasmasmparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `HLASMAsmParser` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AsmParser.cpp}::HLASMAsmParser { ... }
</div>

## Base class

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a123082543e8e0043abcbb49a723e78fa">HLASMAsmParser</a> (SourceMgr &amp;SM, MCContext &amp;Ctx, MCStreamer &amp;Out, const MCAsmInfo &amp;MAI, unsigned CB=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6e296ce63d2e5eb60d747f8f5c93d98">~HLASMAsmParser</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ab8a603879e4abd860791912451799c">parseStatement</a> (ParseStatementInfo &amp;Info, MCAsmParserSemaCallback *SI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseStatement: ::= EndOfStatement ::= Label* <a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> ...Operands... EndOfStatement ::= Label* Identifier OperandList* EndOfStatement. <a href="#a7ab8a603879e4abd860791912451799c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e1e4115586842b5ee0f4f74728a83d2">lexLeadingSpaces</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e847270de7fea4b348a8a958f60547e">parseAsHLASMLabel</a> (ParseStatementInfo &amp;Info, MCAsmParserSemaCallback *SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a366bd3643c18eeef40ba87d368ee8e68">parseAsMachineInstruction</a> (ParseStatementInfo &amp;Info, MCAsmParserSemaCallback *SI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmlexer">MCAsmLexer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7be2837fb399e7dd5e704386b19e9ac1">Lexer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c1fb8f07339ce76d5b055702e3756b">Out</a></td>
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


<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HLASMAsmParser() {#a123082543e8e0043abcbb49a723e78fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AsmParser.cpp}::HLASMAsmParser::HLASMAsmParser (<a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI, unsigned CB=0)</td>
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



<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a66d1a7fb69c6ee8e272ede2e29448a50">anonymous{AsmParser.cpp}::AsmParser::AsmParser</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a33ddf50b4cf84a930050c2e3affa6190">anonymous{AsmParser.cpp}::AsmParser::getLexer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~HLASMAsmParser() {#ae6e296ce63d2e5eb60d747f8f5c93d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AsmParser.cpp}::HLASMAsmParser::~HLASMAsmParser ()</td>
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



<p>Definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parseStatement() {#a7ab8a603879e4abd860791912451799c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HLASMAsmParser::parseStatement (<a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/parsestatementinfo">ParseStatementInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/mcasmparsersemacallback">MCAsmParserSemaCallback</a> * SI)</td>
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

<p>ParseStatement: ::= EndOfStatement ::= Label* <a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> ...Operands... EndOfStatement ::= Label* Identifier OperandList* EndOfStatement.</p>

<p>Definition at line 756 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1a464d658f065637fc039e0645a94d87">anonymous{AsmParser.cpp}::AsmParser::eatToEndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a4947313871f8935468ae02f6621260c8">llvm::MCAsmParser::hasPendingError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#af3d4af20be9f94cbdad904d45cafbefa">anonymous{AsmParser.cpp}::AsmParser::Lex</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1ff20331fe667c9bf3a49cc28516155e">llvm::AsmToken::Space</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### lexLeadingSpaces() {#a4e1e4115586842b5ee0f4f74728a83d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AsmParser.cpp}::HLASMAsmParser::lexLeadingSpaces ()</td>
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



<p>Definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseAsHLASMLabel() {#a2e847270de7fea4b348a8a958f60547e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HLASMAsmParser::parseAsHLASMLabel (<a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/parsestatementinfo">ParseStatementInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/mcasmparsersemacallback">MCAsmParserSemaCallback</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### parseAsMachineInstruction() {#a366bd3643c18eeef40ba87d368ee8e68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HLASMAsmParser::parseAsMachineInstruction (<a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/parsestatementinfo">ParseStatementInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/mcasmparsersemacallback">MCAsmParserSemaCallback</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Lexer {#a7be2837fb399e7dd5e704386b19e9ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmLexer&amp; anonymous{AsmParser.cpp}::HLASMAsmParser::Lexer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### Out {#a40c1fb8f07339ce76d5b055702e3756b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer&amp; anonymous{AsmParser.cpp}::HLASMAsmParser::Out</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
