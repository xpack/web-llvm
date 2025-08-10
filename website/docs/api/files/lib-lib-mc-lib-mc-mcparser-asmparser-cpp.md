---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AsmParser.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">llvm/DebugInfo/CodeView/SymbolRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">llvm/MC/MCCodeView.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdirectives-h">llvm/MC/MCDirectives.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">llvm/MC/MCInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmcond-h">llvm/MC/MCParser/AsmCond.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">llvm/MC/MCParser/AsmLexer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">llvm/MC/MCParser/MCAsmLexer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">llvm/MC/MCParser/MCAsmParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparserextension-h">llvm/MC/MCParser/MCAsmParserExtension.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparserutils-h">llvm/MC/MCParser/MCAsmParserUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcparsedasmoperand-h">llvm/MC/MCParser/MCParsedAsmOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">llvm/MC/MCParser/MCTargetAsmParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">llvm/MC/MCSection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolmacho-h">llvm/MC/MCSymbolMachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">llvm/Support/MD5.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smloc-h">llvm/Support/SMLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">llvm/Support/SourceMgr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cctype&gt;
#include &lt;climits&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;deque&gt;
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;sstream&gt;
#include &lt;string&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-asmparser-cpp-">anonymous{AsmParser.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils">MCParserUtils</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/macroinstantiation">MacroInstantiation</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class for storing information about an active macro instantiation. <a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/macroinstantiation/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/parsestatementinfo">ParseStatementInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/asmparser/cpphashinfoty">CppHashInfoTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The values from the last parsed cpp hash file line comment if any. <a href="/web-llvm/docs/api/structs/anonymous-asmparser-cpp-/asmparser/cpphashinfoty/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/hlasmasmparser">HLASMAsmParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmlexerskipspaceraii">AsmLexerSkipSpaceRAII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a4d1a9851bc429eda0f1707097e39543d">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596b6449296931e40cbfb38f8cb238c1">isAngleBracketString</a> (SMLoc &amp;StrLoc, SMLoc &amp;EndLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function checks if the next token is &lt;string&gt; type or arithmetic. <a href="#a596b6449296931e40cbfb38f8cb238c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97f8c0863c59c4c7900ce9aadf6dff9a">angleBracketString</a> (StringRef AltMacroStr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>creating a string without the escape characters '!'. <a href="#a97f8c0863c59c4c7900ce9aadf6dff9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b1cbdf398cb86b32099da9eba210688">getDarwinBinOpPrecedence</a> (AsmToken::TokenKind K, MCBinaryExpr::Opcode &amp;Kind, bool ShouldUseLogicalShr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90edcafb8111f5004103d92e066b1a7e">getGNUBinOpPrecedence</a> (const MCAsmInfo &amp;MAI, AsmToken::TokenKind K, MCBinaryExpr::Opcode &amp;Kind, bool ShouldUseLogicalShr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c23fe1fabd28591c06e690c2ef01f4e">isIdentifierChar</a> (char c)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee0234125842a6e0f171adb6941b7621">isOperator</a> (AsmToken::TokenKind kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8fb018deb0883d60ae768058d3e871">parseHexOcta</a> (AsmParser &amp;Asm, uint64_t &amp;hi, uint64_t &amp;lo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bac8de926a7ec7b9877746d5d3d3334">isValidEncoding</a> (int64_t Encoding)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac27a97bbb42a7f0481f803251c65c237">rewritesSort</a> (const AsmRewrite *AsmRewriteA, const AsmRewrite *AsmRewriteB)</td>
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

### anonymous enum  {#a4d1a9851bc429eda0f1707097e39543d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">DEFAULT_ADDRSPACE<a id="a4d1a9851bc429eda0f1707097e39543da4fb9b7e46bf210aa9b5b59ac1c5fe8ff"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### angleBracketString() {#a97f8c0863c59c4c7900ce9aadf6dff9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string angleBracketString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> AltMacroStr)</td>
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

<p>creating a string without the escape characters '!'.</p>

<p>Definition at line 1480 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### getDarwinBinOpPrecedence() {#a6b1cbdf398cb86b32099da9eba210688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getDarwinBinOpPrecedence (<a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629">MCBinaryExpr::Opcode</a> &amp; Kind, bool ShouldUseLogicalShr)</td>
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



