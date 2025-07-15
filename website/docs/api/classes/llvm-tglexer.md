---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/tglexer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TGLexer` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/tglexer">TGLexer</a> - <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> Lexer class. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TGLexer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TableGen/TGLexer.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::set&lt; std::string &gt; <a href="#afaf6bde3c87f4217358a4b4b89df79e2">DependenciesSetTy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d312b80b8aa4cd84456b0dfc3f4c6e">TGLexer</a> (SourceMgr &amp;SrcMgr, ArrayRef&lt; std::string &gt; Macros)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d4c7a0a8a974114e46b44769c3489d5">Lex</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#afaf6bde3c87f4217358a4b4b89df79e2">DependenciesSetTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb1f0667722fa49c6ccb2f17dd3505da">getDependencies</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab689f9d1e1e6fac6552e4e709b8a5eec">getCode</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fbd2a869619122ccc00185227129c6e">getCurStrVal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a808bbf264dc2cade1eded9a0e703281a">getCurIntVal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; int64_t, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95583e548bbd2f04af0ac69207ca32f1">getCurBinaryIntVal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6f58ed313b0cd532b86302fa6233296">getLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0764c89473b64b97aef3bb769eb3454e">getLocRange</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaa8691162e06464399f5a6aae797e08">LexToken</a> (bool FileOrLineStart=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexToken - Read the next token and return its code. <a href="#abaa8691162e06464399f5a6aae797e08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a733d2874d23340609381059643498cac">ReturnError</a> (SMLoc Loc, const Twine &amp;Msg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReturnError - Set the error to the specified string at the specified location. <a href="#a733d2874d23340609381059643498cac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae989eef562174715fd0467bd84f0be56">ReturnError</a> (const char *Loc, const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade4e1a25c61d8a455c581c10168fbe89">getNextChar</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2115de5332b02f3a82f121c5da47148d">peekNextChar</a> (int Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9ec08a5988de8f706d507794c96a24">SkipBCPLComment</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SkipBCPLComment - Skip over the comment by finding the next CR or LF. <a href="#a3f9ec08a5988de8f706d507794c96a24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd3f629110f0b33f2e1e6b890db7936f">SkipCComment</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SkipCComment - This skips C-style /‍. <a href="#abd3f629110f0b33f2e1e6b890db7936f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac669f921b57e8a2a9e209a57c52617">LexIdentifier</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5ef617d481fb90b346f98d37985c4af">LexInclude</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexInclude - We just read the "include" token. <a href="#ab5ef617d481fb90b346f98d37985c4af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9823a1536246a9a591cfa10b38bdc16">LexString</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexString - Lex "[^"]*". <a href="#ad9823a1536246a9a591cfa10b38bdc16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec1a7fd3730ff633f70f884f08b6943">LexVarName</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49bfaa63e55e48790a6770af0e438332">LexNumber</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexNumber - Lex: [-+]? <a href="#a49bfaa63e55e48790a6770af0e438332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd717a0a2494e328bda48a072285f4f">LexBracket</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexBracket - We just read '['. <a href="#a0bd717a0a2494e328bda48a072285f4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a856d8882d627bb0252ab6a3823bff7a3">LexExclaim</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexExclaim - Lex '!' and '![a-zA-Z]+'. <a href="#a856d8882d627bb0252ab6a3823bff7a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ed239d0c2994b26ae9e742b3c9ccb8d">processEOF</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d7a1715eac6910fda0bbdaf4110365">prepExitInclude</a> (bool IncludeStackMustBeEmpty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e8bc68528079a175e95dd2ddd1d30a5">prepIsDirective</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a867c1a1d065db380b7fec840eb9356ae">prepEatPreprocessorDirective</a> (tgtok::TokKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11abe11af6104f142a7e2473b2d2a2a8">lexPreprocessor</a> (tgtok::TokKind Kind, bool ReturnNextLiveToken=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad46198c35eb0f839a66ec208c24595c7">prepSkipRegion</a> (bool MustNeverBeFalse)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a691f1c61f879b2706abe4a57d2298544">prepLexMacroName</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89929a75258f31d596cc516565a92a74">prepSkipLineBegin</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1070b590e9eec3b7127af3cc262d03f">prepSkipDirectiveEnd</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af75d8acc29bbce5faf053fab765e6c1c">prepIsProcessingEnabled</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af49dee282006e804868f609449a2b61a">prepReportPreprocessorStackError</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea2a2b60088b4612fc4b6d090af7e5c9">SrcMgr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af039020c88799abd48abc6d6c988ecda">CurPtr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b61b5b61c15417bc909bd298f3d917">CurBuf</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32ca26162797459f35ce6b2082f93529">TokStart</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc1272f56de5aa7c812aeb0ac720caa">CurCode</a> = <a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5ad5504ffda0efa1de5ca3294f5ea86bbf">tgtok::TokKind::Eof</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0cbf714e04da02e991fa8d45ac3a5a1">CurStrVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93a64e9f07729822c53058d6811ce187">CurIntVal</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6671dbb282c185962a846ed772eac53f">CurBuffer</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CurBuffer - This is the current buffer index we're lexing from as managed by the <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> object. <a href="#a6671dbb282c185962a846ed772eac53f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afaf6bde3c87f4217358a4b4b89df79e2">DependenciesSetTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce146a0101ef78286d89ac99159f7d2">Dependencies</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dependencies - This is the list of all included files. <a href="#a1ce146a0101ef78286d89ac99159f7d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a919d7d6cb9698c847b7d0f6d04caf122">DefinedMacros</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; PreprocessorControlDesc &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af08ecf0885658f23a869f719704f112f">PrepIncludeStack</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/tglexer">TGLexer</a> - <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> Lexer class.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### DependenciesSetTy {#afaf6bde3c87f4217358a4b4b89df79e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::set&lt;std::string&gt; llvm::TGLexer::DependenciesSetTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TGLexer() {#af4d312b80b8aa4cd84456b0dfc3f4c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TGLexer::TGLexer (<a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SrcMgr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::string &gt; Macros)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp/#a8803ea8514e96d11aa51299ca02a008e">lexMacroName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCode() {#ab689f9d1e1e6fac6552e4e709b8a5eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind llvm::TGLexer::getCode ()</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

### getCurBinaryIntVal() {#a95583e548bbd2f04af0ac69207ca32f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; int64_t, unsigned &gt; llvm::TGLexer::getCurBinaryIntVal ()</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5a97d8c4bae82b44ebea73f7288c51fdc6">llvm::tgtok::BinaryIntVal</a>.</p>

</div>
</div>

### getCurIntVal() {#a808bbf264dc2cade1eded9a0e703281a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::TGLexer::getCurIntVal ()</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5a3a7597ca475c0fcf10856ef36351d1ac">llvm::tgtok::IntVal</a>.</p>

</div>
</div>

### getCurStrVal() {#a9fbd2a869619122ccc00185227129c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::TGLexer::getCurStrVal ()</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#aeb202308092eb993646d3f969e18e463">llvm::tgtok::isStringValue</a>.</p>

</div>
</div>

### getDependencies() {#afb1f0667722fa49c6ccb2f17dd3505da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DependenciesSetTy &amp; llvm::TGLexer::getDependencies ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

### getLoc() {#ae6f58ed313b0cd532b86302fa6233296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc TGLexer::getLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>.</p>


<p>Referenced by <a href="#a0764c89473b64b97aef3bb769eb3454e">getLocRange</a>.</p>

</div>
</div>

### getLocRange() {#a0764c89473b64b97aef3bb769eb3454e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMRange TGLexer::getLocRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a> and <a href="#ae6f58ed313b0cd532b86302fa6233296">getLoc</a>.</p>

</div>
</div>

### Lex() {#a4d4c7a0a8a974114e46b44769c3489d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind llvm::TGLexer::Lex ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getNextChar() {#ade4e1a25c61d8a455c581c10168fbe89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int TGLexer::getNextChar ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### LexBracket() {#a0bd717a0a2494e328bda48a072285f4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind TGLexer::LexBracket ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexBracket - We just read '['.</p>


<p>If this is a code block, return it, otherwise return the bracket. Match: '[' and '[{ ( [^}]+ | }[^]] )* }]'</p>


<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### LexExclaim() {#a856d8882d627bb0252ab6a3823bff7a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind TGLexer::LexExclaim ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexExclaim - Lex '!' and '![a-zA-Z]+'.</p>

<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### LexIdentifier() {#abac669f921b57e8a2a9e209a57c52617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind TGLexer::LexIdentifier ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### LexInclude() {#ab5ef617d481fb90b346f98d37985c4af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGLexer::LexInclude ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexInclude - We just read the "include" token.</p>


<p>Get the string token that comes next and enter the include.</p>


<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### LexNumber() {#a49bfaa63e55e48790a6770af0e438332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind TGLexer::LexNumber ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexNumber - Lex: [-+]?</p>


<p>[0-9]+ 0x[0-9a-fA-F]+ 0b[01]+</p>


<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### lexPreprocessor() {#a11abe11af6104f142a7e2473b2d2a2a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind TGLexer::lexPreprocessor (<a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a> Kind, bool ReturnNextLiveToken=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### LexString() {#ad9823a1536246a9a591cfa10b38bdc16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind TGLexer::LexString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexString - Lex "[^"]*".</p>

<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### LexToken() {#abaa8691162e06464399f5a6aae797e08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind TGLexer::LexToken (bool FileOrLineStart=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexToken - Read the next token and return its code.</p>

<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### LexVarName() {#a9ec1a7fd3730ff633f70f884f08b6943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind TGLexer::LexVarName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### peekNextChar() {#a2115de5332b02f3a82f121c5da47148d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int TGLexer::peekNextChar (int Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### prepEatPreprocessorDirective() {#a867c1a1d065db380b7fec840eb9356ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TGLexer::prepEatPreprocessorDirective (<a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5">tgtok::TokKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### prepExitInclude() {#a54d7a1715eac6910fda0bbdaf4110365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGLexer::prepExitInclude (bool IncludeStackMustBeEmpty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### prepIsDirective() {#a6e8bc68528079a175e95dd2ddd1d30a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind TGLexer::prepIsDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### prepIsProcessingEnabled() {#af75d8acc29bbce5faf053fab765e6c1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGLexer::prepIsProcessingEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### prepLexMacroName() {#a691f1c61f879b2706abe4a57d2298544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef TGLexer::prepLexMacroName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### prepReportPreprocessorStackError() {#af49dee282006e804868f609449a2b61a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TGLexer::prepReportPreprocessorStackError ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 1042 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### prepSkipDirectiveEnd() {#af1070b590e9eec3b7127af3cc262d03f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGLexer::prepSkipDirectiveEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 976 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### prepSkipLineBegin() {#a89929a75258f31d596cc516565a92a74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGLexer::prepSkipLineBegin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### prepSkipRegion() {#ad46198c35eb0f839a66ec208c24595c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGLexer::prepSkipRegion (bool MustNeverBeFalse)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### processEOF() {#a4ed239d0c2994b26ae9e742b3c9ccb8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TGLexer::processEOF ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### ReturnError() {#a733d2874d23340609381059643498cac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind TGLexer::ReturnError (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReturnError - Set the error to the specified string at the specified location.</p>


<p>This is defined to always return <a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5a857bb78262fafbb375c8ddb3bbb40786">tgtok::Error</a>.</p>


<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### ReturnError() {#ae989eef562174715fd0467bd84f0be56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind TGLexer::ReturnError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### SkipBCPLComment() {#a3f9ec08a5988de8f706d507794c96a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TGLexer::SkipBCPLComment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SkipBCPLComment - Skip over the comment by finding the next CR or LF.</p>


<p>Or we may end up at the end of the buffer.</p>


<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

### SkipCComment() {#abd3f629110f0b33f2e1e6b890db7936f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">comments The only difference from C *is that we allow nesting *bool TGLexer::SkipCComment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SkipCComment - This skips C-style /‍.</p>

<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>, definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurBuf {#ae7b61b5b61c15417bc909bd298f3d917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::TGLexer::CurBuf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

### CurBuffer {#a6671dbb282c185962a846ed772eac53f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TGLexer::CurBuffer = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CurBuffer - This is the current buffer index we're lexing from as managed by the <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> object.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

### CurCode {#a0fc1272f56de5aa7c812aeb0ac720caa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">tgtok::TokKind llvm::TGLexer::CurCode = <a href="/web-llvm/docs/api/namespaces/llvm/tgtok/#abbc5259d649363016626e2529fabe0c5ad5504ffda0efa1de5ca3294f5ea86bbf">tgtok::TokKind::Eof</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

### CurIntVal {#a93a64e9f07729822c53058d6811ce187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::TGLexer::CurIntVal = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

### CurPtr {#af039020c88799abd48abc6d6c988ecda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::TGLexer::CurPtr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

### CurStrVal {#af0cbf714e04da02e991fa8d45ac3a5a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::TGLexer::CurStrVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

### DefinedMacros {#a919d7d6cb9698c847b7d0f6d04caf122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet llvm::TGLexer::DefinedMacros</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

### Dependencies {#a1ce146a0101ef78286d89ac99159f7d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DependenciesSetTy llvm::TGLexer::Dependencies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dependencies - This is the list of all included files.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

### PrepIncludeStack {#af08ecf0885658f23a869f719704f112f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SmallVector&lt;PreprocessorControlDesc&gt; &gt; llvm::TGLexer::PrepIncludeStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

### SrcMgr {#aea2a2b60088b4612fc4b6d090af7e5c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr&amp; llvm::TGLexer::SrcMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

### TokStart {#a32ca26162797459f35ce6b2082f93529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::TGLexer::TokStart = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp">TGLexer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
