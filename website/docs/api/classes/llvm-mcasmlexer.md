---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcasmlexer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCAsmLexer` Class

<p>Generic assembler lexer interface, for use by target specific assembly lexers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCAsmLexer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">llvm/MC/MCParser/MCAsmLexer.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmlexer">AsmLexer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/asmlexer">AsmLexer</a> - Lexer class for assembly files. <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a542dece65344b7d013c729b27659d1bd">MCAsmLexer</a> (const MCAsmLexer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cc9a9558fc4a9b798c4e4e678a10d83">MCAsmLexer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbdbaf82bb70736c2652c0e2d12e463c">~MCAsmLexer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmlexer">MCAsmLexer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0712fe2c5dd593e5144adb71d9a590ce">operator=</a> (const MCAsmLexer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53eb41641168379037fde8952d5f01e">Lex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Consume the next token from the input stream and return it. <a href="#ac53eb41641168379037fde8952d5f01e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a034a2fd8181cc28944d0a36f2ddbf6a3">UnLex</a> (AsmToken const &amp;Token)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a471848eeb7b4f3a0facc3e84528159d0">isAtStartOfStatement</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a964fb4d0bf3e6dcdc3c9f323ef744d6b">LexUntilEndOfStatement</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54bfbf3752a7a79c026b8ffe73308cb6">getLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current source location. <a href="#a54bfbf3752a7a79c026b8ffe73308cb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd3bad41979d112344478f44007a551">getTok</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current (last) lexed token. <a href="#aacd3bad41979d112344478f44007a551">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15c6963070232572295ec73454d1ad84">peekTok</a> (bool ShouldSkipSpace=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look ahead at the next token to be lexed. <a href="#a15c6963070232572295ec73454d1ad84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0abcd1868c28ebd840f3afcc89d4284">peekTokens</a> (MutableArrayRef&lt; AsmToken &gt; Buf, bool ShouldSkipSpace=true)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look ahead an arbitrary number of tokens. <a href="#af0abcd1868c28ebd840f3afcc89d4284">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59a6bb403f7b5d494829196e988c848">getErrLoc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current error location. <a href="#aa59a6bb403f7b5d494829196e988c848">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ab8c42fdd5aace6049066a5c3478ac">getErr</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current error string. <a href="#af9ab8c42fdd5aace6049066a5c3478ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aada8db353e1a724d98d761da7e2cb94a">getKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the kind of current token. <a href="#aada8db353e1a724d98d761da7e2cb94a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9a2ad2c78d9254fe58140aef128b6ab">is</a> (AsmToken::TokenKind K) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the current token has kind <span class="doxyComputerOutput">K</span>. <a href="#ad9a2ad2c78d9254fe58140aef128b6ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a274996965acf3447ca933ddeba9145ce">isNot</a> (AsmToken::TokenKind K) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the current token has kind <span class="doxyComputerOutput">K</span>. <a href="#a274996965acf3447ca933ddeba9145ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab16ae12503b4bf57e5d891fa3eec9f19">setSkipSpace</a> (bool val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether spaces should be ignored by the lexer. <a href="#ab16ae12503b4bf57e5d891fa3eec9f19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a446d5927b92bd51164eb591aafd76536">getAllowAtInIdentifier</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab0aa2c8c8e4b819307e9babb78cfba1">setAllowAtInIdentifier</a> (bool v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bb79a93881c745bc31a798b4f5b8928">setAllowHashInIdentifier</a> (bool V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b54a645ed6af37f5520203174808d4">setCommentConsumer</a> (AsmCommentConsumer *CommentConsumer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f74f90078678fa895f595aee2a02ac">setLexMasmIntegers</a> (bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether to lex masm-style binary (e.g., 0b1101) and radix-specified literals (e.g., 0ABCh [hex], 576t [decimal], 77o [octal], 1101y [binary]). <a href="#aa7f74f90078678fa895f595aee2a02ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa102e898c09bbe0901b329189c22e800">useMasmDefaultRadix</a> (bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether to use masm-style default-radix integer literals. <a href="#aa102e898c09bbe0901b329189c22e800">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ff022c060a8498ee5574125200aad8e">getMasmDefaultRadix</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9026e075a93ea7cf8eea8bed557835d5">setMasmDefaultRadix</a> (unsigned Radix)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48efcb983940fb57407365e99f44ba0">setLexMasmHexFloats</a> (bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether to lex masm-style hex float literals, such as 3f800000r. <a href="#aa48efcb983940fb57407365e99f44ba0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e8e65425bf30d6913405f89822e614">setLexMasmStrings</a> (bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether to lex masm-style string literals, such as 'Can''t find file' and "This ""value"" not found". <a href="#a18e8e65425bf30d6913405f89822e614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89ddfdb1ed73274cdefd9f86e7476f61">setLexMotorolaIntegers</a> (bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether to lex Motorola-style integer literals, such as $deadbeef or %01010110. <a href="#a89ddfdb1ed73274cdefd9f86e7476f61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d54a8a398ef00a90a83ddb623f094c">setLexHLASMIntegers</a> (bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether to lex HLASM-flavour integers. For now this is only [0-9]*. <a href="#a19d54a8a398ef00a90a83ddb623f094c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0444d4931bb723a724c77837cf8e7cc">setLexHLASMStrings</a> (bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether to "lex" HLASM-flavour character and string literals. <a href="#ab0444d4931bb723a724c77837cf8e7cc">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afef88e4d1bfe7da9440f0f77f63e72d1">LexToken</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af190e00774c0c3297efbc82fb505e30a">SetError</a> (SMLoc errLoc, const std::string &amp;err)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac2076dcf6a840f61d7fe9a8c4700f19">TokStart</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23b5bae0c60695a979d7864a11661345">SkipSpace</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3c87fe4f2d3830147b43040ddc35034">AllowAtInIdentifier</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8890c39af28ea51e8ba8a72e77b0272">AllowHashInIdentifier</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab57f4b9df89bb6084d92f7592a528fb8">IsAtStartOfStatement</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1339f871fd5bd37a18caa2d991634a96">LexMasmHexFloats</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a908f62ddd808a995251e8546c5191138">LexMasmIntegers</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a268865558b1d5ef30e4dfc81c0422591">LexMasmStrings</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95131b9168fb87f1b59758f10e6b0fa9">LexMotorolaIntegers</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46a51d75962ede3cb04224d5311e1121">UseMasmDefaultRadix</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadebf978610820fe61fa522a89a97f94">DefaultRadix</a> = 10</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5446c8f5dd4711f40a348db7d6ecf45b">LexHLASMIntegers</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d9d6c13036cf05809fe08882c83237b">LexHLASMStrings</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmcommentconsumer">AsmCommentConsumer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da98be5bea9b2adad63cddee19f18e5">CommentConsumer</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14e83f6d1c2a53101f32e68548391663">CurTok</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current token, stored in the base class for faster access. <a href="#a14e83f6d1c2a53101f32e68548391663">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00ce2fb35afaa4cd4f1d2e13d5fc1d43">ErrLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The location and description of the current error. <a href="#a00ce2fb35afaa4cd4f1d2e13d5fc1d43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac04f0475109cbc012be8aea4e721142d">Err</a></td>
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

<p>Generic assembler lexer interface, for use by target specific assembly lexers.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCAsmLexer() {#a542dece65344b7d013c729b27659d1bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCAsmLexer::MCAsmLexer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer">MCAsmLexer</a> &amp;)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#a8cc9a9558fc4a9b798c4e4e678a10d83">MCAsmLexer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### MCAsmLexer() {#a8cc9a9558fc4a9b798c4e4e678a10d83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmLexer::MCAsmLexer ()</td>
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



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmlexer-cpp">MCAsmLexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1ff20331fe667c9bf3a49cc28516155e">llvm::AsmToken::Space</a>.</p>


<p>Referenced by <a href="#a542dece65344b7d013c729b27659d1bd">MCAsmLexer</a> and <a href="#a0712fe2c5dd593e5144adb71d9a590ce">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MCAsmLexer() {#abbdbaf82bb70736c2652c0e2d12e463c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmLexer::~MCAsmLexer ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a0712fe2c5dd593e5144adb71d9a590ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmLexer &amp; llvm::MCAsmLexer::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer">MCAsmLexer</a> &amp;)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#a8cc9a9558fc4a9b798c4e4e678a10d83">MCAsmLexer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAllowAtInIdentifier() {#a446d5927b92bd51164eb591aafd76536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::getAllowAtInIdentifier ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#ab3c87fe4f2d3830147b43040ddc35034">AllowAtInIdentifier</a>.</p>

</div>
</div>

### getErr() {#af9ab8c42fdd5aace6049066a5c3478ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::MCAsmLexer::getErr ()</td>
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

<p>Get the current error string.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#a18e95622dd1cef434cddeae8612854d8">llvm::AsmLexer::peekTokens</a>.</p>

</div>
</div>

### getErrLoc() {#aa59a6bb403f7b5d494829196e988c848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::MCAsmLexer::getErrLoc ()</td>
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

<p>Get the current error location.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#a18e95622dd1cef434cddeae8612854d8">llvm::AsmLexer::peekTokens</a>.</p>

</div>
</div>

### getKind() {#aada8db353e1a724d98d761da7e2cb94a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken::TokenKind llvm::MCAsmLexer::getKind ()</td>
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

<p>Get the kind of current token.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a792392c4dfe6e57615554204b0c51a2e">llvm::AsmToken::getKind</a> and <a href="#aacd3bad41979d112344478f44007a551">getTok</a>.</p>

</div>
</div>

### getLoc() {#a54bfbf3752a7a79c026b8ffe73308cb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc MCAsmLexer::getLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the current source location.</p>

<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmlexer-cpp">MCAsmLexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a> and <a href="#aac2076dcf6a840f61d7fe9a8c4700f19">TokStart</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#acb5fd683cbbfb19a2e0d78ee46bb283c">llvm::MCAsmParserExtension::parseDirectiveCGProfile</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ae577a9371ea38b78cffc39d0ca5f6623">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#aa91d3c1b093e3561b948794724961f4b">anonymous{AsmParser.cpp}::AsmParser::parseIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#af6dea9845d70ac952115bdbe378dbea1">anonymous{MasmParser.cpp}::MasmParser::parseIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a1c3ac00eab4ed0328bc8c8942957c83b">anonymous{MasmParser.cpp}::MasmParser::parseRealValue</a>.</p>

</div>
</div>

### getMasmDefaultRadix() {#a9ff022c060a8498ee5574125200aad8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCAsmLexer::getMasmDefaultRadix ()</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#aadebf978610820fe61fa522a89a97f94">DefaultRadix</a>.</p>

</div>
</div>

### getTok() {#aacd3bad41979d112344478f44007a551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AsmToken &amp; llvm::MCAsmLexer::getTok ()</td>
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

<p>Get the current (last) lexed token.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#aada8db353e1a724d98d761da7e2cb94a">getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="#ad9a2ad2c78d9254fe58140aef128b6ab">is</a>, <a href="#a274996965acf3447ca933ddeba9145ce">isNot</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ae577a9371ea38b78cffc39d0ca5f6623">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseExpression</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#a64ef2d014c82249a7bc8cb033757d7f1">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseOperand</a>.</p>

</div>
</div>

### is() {#ad9a2ad2c78d9254fe58140aef128b6ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::is (<a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> K)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the current token has kind <span class="doxyComputerOutput">K</span>.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>References <a href="#aacd3bad41979d112344478f44007a551">getTok</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a710e72de4b87af42e7605679d1fb2c24">llvm::AsmToken::is</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8">llvm::AsmLexer::LexToken</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>.</p>

</div>
</div>

### isAtStartOfStatement() {#a471848eeb7b4f3a0facc3e84528159d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::isAtStartOfStatement ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#ab57f4b9df89bb6084d92f7592a528fb8">IsAtStartOfStatement</a>.</p>

</div>
</div>

### isNot() {#a274996965acf3447ca933ddeba9145ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::isNot (<a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> K)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the current token has kind <span class="doxyComputerOutput">K</span>.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>References <a href="#aacd3bad41979d112344478f44007a551">getTok</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a2f492d3c8c226803c571528284a95d36">llvm::AsmToken::isNot</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#a6c0aead93728457ceebf342312b92807">expectAbsExpression</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#a7a374b13bc9d10c9298dd591ee50fc82">parseExpr</a>.</p>

</div>
</div>

### Lex() {#ac53eb41641168379037fde8952d5f01e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AsmToken &amp; llvm::MCAsmLexer::Lex ()</td>
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

<p>Consume the next token from the input stream and return it.</p>


<p>The lexer will continuously return the end-of-file token once the end of the main input file has been reached.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="#ab57f4b9df89bb6084d92f7592a528fb8">IsAtStartOfStatement</a>, <a href="#afef88e4d1bfe7da9440f0f77f63e72d1">LexToken</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afe58695435b93e0599ed2f77e877a0aa">llvm::MCAsmParser::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#a6c0aead93728457ceebf342312b92807">expectAbsExpression</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#a7a374b13bc9d10c9298dd591ee50fc82">parseExpr</a>.</p>

</div>
</div>

### LexUntilEndOfStatement() {#a964fb4d0bf3e6dcdc3c9f323ef744d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringRef llvm::MCAsmLexer::LexUntilEndOfStatement ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>

</div>
</div>

### peekTok() {#a15c6963070232572295ec73454d1ad84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AsmToken llvm::MCAsmLexer::peekTok (bool ShouldSkipSpace=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Look ahead at the next token to be lexed.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af0abcd1868c28ebd840f3afcc89d4284">peekTokens</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>.</p>

</div>
</div>

### peekTokens() {#af0abcd1868c28ebd840f3afcc89d4284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual size_t llvm::MCAsmLexer::peekTokens (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &gt; Buf, bool ShouldSkipSpace=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look ahead an arbitrary number of tokens.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#a15c6963070232572295ec73454d1ad84">peekTok</a>.</p>

</div>
</div>

### setAllowAtInIdentifier() {#aab0aa2c8c8e4b819307e9babb78cfba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::setAllowAtInIdentifier (bool v)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#ab3c87fe4f2d3830147b43040ddc35034">AllowAtInIdentifier</a>.</p>

</div>
</div>

### setAllowHashInIdentifier() {#a0bb79a93881c745bc31a798b4f5b8928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::setAllowHashInIdentifier (bool V)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#af8890c39af28ea51e8ba8a72e77b0272">AllowHashInIdentifier</a>.</p>

</div>
</div>

### setCommentConsumer() {#a27b54a645ed6af37f5520203174808d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::setCommentConsumer (<a href="/web-llvm/docs/api/classes/llvm/asmcommentconsumer">AsmCommentConsumer</a> * CommentConsumer)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#a5da98be5bea9b2adad63cddee19f18e5">CommentConsumer</a>.</p>

</div>
</div>

### setLexHLASMIntegers() {#a19d54a8a398ef00a90a83ddb623f094c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::setLexHLASMIntegers (bool V)</td>
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

<p>Set whether to lex HLASM-flavour integers. For now this is only [0-9]*.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#a5446c8f5dd4711f40a348db7d6ecf45b">LexHLASMIntegers</a>.</p>

</div>
</div>

### setLexHLASMStrings() {#ab0444d4931bb723a724c77837cf8e7cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::setLexHLASMStrings (bool V)</td>
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

<p>Set whether to "lex" HLASM-flavour character and string literals.</p>


<p>For now, setting this option to true, will disable lexing for character and string literals.</p>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#a3d9d6c13036cf05809fe08882c83237b">LexHLASMStrings</a>.</p>

</div>
</div>

### setLexMasmHexFloats() {#aa48efcb983940fb57407365e99f44ba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::setLexMasmHexFloats (bool V)</td>
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

<p>Set whether to lex masm-style hex float literals, such as 3f800000r.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#a1339f871fd5bd37a18caa2d991634a96">LexMasmHexFloats</a>.</p>

</div>
</div>

### setLexMasmIntegers() {#aa7f74f90078678fa895f595aee2a02ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::setLexMasmIntegers (bool V)</td>
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

<p>Set whether to lex masm-style binary (e.g., 0b1101) and radix-specified literals (e.g., 0ABCh [hex], 576t [decimal], 77o [octal], 1101y [binary]).</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#a908f62ddd808a995251e8546c5191138">LexMasmIntegers</a>.</p>

</div>
</div>

### setLexMasmStrings() {#a18e8e65425bf30d6913405f89822e614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::setLexMasmStrings (bool V)</td>
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

<p>Set whether to lex masm-style string literals, such as 'Can''t find file' and "This ""value"" not found".</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#a268865558b1d5ef30e4dfc81c0422591">LexMasmStrings</a>.</p>

</div>
</div>

### setLexMotorolaIntegers() {#a89ddfdb1ed73274cdefd9f86e7476f61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::setLexMotorolaIntegers (bool V)</td>
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

<p>Set whether to lex Motorola-style integer literals, such as $deadbeef or %01010110.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#a95131b9168fb87f1b59758f10e6b0fa9">LexMotorolaIntegers</a>.</p>

</div>
</div>

### setMasmDefaultRadix() {#a9026e075a93ea7cf8eea8bed557835d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::setMasmDefaultRadix (unsigned Radix)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#aadebf978610820fe61fa522a89a97f94">DefaultRadix</a>.</p>

</div>
</div>

### setSkipSpace() {#ab16ae12503b4bf57e5d891fa3eec9f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::setSkipSpace (bool val)</td>
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

<p>Set whether spaces should be ignored by the lexer.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#a23b5bae0c60695a979d7864a11661345">SkipSpace</a>.</p>

</div>
</div>

### UnLex() {#a034a2fd8181cc28944d0a36f2ddbf6a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::UnLex (<a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Token)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#ab57f4b9df89bb6084d92f7592a528fb8">IsAtStartOfStatement</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8">llvm::AsmLexer::LexToken</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ae577a9371ea38b78cffc39d0ca5f6623">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseExpression</a>.</p>

</div>
</div>

### useMasmDefaultRadix() {#aa102e898c09bbe0901b329189c22e800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::useMasmDefaultRadix (bool V)</td>
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

<p>Set whether to use masm-style default-radix integer literals.</p>


<p>If disabled, assume decimal unless prefixed (e.g., 0x2c [hex], 077 [octal]).</p>


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Reference <a href="#a46a51d75962ede3cb04224d5311e1121">UseMasmDefaultRadix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### LexToken() {#afef88e4d1bfe7da9440f0f77f63e72d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual AsmToken llvm::MCAsmLexer::LexToken ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#ac53eb41641168379037fde8952d5f01e">Lex</a>.</p>

</div>
</div>

### SetError() {#af190e00774c0c3297efbc82fb505e30a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCAsmLexer::SetError (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> errLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; err)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#a18e95622dd1cef434cddeae8612854d8">llvm::AsmLexer::peekTokens</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AllowAtInIdentifier {#ab3c87fe4f2d3830147b43040ddc35034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::AllowAtInIdentifier = false</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#a2cf3180e209a3079c3c08ab8c818a9ae">llvm::AsmLexer::AsmLexer</a>, <a href="#a446d5927b92bd51164eb591aafd76536">getAllowAtInIdentifier</a> and <a href="#aab0aa2c8c8e4b819307e9babb78cfba1">setAllowAtInIdentifier</a>.</p>

</div>
</div>

### AllowHashInIdentifier {#af8890c39af28ea51e8ba8a72e77b0272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::AllowHashInIdentifier = false</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#a0bb79a93881c745bc31a798b4f5b8928">setAllowHashInIdentifier</a>.</p>

</div>
</div>

### CommentConsumer {#a5da98be5bea9b2adad63cddee19f18e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmCommentConsumer* llvm::MCAsmLexer::CommentConsumer = nullptr</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#a27b54a645ed6af37f5520203174808d4">setCommentConsumer</a>.</p>

</div>
</div>

### DefaultRadix {#aadebf978610820fe61fa522a89a97f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCAsmLexer::DefaultRadix = 10</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#a9ff022c060a8498ee5574125200aad8e">getMasmDefaultRadix</a> and <a href="#a9026e075a93ea7cf8eea8bed557835d5">setMasmDefaultRadix</a>.</p>

</div>
</div>

### IsAtStartOfStatement {#ab57f4b9df89bb6084d92f7592a528fb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::IsAtStartOfStatement = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#a471848eeb7b4f3a0facc3e84528159d0">isAtStartOfStatement</a>, <a href="#ac53eb41641168379037fde8952d5f01e">Lex</a> and <a href="#a034a2fd8181cc28944d0a36f2ddbf6a3">UnLex</a>.</p>

</div>
</div>

### LexHLASMIntegers {#a5446c8f5dd4711f40a348db7d6ecf45b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::LexHLASMIntegers = false</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#a19d54a8a398ef00a90a83ddb623f094c">setLexHLASMIntegers</a>.</p>

</div>
</div>

### LexHLASMStrings {#a3d9d6c13036cf05809fe08882c83237b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::LexHLASMStrings = false</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#ab0444d4931bb723a724c77837cf8e7cc">setLexHLASMStrings</a>.</p>

</div>
</div>

### LexMasmHexFloats {#a1339f871fd5bd37a18caa2d991634a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::LexMasmHexFloats = false</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#aa48efcb983940fb57407365e99f44ba0">setLexMasmHexFloats</a>.</p>

</div>
</div>

### LexMasmIntegers {#a908f62ddd808a995251e8546c5191138}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::LexMasmIntegers = false</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#aa7f74f90078678fa895f595aee2a02ac">setLexMasmIntegers</a>.</p>

</div>
</div>

### LexMasmStrings {#a268865558b1d5ef30e4dfc81c0422591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::LexMasmStrings = false</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#a18e8e65425bf30d6913405f89822e614">setLexMasmStrings</a>.</p>

</div>
</div>

### LexMotorolaIntegers {#a95131b9168fb87f1b59758f10e6b0fa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::LexMotorolaIntegers = false</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#a2cf3180e209a3079c3c08ab8c818a9ae">llvm::AsmLexer::AsmLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8">llvm::AsmLexer::LexToken</a> and <a href="#a89ddfdb1ed73274cdefd9f86e7476f61">setLexMotorolaIntegers</a>.</p>

</div>
</div>

### SkipSpace {#a23b5bae0c60695a979d7864a11661345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::SkipSpace = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8">llvm::AsmLexer::LexToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#a18e95622dd1cef434cddeae8612854d8">llvm::AsmLexer::peekTokens</a> and <a href="#ab16ae12503b4bf57e5d891fa3eec9f19">setSkipSpace</a>.</p>

</div>
</div>

### TokStart {#aac2076dcf6a840f61d7fe9a8c4700f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::MCAsmLexer::TokStart = nullptr</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#a54bfbf3752a7a79c026b8ffe73308cb6">getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8">llvm::AsmLexer::LexToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#a564882070bf87421f0775ebd6cf64014">llvm::AsmLexer::LexUntilEndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#a18e95622dd1cef434cddeae8612854d8">llvm::AsmLexer::peekTokens</a> and <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#abf479f9ea9b5902aea9e0ab3fd50ad94">llvm::AsmLexer::setBuffer</a>.</p>

</div>
</div>

### UseMasmDefaultRadix {#a46a51d75962ede3cb04224d5311e1121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCAsmLexer::UseMasmDefaultRadix = false</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>


<p>Referenced by <a href="#aa102e898c09bbe0901b329189c22e800">useMasmDefaultRadix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurTok {#a14e83f6d1c2a53101f32e68548391663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AsmToken, 1&gt; llvm::MCAsmLexer::CurTok</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current token, stored in the base class for faster access.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>

</div>
</div>

### Err {#ac04f0475109cbc012be8aea4e721142d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCAsmLexer::Err</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>

</div>
</div>

### ErrLoc {#a00ce2fb35afaa4cd4f1d2e13d5fc1d43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::MCAsmLexer::ErrLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The location and description of the current error.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmlexer-h">MCAsmLexer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmlexer-cpp">MCAsmLexer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