<p>Definition at line 1576 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ae3bbdb1bec11d89ba5478648dcd3ec3c">llvm::MCBinaryExpr::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a829ba931cbc81b6741c399abca551130">llvm::AsmToken::Amp</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a4f6152e3e4d07396f01fcee52f9e6a8d">llvm::AsmToken::AmpAmp</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a4f10c2fcbde759540aed2b1bf0751481">llvm::MCBinaryExpr::And</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0cd156d89940c517bc5add15227a62a0">llvm::MCBinaryExpr::AShr</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a37166ce08fbc1f81e0b1637575f3f116">llvm::AsmToken::Caret</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0b0dd01b0b404f79f6c77d09b4291f99">llvm::MCBinaryExpr::Div</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a1cf6761d7f868d227481827f80c74e45">llvm::MCBinaryExpr::EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8d7d001fb130f9f7daa5b8f1b3ca3044">llvm::AsmToken::EqualEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad8f908421e23922e29e64df58fb3f61f">llvm::AsmToken::ExclaimEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0bf4b7df9c117d60974b94c95d778fc3">llvm::AsmToken::Greater</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a59fc39402b39f6d595004effefd091c3">llvm::AsmToken::GreaterEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aa196e2a16fa7cc608b18b2bb7c0db3c3">llvm::AsmToken::GreaterGreater</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a3cda1ebe5c1234eea7d27d545aba1738">llvm::MCBinaryExpr::GT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a13268dae72eac8a642225c0ff45dfcd0">llvm::MCBinaryExpr::GTE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a9af6b1faad71fbdd9d2a7a8958ed4ea9">llvm::MCBinaryExpr::LAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8ed7ac51e3a2326ae92b40e8154d0e6b">llvm::AsmToken::Less</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a42a1d2e47b0e72229b4527397e7bd3f6">llvm::AsmToken::LessEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a75b12bfe9ad391209f61bd77d198ac3d">llvm::AsmToken::LessGreater</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2cd2ef0141924332a5db5c4d67a58d76">llvm::AsmToken::LessLess</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629aaffa02e8782d8f2e11b90fb97b4d53cb">llvm::MCBinaryExpr::LOr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a11c8e78341eb2a99a09a496a5511b068">llvm::MCBinaryExpr::LShr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ab9bf167f2d33f25da27ec2cc9ab65648">llvm::MCBinaryExpr::LT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629af7fe864573da32fa4c66bef734c85456">llvm::MCBinaryExpr::LTE</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a40ec3d6af8d23efa53e527ae4e1525f2">llvm::MCBinaryExpr::Mod</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2cb7977b1f22c763fe362191442ec8b2">llvm::MCBinaryExpr::Mul</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629afa5c823b0ff7699d14051a05162d8288">llvm::MCBinaryExpr::NE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a7cc60301ef15f92ae57708ed4fe403f7">llvm::MCBinaryExpr::Or</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a3307eed2aff3782f3d420aebbe433486">llvm::AsmToken::Percent</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a7da9940ae6624563c0ff853d5fa7abc5">llvm::AsmToken::Pipe</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aa74a0718c3470a543bb0b0a865d3fc68">llvm::AsmToken::PipePipe</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac97d79769cee46bf3915460c278d5de6">llvm::AsmToken::Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0bb5874c2ea71cc7d1f2e1304b1a4d3a">llvm::MCBinaryExpr::Shl</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a9416ef6f33208f9c76db8f44ca45e61a">llvm::AsmToken::Slash</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a871b85a46f471e616995b722df807211">llvm::AsmToken::Star</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2042f1a9af632c3d4d83f157201623d2">llvm::MCBinaryExpr::Sub</a> and <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a9039641f4bc6800217773d9688b7f7e5">llvm::MCBinaryExpr::Xor</a>.</p>

</div>
</div>

### getGNUBinOpPrecedence() {#a90edcafb8111f5004103d92e066b1a7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getGNUBinOpPrecedence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629">MCBinaryExpr::Opcode</a> &amp; Kind, bool ShouldUseLogicalShr)</td>
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



