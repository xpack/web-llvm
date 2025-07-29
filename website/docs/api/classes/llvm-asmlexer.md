---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/asmlexer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AsmLexer` Class

<p><a href="/web-llvm/docs/api/classes/llvm/asmlexer">AsmLexer</a> - Lexer class for assembly files. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AsmLexer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">llvm/MC/MCParser/AsmLexer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmlexer">MCAsmLexer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic assembler lexer interface, for use by target specific assembly lexers. <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf3180e209a3079c3c08ab8c818a9ae">AsmLexer</a> (const MCAsmInfo &amp;MAI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980e64ca41f4ad2eb723c80e7ed76008">AsmLexer</a> (const AsmLexer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a117cd3b718b7f46f06224917038073f8">~AsmLexer</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmlexer">AsmLexer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb37df9067c0dcbc885e1e6dca1e00cf">operator=</a> (const AsmLexer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf479f9ea9b5902aea9e0ab3fd50ad94">setBuffer</a> (StringRef Buf, const char *ptr=nullptr, bool EndStatementAtEOF=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a564882070bf87421f0775ebd6cf64014">LexUntilEndOfStatement</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e95622dd1cef434cddeae8612854d8">peekTokens</a> (MutableArrayRef&lt; AsmToken &gt; Buf, bool ShouldSkipSpace=true) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look ahead an arbitrary number of tokens. <a href="#a18e95622dd1cef434cddeae8612854d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bad0df670282ea62b092aa9b3907ee0">getMAI</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8">LexToken</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexToken - Read the next token and return its code. <a href="#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17dec07b2899ccf622a571b224635625">isAtStartOfComment</a> (const char *Ptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91dd47ae840c35211cc784acc2b6fbca">isAtStatementSeparator</a> (const char *Ptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ea7b7a473abb1e3dd84c82760142c2">getNextChar</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8f17e531fbf60b307dc0ee2a6f14c5">peekNextChar</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9cc0a833b1230fc974d77fd506abeaf">ReturnError</a> (const char *Loc, const std::string &amp;Msg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReturnError - Set the error to the specified string at the specified location. <a href="#ab9cc0a833b1230fc974d77fd506abeaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a530d1c83b94094de89a20d1bf956b74f">LexIdentifier</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fce297825f118eb0a8758a95d6e273f">LexSlash</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexSlash: Slash: / C-Style Comment: /* ... *‍/ C-style Comment: // ... <a href="#a6fce297825f118eb0a8758a95d6e273f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf469cf5c1ac6bbfe536600a9a84309f">LexLineComment</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexLineComment: Comment: #[^
<br/>
]* : //[^
<br/>
]*. <a href="#adf469cf5c1ac6bbfe536600a9a84309f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1df22768e543cc8adc0e8ab6fecdc96">LexDigit</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexDigit: First character is [0-9]. <a href="#ae1df22768e543cc8adc0e8ab6fecdc96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06dcd3c7a299c8348e80364d0a23e2f7">LexSingleQuote</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexSingleQuote: Integer: 'b'. <a href="#a06dcd3c7a299c8348e80364d0a23e2f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198ab63b4d62151d62bee9294f3d0a74">LexQuote</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexQuote: String: "...". <a href="#a198ab63b4d62151d62bee9294f3d0a74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a257c524b69fc9619596157eecfe0de6d">LexFloatLiteral</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The leading integral digit sequence and dot should have already been consumed, some or all of the fractional digit sequence <em>can</em> have been consumed. <a href="#a257c524b69fc9619596157eecfe0de6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce0f2ccd4d0b41ff3c17986640bef07">LexHexFloatLiteral</a> (bool NoIntDigits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexHexFloatLiteral matches essentially (. <a href="#a1ce0f2ccd4d0b41ff3c17986640bef07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a691964f50fbc398ffd0932b1fad63ba8">LexUntilEndOfLine</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02b32526387a336235d8b2dc6b9f4fe">MAI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3f2f47b9767ccfcf66ac446c6b32185">CurPtr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0eaed4579b1202f172e3f3b4e2df6ff">CurBuf</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab86bd74328f94fa40e9111cf4be2c02c">IsAtStartOfLine</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706902cb773df7f7dbe3f7382b8823fd">IsAtStartOfStatement</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac66424f3c36d601ca62ed80c8d04dcb3">IsPeeking</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab88cc2a1ec3417333fa33cd7bc2b71a">EndStatementAtEOF</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/asmlexer">AsmLexer</a> - Lexer class for assembly files.</p>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AsmLexer() {#a2cf3180e209a3079c3c08ab8c818a9ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmLexer::AsmLexer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#ab3c87fe4f2d3830147b43040ddc35034">llvm::MCAsmLexer::AllowAtInIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#a95131b9168fb87f1b59758f10e6b0fa9">llvm::MCAsmLexer::LexMotorolaIntegers</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="#a980e64ca41f4ad2eb723c80e7ed76008">AsmLexer</a> and <a href="#abb37df9067c0dcbc885e1e6dca1e00cf">operator=</a>.</p>

</div>
</div>

### AsmLexer() {#a980e64ca41f4ad2eb723c80e7ed76008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AsmLexer::AsmLexer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmlexer">AsmLexer</a> &amp;)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>.</p>


<p>Reference <a href="#a2cf3180e209a3079c3c08ab8c818a9ae">AsmLexer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AsmLexer() {#a117cd3b718b7f46f06224917038073f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmLexer::~AsmLexer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#abb37df9067c0dcbc885e1e6dca1e00cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmLexer &amp; llvm::AsmLexer::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmlexer">AsmLexer</a> &amp;)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>.</p>


<p>Reference <a href="#a2cf3180e209a3079c3c08ab8c818a9ae">AsmLexer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMAI() {#a6bad0df670282ea62b092aa9b3907ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmInfo &amp; llvm::AsmLexer::getMAI ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>.</p>

</div>
</div>

### LexUntilEndOfStatement() {#a564882070bf87421f0775ebd6cf64014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AsmLexer::LexUntilEndOfStatement ()</td>
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



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#aac2076dcf6a840f61d7fe9a8c4700f19">llvm::MCAsmLexer::TokStart</a>.</p>

</div>
</div>

### peekTokens() {#a18e95622dd1cef434cddeae8612854d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t AsmLexer::peekTokens (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &gt; Buf, bool ShouldSkipSpace=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Look ahead an arbitrary number of tokens.</p>

<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">llvm::AsmToken::Eof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#af9ab8c42fdd5aace6049066a5c3478ac">llvm::MCAsmLexer::getErr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#aa59a6bb403f7b5d494829196e988c848">llvm::MCAsmLexer::getErrLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a710e72de4b87af42e7605679d1fb2c24">llvm::AsmToken::is</a>, <a href="#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8">LexToken</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#af190e00774c0c3297efbc82fb505e30a">llvm::MCAsmLexer::SetError</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#a23b5bae0c60695a979d7864a11661345">llvm::MCAsmLexer::SkipSpace</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#aac2076dcf6a840f61d7fe9a8c4700f19">llvm::MCAsmLexer::TokStart</a>.</p>


<p>Referenced by <a href="#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8">LexToken</a>.</p>

</div>
</div>

### setBuffer() {#abf479f9ea9b5902aea9e0ab3fd50ad94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AsmLexer::setBuffer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ptr=nullptr, bool EndStatementAtEOF=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#aac2076dcf6a840f61d7fe9a8c4700f19">llvm::MCAsmLexer::TokStart</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### LexToken() {#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken AsmLexer::LexToken ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexToken - Read the next token and return its code.</p>

<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a829ba931cbc81b6741c399abca551130">llvm::AsmToken::Amp</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a4f6152e3e4d07396f01fcee52f9e6a8d">llvm::AsmToken::AmpAmp</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a4aeb4b633eccde6dcae9b02af09c8302">llvm::AsmToken::At</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a3690783ddbc5a9d0f0f3c94f48dcf052">llvm::AsmToken::BackSlash</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a37166ce08fbc1f81e0b1637575f3f116">llvm::AsmToken::Caret</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aaf57ac1b90bbb375414e2fd3fc15bf4c">llvm::AsmToken::Dollar</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">llvm::AsmToken::Eof</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aaf27951b9eea060afd2ae6a01e8a8e0e">llvm::AsmToken::Equal</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8d7d001fb130f9f7daa5b8f1b3ca3044">llvm::AsmToken::EqualEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039af475f82c0aa5e42ef5751dcdc3bee49f">llvm::AsmToken::Exclaim</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad8f908421e23922e29e64df58fb3f61f">llvm::AsmToken::ExclaimEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0bf4b7df9c117d60974b94c95d778fc3">llvm::AsmToken::Greater</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a59fc39402b39f6d595004effefd091c3">llvm::AsmToken::GreaterEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aa196e2a16fa7cc608b18b2bb7c0db3c3">llvm::AsmToken::GreaterGreater</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8008076fe2821cf033daf56965fd748b">llvm::AsmToken::Hash</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a5ed906a629ca3518e4b230146dff4c7a">llvm::AsmToken::HashDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#ad9a2ad2c78d9254fe58140aef128b6ab">llvm::MCAsmLexer::is</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#aa05944bb87057627a566963c526f1ca5">isHexDigit</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a33f6b27b4c0cd2e6d1e970ea90de765d">llvm::AsmToken::LBrac</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a940bbb142e7bb0990d40889426def99c">llvm::AsmToken::LCurly</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8ed7ac51e3a2326ae92b40e8154d0e6b">llvm::AsmToken::Less</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a42a1d2e47b0e72229b4527397e7bd3f6">llvm::AsmToken::LessEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a75b12bfe9ad391209f61bd77d198ac3d">llvm::AsmToken::LessGreater</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2cd2ef0141924332a5db5c4d67a58d76">llvm::AsmToken::LessLess</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#a95131b9168fb87f1b59758f10e6b0fa9">llvm::MCAsmLexer::LexMotorolaIntegers</a>, <a href="#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8">LexToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ab7565cea737f907e6d9d8a66b2f20a19">llvm::AsmToken::MinusGreater</a>, <a href="#a18e95622dd1cef434cddeae8612854d8">peekTokens</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a3307eed2aff3782f3d420aebbe433486">llvm::AsmToken::Percent</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a00c4e8d8fb246b6b7aeed5c7b53ee299">llvm::AsmToken::PercentCall16</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a707c1a6ff33be3833fa784e55c72d356">llvm::AsmToken::PercentCall_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a074f871580c44c082aa24aaafd8a238a">llvm::AsmToken::PercentCall_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a267b3c56c189ca7b2c22f3f5a29647fe">llvm::AsmToken::PercentDtprel_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aa8b764c71f0045677baab76623a52bcd">llvm::AsmToken::PercentDtprel_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a00774b22629d30aaa48e1c2bd537028b">llvm::AsmToken::PercentGot</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039af1f8ea5e121b4bc15a5df42c055bd6d7">llvm::AsmToken::PercentGot_Disp</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ab0762694eece06d0f7a3a2079a4a4fc8">llvm::AsmToken::PercentGot_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0c1d09e9bf3105cc4a9f0fdbd353573e">llvm::AsmToken::PercentGot_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad1e2f5b48c997464f7959fc57dffc5f8">llvm::AsmToken::PercentGot_Ofst</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a92f6b21bb33e8fed87795f60509087b9">llvm::AsmToken::PercentGot_Page</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0605e7b15189ad4dbaf2de310d8d71d6">llvm::AsmToken::PercentGottprel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aceac274aaa62864ab0b60654281e237a">llvm::AsmToken::PercentGp_Rel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a07aadc6194c34b01c1dbc32579382c1e">llvm::AsmToken::PercentHi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1889a8a107d7a02053f669a752290d2d">llvm::AsmToken::PercentHigher</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ab00380bcbfc11a24a06d6ff70619f9fa">llvm::AsmToken::PercentHighest</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad3c8fae162d44bb21f7f39c853e85eca">llvm::AsmToken::PercentLo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039afe3b827d1ceee6cf5aaf0bb61cc1e77f">llvm::AsmToken::PercentNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a28be2810a4857bb3b0aad6844d80176e">llvm::AsmToken::PercentPcrel_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a7aa2c1d1de0fe4ef4d1d2275632aa6a1">llvm::AsmToken::PercentPcrel_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8f666b660d975090f718938ee00fe9fc">llvm::AsmToken::PercentTlsgd</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a91a7f91ec2b3a0618572a821556591cf">llvm::AsmToken::PercentTlsldm</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8df6f192abb2cb6a173a7a2aa91bd8a2">llvm::AsmToken::PercentTprel_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a63518ba1849d2eb240372e55b9a04436">llvm::AsmToken::PercentTprel_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a7da9940ae6624563c0ff853d5fa7abc5">llvm::AsmToken::Pipe</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aa74a0718c3470a543bb0b0a865d3fc68">llvm::AsmToken::PipePipe</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac97d79769cee46bf3915460c278d5de6">llvm::AsmToken::Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a5ee2ae41fbe7fbaa6e0d98b06e85ca4e">llvm::AsmToken::Question</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a23ee1110c9b68d6faa5a6823d1a90740">llvm::AsmToken::RBrac</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a3847b0adce89a393ecf0b359d8ff8646">llvm::AsmToken::RCurly</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322">llvm::AsmToken::RParen</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#a23b5bae0c60695a979d7864a11661345">llvm::MCAsmLexer::SkipSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1ff20331fe667c9bf3a49cc28516155e">llvm::AsmToken::Space</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a871b85a46f471e616995b722df807211">llvm::AsmToken::Star</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a18d693ac4253b089ce44aa602246fe58">llvm::AsmToken::String</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a151c8770a1290c7713e3a8490ee09471">llvm::AsmToken::Tilde</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#aac2076dcf6a840f61d7fe9a8c4700f19">llvm::MCAsmLexer::TokStart</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#a034a2fd8181cc28944d0a36f2ddbf6a3">llvm::MCAsmLexer::UnLex</a>.</p>


<p>Referenced by <a href="#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8">LexToken</a> and <a href="#a18e95622dd1cef434cddeae8612854d8">peekTokens</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getNextChar() {#aa8ea7b7a473abb1e3dd84c82760142c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int AsmLexer::getNextChar ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### isAtStartOfComment() {#a17dec07b2899ccf622a571b224635625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmLexer::isAtStartOfComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### isAtStatementSeparator() {#a91dd47ae840c35211cc784acc2b6fbca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AsmLexer::isAtStatementSeparator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### LexDigit() {#ae1df22768e543cc8adc0e8ab6fecdc96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken AsmLexer::LexDigit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexDigit: First character is [0-9].</p>


<p>Local Label: [0-9][:] Forward/Backward Label: [0-9][fb] Binary integer: 0b[01]+ Octal integer: 0[0-7]+ Hex integer: 0x[0-9a-fA-F]+ or [0x]?[0-9][0-9a-fA-F]*[hH] Decimal integer: [1-9][0-9]*</p>


<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### LexFloatLiteral() {#a257c524b69fc9619596157eecfe0de6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken AsmLexer::LexFloatLiteral ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The leading integral digit sequence and dot should have already been consumed, some or all of the fractional digit sequence <em>can</em> have been consumed.</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### LexHexFloatLiteral() {#a1ce0f2ccd4d0b41ff3c17986640bef07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken AsmLexer::LexHexFloatLiteral (bool NoIntDigits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexHexFloatLiteral matches essentially (.</p>


<p>[0-9a-fA-F]*)?[pP][+-]?[0-9a-fA-F]+ while making sure there are enough actual digits around for the constant to be valid.</p>


<p>The leading "0x[0-9a-fA-F]*" (i.e. integer part) has already been consumed before we get here.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### LexIdentifier() {#a530d1c83b94094de89a20d1bf956b74f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken AsmLexer::LexIdentifier ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### LexLineComment() {#adf469cf5c1ac6bbfe536600a9a84309f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken AsmLexer::LexLineComment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexLineComment: Comment: #[^
<br/>
]* : //[^
<br/>
]*.</p>

<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### LexQuote() {#a198ab63b4d62151d62bee9294f3d0a74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken AsmLexer::LexQuote ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexQuote: String: "...".</p>

<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### LexSingleQuote() {#a06dcd3c7a299c8348e80364d0a23e2f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken AsmLexer::LexSingleQuote ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexSingleQuote: Integer: 'b'.</p>

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### LexSlash() {#a6fce297825f118eb0a8758a95d6e273f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken AsmLexer::LexSlash ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexSlash: Slash: / C-Style Comment: /* ... *‍/ C-style Comment: // ...</p>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### LexUntilEndOfLine() {#a691964f50fbc398ffd0932b1fad63ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AsmLexer::LexUntilEndOfLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### peekNextChar() {#ade8f17e531fbf60b307dc0ee2a6f14c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int AsmLexer::peekNextChar ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

### ReturnError() {#ab9cc0a833b1230fc974d77fd506abeaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken AsmLexer::ReturnError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReturnError - Set the error to the specified string at the specified location.</p>


<p>This is defined to always return <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012">AsmToken::Error</a>.</p>


<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurBuf {#ac0eaed4579b1202f172e3f3b4e2df6ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AsmLexer::CurBuf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>.</p>

</div>
</div>

### CurPtr {#ad3f2f47b9767ccfcf66ac446c6b32185}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::AsmLexer::CurPtr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>.</p>

</div>
</div>

### EndStatementAtEOF {#aab88cc2a1ec3417333fa33cd7bc2b71a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AsmLexer::EndStatementAtEOF = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>.</p>

</div>
</div>

### IsAtStartOfLine {#ab86bd74328f94fa40e9111cf4be2c02c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AsmLexer::IsAtStartOfLine = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>.</p>

</div>
</div>

### IsAtStartOfStatement {#a706902cb773df7f7dbe3f7382b8823fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AsmLexer::IsAtStartOfStatement = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>.</p>

</div>
</div>

### IsPeeking {#ac66424f3c36d601ca62ed80c8d04dcb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AsmLexer::IsPeeking = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>.</p>

</div>
</div>

### MAI {#ab02b32526387a336235d8b2dc6b9f4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmInfo&amp; llvm::AsmLexer::MAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmlexer-h">AsmLexer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp">AsmLexer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