<p>Definition at line 1652 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ae3bbdb1bec11d89ba5478648dcd3ec3c">llvm::MCBinaryExpr::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a829ba931cbc81b6741c399abca551130">llvm::AsmToken::Amp</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a4f6152e3e4d07396f01fcee52f9e6a8d">llvm::AsmToken::AmpAmp</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a4f10c2fcbde759540aed2b1bf0751481">llvm::MCBinaryExpr::And</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0cd156d89940c517bc5add15227a62a0">llvm::MCBinaryExpr::AShr</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a37166ce08fbc1f81e0b1637575f3f116">llvm::AsmToken::Caret</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0b0dd01b0b404f79f6c77d09b4291f99">llvm::MCBinaryExpr::Div</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a1cf6761d7f868d227481827f80c74e45">llvm::MCBinaryExpr::EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8d7d001fb130f9f7daa5b8f1b3ca3044">llvm::AsmToken::EqualEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039af475f82c0aa5e42ef5751dcdc3bee49f">llvm::AsmToken::Exclaim</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad8f908421e23922e29e64df58fb3f61f">llvm::AsmToken::ExclaimEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a83dadee742338c79e561e3efff6ee00a">llvm::MCAsmInfo::getCommentString</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0bf4b7df9c117d60974b94c95d778fc3">llvm::AsmToken::Greater</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a59fc39402b39f6d595004effefd091c3">llvm::AsmToken::GreaterEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aa196e2a16fa7cc608b18b2bb7c0db3c3">llvm::AsmToken::GreaterGreater</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a3cda1ebe5c1234eea7d27d545aba1738">llvm::MCBinaryExpr::GT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a13268dae72eac8a642225c0ff45dfcd0">llvm::MCBinaryExpr::GTE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a9af6b1faad71fbdd9d2a7a8958ed4ea9">llvm::MCBinaryExpr::LAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8ed7ac51e3a2326ae92b40e8154d0e6b">llvm::AsmToken::Less</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a42a1d2e47b0e72229b4527397e7bd3f6">llvm::AsmToken::LessEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a75b12bfe9ad391209f61bd77d198ac3d">llvm::AsmToken::LessGreater</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2cd2ef0141924332a5db5c4d67a58d76">llvm::AsmToken::LessLess</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629aaffa02e8782d8f2e11b90fb97b4d53cb">llvm::MCBinaryExpr::LOr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a11c8e78341eb2a99a09a496a5511b068">llvm::MCBinaryExpr::LShr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ab9bf167f2d33f25da27ec2cc9ab65648">llvm::MCBinaryExpr::LT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629af7fe864573da32fa4c66bef734c85456">llvm::MCBinaryExpr::LTE</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a40ec3d6af8d23efa53e527ae4e1525f2">llvm::MCBinaryExpr::Mod</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2cb7977b1f22c763fe362191442ec8b2">llvm::MCBinaryExpr::Mul</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629afa5c823b0ff7699d14051a05162d8288">llvm::MCBinaryExpr::NE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a7cc60301ef15f92ae57708ed4fe403f7">llvm::MCBinaryExpr::Or</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a952b1824a84c532fdcfa4e55e5548b5b">llvm::MCBinaryExpr::OrNot</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a3307eed2aff3782f3d420aebbe433486">llvm::AsmToken::Percent</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a7da9940ae6624563c0ff853d5fa7abc5">llvm::AsmToken::Pipe</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aa74a0718c3470a543bb0b0a865d3fc68">llvm::AsmToken::PipePipe</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac97d79769cee46bf3915460c278d5de6">llvm::AsmToken::Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0bb5874c2ea71cc7d1f2e1304b1a4d3a">llvm::MCBinaryExpr::Shl</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a9416ef6f33208f9c76db8f44ca45e61a">llvm::AsmToken::Slash</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a871b85a46f471e616995b722df807211">llvm::AsmToken::Star</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2042f1a9af632c3d4d83f157201623d2">llvm::MCBinaryExpr::Sub</a> and <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a9039641f4bc6800217773d9688b7f7e5">llvm::MCBinaryExpr::Xor</a>.</p>

</div>
</div>

### isAngleBracketString() {#a596b6449296931e40cbfb38f8cb238c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAngleBracketString (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StrLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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

<p>This function checks if the next token is &lt;string&gt; type or arithmetic.</p>


<p>string that begin with character '&lt;' must end with character '&gt;'. otherwise it is arithmetics. If the function returns a 'true' value, the End argument will be filled with the last location pointed to the '&gt;' character. There is a gap between the AltMacro's documentation and the single quote implementation. GCC does not fully support this feature and so we will not support it. TODO: Adding single quote as a string.</p>


<p>Definition at line 1462 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a> and <a href="/web-llvm/docs/api/classes/llvm/smloc/#a7428ebe08f75a705043e1bd005d0542d">llvm::SMLoc::getPointer</a>.</p>

</div>
</div>

### isIdentifierChar() {#a6c23fe1fabd28591c06e690c2ef01f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isIdentifierChar (char c)</td>
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



<p>Definition at line 2511 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>

</div>
</div>

### isOperator() {#aee0234125842a6e0f171adb6941b7621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isOperator (<a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> kind)</td>
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



<p>Definition at line 2647 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a829ba931cbc81b6741c399abca551130">llvm::AsmToken::Amp</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a4f6152e3e4d07396f01fcee52f9e6a8d">llvm::AsmToken::AmpAmp</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a37166ce08fbc1f81e0b1637575f3f116">llvm::AsmToken::Caret</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae95926c6ea560f4332395213cc7519e9">llvm::AsmToken::Dot</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aaf27951b9eea060afd2ae6a01e8a8e0e">llvm::AsmToken::Equal</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8d7d001fb130f9f7daa5b8f1b3ca3044">llvm::AsmToken::EqualEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039af475f82c0aa5e42ef5751dcdc3bee49f">llvm::AsmToken::Exclaim</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad8f908421e23922e29e64df58fb3f61f">llvm::AsmToken::ExclaimEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0bf4b7df9c117d60974b94c95d778fc3">llvm::AsmToken::Greater</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a59fc39402b39f6d595004effefd091c3">llvm::AsmToken::GreaterEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aa196e2a16fa7cc608b18b2bb7c0db3c3">llvm::AsmToken::GreaterGreater</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8ed7ac51e3a2326ae92b40e8154d0e6b">llvm::AsmToken::Less</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a42a1d2e47b0e72229b4527397e7bd3f6">llvm::AsmToken::LessEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a75b12bfe9ad391209f61bd77d198ac3d">llvm::AsmToken::LessGreater</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2cd2ef0141924332a5db5c4d67a58d76">llvm::AsmToken::LessLess</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a7da9940ae6624563c0ff853d5fa7abc5">llvm::AsmToken::Pipe</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aa74a0718c3470a543bb0b0a865d3fc68">llvm::AsmToken::PipePipe</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac97d79769cee46bf3915460c278d5de6">llvm::AsmToken::Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a9416ef6f33208f9c76db8f44ca45e61a">llvm::AsmToken::Slash</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a871b85a46f471e616995b722df807211">llvm::AsmToken::Star</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a151c8770a1290c7713e3a8490ee09471">llvm::AsmToken::Tilde</a>.</p>

</div>
</div>

### isValidEncoding() {#a3bac8de926a7ec7b9877746d5d3d3334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isValidEncoding (int64_t Encoding)</td>
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



<p>Definition at line 4386 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab8bb265a153372d87860f6a33d858f3e">llvm::dwarf::DW_EH_PE_absptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255af88641d07cb5fdb688ad0d4e78314222">llvm::dwarf::DW_EH_PE_omit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a18cb02c6dc96569494f65b82ab70487b">llvm::dwarf::DW_EH_PE_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255abf732c58551b977c2f830e8ddd06e64f">llvm::dwarf::DW_EH_PE_sdata2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a68bcc7d64ea60cf76503e913360e0b01">llvm::dwarf::DW_EH_PE_sdata4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab4f228eae8e91cb5eb218c4372d2cd75">llvm::dwarf::DW_EH_PE_sdata8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a43244ccf6c5f085a9fdf303d86761a27">llvm::dwarf::DW_EH_PE_signed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab06941f802d97190e82e32018265b5f1">llvm::dwarf::DW_EH_PE_udata2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255abfafdba601fd5cab55113f2cdb96c033">llvm::dwarf::DW_EH_PE_udata4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ac75ce7ce2df1136a194d4cd1d889c06a">llvm::dwarf::DW_EH_PE_udata8</a>.</p>

</div>
</div>

### parseHexOcta() {#acd8fb018deb0883d60ae768058d3e871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool parseHexOcta (AsmParser &amp; Asm, uint64_t &amp; hi, uint64_t &amp; lo)</td>
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



<p>Definition at line 3229 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8792e8ff663b631c3d0069d1655c7b45">llvm::AsmToken::BigNum</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a2d5c4385716b3fa4a96e879987cccedc">llvm::APInt::getHiBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a0fa9845f80fa0642b31c238f4ab0d5ef">llvm::APInt::getLoBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#ae00c35cb040107c05f3fe00c15bb3da0">llvm::APInt::isIntN</a>.</p>

</div>
</div>

### rewritesSort() {#ac27a97bbb42a7f0481f803251c65c237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int rewritesSort (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/asmrewrite">AsmRewrite</a> * AsmRewriteA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/asmrewrite">AsmRewrite</a> * AsmRewriteB)</td>
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



<p>Definition at line 6008 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a79d60bf85f65fc322339ebf2dc6c09eb">llvm::AsmRewritePrecedence</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a7428ebe08f75a705043e1bd005d0542d">llvm::SMLoc::getPointer</a>, <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#a49376fe6e2f150528a01d6e04c6bbbf9">llvm::AsmRewrite::Kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/structs/llvm/asmrewrite/#a801ff63a978f05ed7a17965654f4db42">llvm::AsmRewrite::Loc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
