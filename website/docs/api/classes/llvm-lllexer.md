---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lllexer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LLLexer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LLLexer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">llvm/AsmParser/LLLexer.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> <a href="#a8ba87c44f4d51a249fbf317476e120dd">LocTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ErrorPriority { <a href="#a00063c626777d5b1b7669999ed01a82e">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a550a9224847f5997d72ade652885b4f8">LLLexer</a> (StringRef StartBuf, SourceMgr &amp;SM, SMDiagnostic &amp;, LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b1da9a5f64660d2bf35d3ee3693a892">Lex</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8ba87c44f4d51a249fbf317476e120dd">LocTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81a6260afd03d49c34d264878ee536ec">getLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d0739296422d2d57a72798f73496eb8">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5401f3c97b303be13b5addb4aefd1099">getStrVal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7115f84f164a5b7d5ce7cdf78ef25b70">getTyVal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18cb4b08f3026dc01ce3d8f8970a1af9">getUIntVal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b5af5940a123fad2d3c0eced7291f64">getAPSIntVal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3ee0b4f9ba7a89249a021674ab97bbd">getAPFloatVal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f70869d091d440fe3f988e6895a1423">setIgnoreColonInIdentifiers</a> (bool val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08fe8c37bab0ac644973c425ef9ff89e">ParseError</a> (LocTy ErrorLoc, const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6217e100e1f79d145dc8edb338bad3a">ParseError</a> (const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4254cd5d352fad04709da8564c01413c">Warning</a> (LocTy WarningLoc, const Twine &amp;Msg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6609be94c502be98d0d68b2be12a82e5">Warning</a> (const Twine &amp;Msg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebdd211dcc391e7501ef56196a3eed7d">LexToken</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd552a590c8e9ca00afe47fb962803a0">getNextChar</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b7f51deabff1e479dcbff94ceb7f1d2">SkipLineComment</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f0d07413db8352461031d315fa31c89">SkipCComment</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This skips C-style /‍. <a href="#a2f0d07413db8352461031d315fa31c89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a357f4e9adc2114ce5519f87884f05f1f">ReadString</a> (lltok::Kind kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReadString - Read a string until the closing quote. <a href="#a357f4e9adc2114ce5519f87884f05f1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08eef1f7882dab2070635478d527da26">ReadVarName</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReadVarName - Read the rest of a token containing a variable name. <a href="#a08eef1f7882dab2070635478d527da26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b5b58df546a2d7d887b9e62e644200">LexIdentifier</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lex a label, integer type, keyword, or hexadecimal integer constant. <a href="#ac8b5b58df546a2d7d887b9e62e644200">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e4ecb90f9f47dbbb9eaa4df10984cfc">LexDigitOrNegative</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lex tokens for a label or a numeric constant, possibly starting with -. <a href="#a7e4ecb90f9f47dbbb9eaa4df10984cfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e6bba9fdb8b9b83664b49eb2addda7">LexPositive</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lex a floating point constant starting with +. <a href="#a57e6bba9fdb8b9b83664b49eb2addda7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c00cbeb965c960e9b8ac746cc7528e">LexAt</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lex all tokens that start with an @ character. <a href="#ad1c00cbeb965c960e9b8ac746cc7528e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5182c6bce4b7618953dee9301c8bc4ab">LexDollar</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a309068a02839249a37073af188b580">LexExclaim</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lex all tokens that start with a ! <a href="#a9a309068a02839249a37073af188b580">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ef09eda598adf9f7976478aaeb1753">LexPercent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lex all tokens that start with a % character. <a href="#a10ef09eda598adf9f7976478aaeb1753">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45c5639237be6d9dcce666377d7230c">LexUIntID</a> (lltok::Kind Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe24b58cc43e7d8ce00913511b3e2efe">LexVar</a> (lltok::Kind Var, lltok::Kind VarID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52863f8ea8943c513367753b65ce2564">LexQuote</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lex all tokens that start with a " character. <a href="#a52863f8ea8943c513367753b65ce2564">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdb84f3f7d739d61c017d3e8b967a5ca">Lex0x</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lex all tokens that start with a 0x prefix, knowing they match and are not labels. <a href="#abdb84f3f7d739d61c017d3e8b967a5ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85710972ca84dc397efacaba36a8a2fd">LexHash</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lex all tokens that start with a # character. <a href="#a85710972ca84dc397efacaba36a8a2fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d29d4925b133677ccb26d09e51508a6">LexCaret</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lex all tokens that start with a ^ character. <a href="#a8d29d4925b133677ccb26d09e51508a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb908c15f3e920ae9a601c90b92a1e5e">atoull</a> (const char *Buffer, const char *End)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95cff6dbe31b22895d94888d129bbce4">HexIntToVal</a> (const char *Buffer, const char *End)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1b50595d080909189a8623c72439ce9">HexToIntPair</a> (const char *Buffer, const char *End, uint64_t Pair[2])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ec70c4df80ea6f9c26d98b6184cdd85">FP80HexToIntPair</a> (const char *Buffer, const char *End, uint64_t Pair[2])</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FP80HexToIntPair - translate an 80 bit FP80 number (20 hexits) into { low64, high16 } as usual for an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#a7ec70c4df80ea6f9c26d98b6184cdd85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12fb567d3d7f38ded00faa1661b2e448">Error</a> (LocTy ErrorLoc, const Twine &amp;Msg, ErrorPriority Origin)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05035ec333afca12890d314a34904e37">LexError</a> (LocTy ErrorLoc, const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06309d2aea055dc453c89bc7ef4db9c5">LexError</a> (const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf12e598147bcb88e39e55312f7cbbc1">CurPtr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae624acaf222d281bf2c5ddc9419603">CurBuf</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a18635a0c63778ac1f3453b0297f8ba">ErrorInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcf392b9a897f4b6ab0442169ee4e4a6">SM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5df3edc04912c068b564796f4edce76">Context</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e0501e2895f7d6be43693a478c0eab">TokStart</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a984e031376db7a846b07687458f590fc">CurKind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a780e62a18337a4a62f94109177c69d70">StrVal</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e6a8d2daae5f4a00f72c0b7c299ec2">UIntVal</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa61a12ba6eb2d8e0d2958845f9e6bb04">TyVal</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fc5b0369f96c5bcb35e9219eb597ffd">APFloatVal</a> {0.0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8275bfacafd6fe06756af74e84db5358">APSIntVal</a> {0}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0ac8017696c4099af308ec73dc6ea0b">IgnoreColonInIdentifiers</a> = false</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LocTy {#a8ba87c44f4d51a249fbf317476e120dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SMLoc llvm::LLLexer::LocTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ErrorPriority {#a00063c626777d5b1b7669999ed01a82e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::LLLexer::ErrorPriority </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">None<a id="a00063c626777d5b1b7669999ed01a82ea6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Parser<a id="a00063c626777d5b1b7669999ed01a82ea9a83ab0d60fed7c37d928ccb30d1b6ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lexer<a id="a00063c626777d5b1b7669999ed01a82eac99c8065d9a0587b2171ca8644cac62d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LLLexer() {#a550a9224847f5997d72ade652885b4f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLLexer::LLLexer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StartBuf, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Err, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAPFloatVal() {#ae3ee0b4f9ba7a89249a021674ab97bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APFloat &amp; llvm::LLLexer::getAPFloatVal ()</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### getAPSIntVal() {#a9b5af5940a123fad2d3c0eced7291f64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APSInt &amp; llvm::LLLexer::getAPSIntVal ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### getKind() {#a2d0739296422d2d57a72798f73496eb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind llvm::LLLexer::getKind ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### getLoc() {#a81a6260afd03d49c34d264878ee536ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocTy llvm::LLLexer::getLoc ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>.</p>


<p>Referenced by <a href="#af6217e100e1f79d145dc8edb338bad3a">ParseError</a> and <a href="#a6609be94c502be98d0d68b2be12a82e5">Warning</a>.</p>

</div>
</div>

### getStrVal() {#a5401f3c97b303be13b5addb4aefd1099}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::LLLexer::getStrVal ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### getTyVal() {#a7115f84f164a5b7d5ce7cdf78ef25b70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::LLLexer::getTyVal ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### getUIntVal() {#a18cb4b08f3026dc01ce3d8f8970a1af9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LLLexer::getUIntVal ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### Lex() {#a0b1da9a5f64660d2bf35d3ee3693a892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind llvm::LLLexer::Lex ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### ParseError() {#a08fe8c37bab0ac644973c425ef9ff89e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLLexer::ParseError (<a href="#a8ba87c44f4d51a249fbf317476e120dd">LocTy</a> ErrorLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>.</p>

</div>
</div>

### ParseError() {#af6217e100e1f79d145dc8edb338bad3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLLexer::ParseError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>


<p>References <a href="#a81a6260afd03d49c34d264878ee536ec">getLoc</a> and <a href="#af6217e100e1f79d145dc8edb338bad3a">ParseError</a>.</p>


<p>Referenced by <a href="#af6217e100e1f79d145dc8edb338bad3a">ParseError</a>.</p>

</div>
</div>

### setIgnoreColonInIdentifiers() {#a9f70869d091d440fe3f988e6895a1423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LLLexer::setIgnoreColonInIdentifiers (bool val)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### Warning() {#a4254cd5d352fad04709da8564c01413c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLLexer::Warning (<a href="#a8ba87c44f4d51a249fbf317476e120dd">LocTy</a> WarningLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777a6bcc8ac9374461ed0599334db63365d0">llvm::SourceMgr::DK_Warning</a>.</p>

</div>
</div>

### Warning() {#a6609be94c502be98d0d68b2be12a82e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LLLexer::Warning (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>


<p>References <a href="#a81a6260afd03d49c34d264878ee536ec">getLoc</a> and <a href="#a6609be94c502be98d0d68b2be12a82e5">Warning</a>.</p>


<p>Referenced by <a href="#a6609be94c502be98d0d68b2be12a82e5">Warning</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### atoull() {#abb908c15f3e920ae9a601c90b92a1e5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLLexer::atoull (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### Error() {#a12fb567d3d7f38ded00faa1661b2e448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLLexer::Error (<a href="#a8ba87c44f4d51a249fbf317476e120dd">LocTy</a> ErrorLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, ErrorPriority Priority)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### FP80HexToIntPair() {#a7ec70c4df80ea6f9c26d98b6184cdd85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLLexer::FP80HexToIntPair (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * End, uint64_t Pair=[2])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FP80HexToIntPair - translate an 80 bit FP80 number (20 hexits) into { low64, high16 } as usual for an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>

<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### getNextChar() {#acd552a590c8e9ca00afe47fb962803a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLLexer::getNextChar ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### HexIntToVal() {#a95cff6dbe31b22895d94888d129bbce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLLexer::HexIntToVal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### HexToIntPair() {#af1b50595d080909189a8623c72439ce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLLexer::HexToIntPair (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * End, uint64_t Pair=[2])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### Lex0x() {#abdb84f3f7d739d61c017d3e8b967a5ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::Lex0x ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lex all tokens that start with a 0x prefix, knowing they match and are not labels.</p>


<p>HexFPConstant 0x[0-9A-Fa-f]+ HexFP80Constant 0xK[0-9A-Fa-f]+ HexFP128Constant 0xL[0-9A-Fa-f]+ HexPPC128Constant 0xM[0-9A-Fa-f]+ HexHalfConstant 0xH[0-9A-Fa-f]+ HexBFloatConstant 0xR[0-9A-Fa-f]+</p>


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexAt() {#ad1c00cbeb965c960e9b8ac746cc7528e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexAt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lex all tokens that start with an @ character.</p>


<p>GlobalVar \"[^\"]*\" GlobalVar @[-a-zA-Z$._][-a-zA-Z$._0-9]* GlobalVarID @[0-9]+</p>


<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexCaret() {#a8d29d4925b133677ccb26d09e51508a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexCaret ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lex all tokens that start with a ^ character.</p>


<p>SummaryID ::= ^[0-9]+</p>


<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexDigitOrNegative() {#a7e4ecb90f9f47dbbb9eaa4df10984cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexDigitOrNegative ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lex tokens for a label or a numeric constant, possibly starting with -.</p>


<p>Label [-a-zA-Z$._0-9]+: NInteger -[0-9]+ FPConstant [-+]?[0-9]+[.][0-9]*([eE][-+]?[0-9]+)? PInteger [0-9]+ HexFPConstant 0x[0-9A-Fa-f]+ HexFP80Constant 0xK[0-9A-Fa-f]+ HexFP128Constant 0xL[0-9A-Fa-f]+ HexPPC128Constant 0xM[0-9A-Fa-f]+</p>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexDollar() {#a5182c6bce4b7618953dee9301c8bc4ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexDollar ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexError() {#a05035ec333afca12890d314a34904e37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LLLexer::LexError (<a href="#a8ba87c44f4d51a249fbf317476e120dd">LocTy</a> ErrorLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### LexError() {#a06309d2aea055dc453c89bc7ef4db9c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LLLexer::LexError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### LexExclaim() {#a9a309068a02839249a37073af188b580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexExclaim ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lex all tokens that start with a !</p>


<p>character. !foo !</p>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexHash() {#a85710972ca84dc397efacaba36a8a2fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexHash ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lex all tokens that start with a # character.</p>


<p>AttrGrpID ::= #[0-9]+ Hash ::= #</p>


<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexIdentifier() {#ac8b5b58df546a2d7d887b9e62e644200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexIdentifier ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lex a label, integer type, keyword, or hexadecimal integer constant.</p>


<p>Label [-a-zA-Z$._0-9]+: <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> i[0-9]+ Keyword sdiv, float, ... HexIntConstant [us]0x[0-9A-Fa-f]+</p>


<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexPercent() {#a10ef09eda598adf9f7976478aaeb1753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexPercent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lex all tokens that start with a % character.</p>


<p>LocalVar ::= %"[^"]*" LocalVar ::= %[-a-zA-Z$._][-a-zA-Z$._0-9]* LocalVarID ::= %[0-9]+</p>


<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexPositive() {#a57e6bba9fdb8b9b83664b49eb2addda7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexPositive ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lex a floating point constant starting with +.</p>


<p>FPConstant [-+]?[0-9]+[.][0-9]*([eE][-+]?[0-9]+)?</p>


<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 1200 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexQuote() {#a52863f8ea8943c513367753b65ce2564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexQuote ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lex all tokens that start with a " character.</p>


<p>QuoteLabel "[^"]+":
  StringConstant    "[^"]*"</p>


<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexToken() {#aebdd211dcc391e7501ef56196a3eed7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexToken ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexUIntID() {#af45c5639237be6d9dcce666377d7230c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexUIntID (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> Token)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### LexVar() {#afe24b58cc43e7d8ce00913511b3e2efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::LexVar (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> Var, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> VarID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### ReadString() {#a357f4e9adc2114ce5519f87884f05f1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind LLLexer::ReadString (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReadString - Read a string until the closing quote.</p>

<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### ReadVarName() {#a08eef1f7882dab2070635478d527da26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LLLexer::ReadVarName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReadVarName - Read the rest of a token containing a variable name.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### SkipCComment() {#a2f0d07413db8352461031d315fa31c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">comments Returns true if there *was an error *bool LLLexer::SkipCComment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This skips C-style /‍.</p>

<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

### SkipLineComment() {#a4b7f51deabff1e479dcbff94ceb7f1d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLLexer::SkipLineComment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### APFloatVal {#a8fc5b0369f96c5bcb35e9219eb597ffd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::LLLexer::APFloatVal {0.0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### APSIntVal {#a8275bfacafd6fe06756af74e84db5358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::LLLexer::APSIntVal {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### Context {#aa5df3edc04912c068b564796f4edce76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; llvm::LLLexer::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### CurBuf {#a3ae624acaf222d281bf2c5ddc9419603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::LLLexer::CurBuf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### CurKind {#a984e031376db7a846b07687458f590fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lltok::Kind llvm::LLLexer::CurKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### CurPtr {#abf12e598147bcb88e39e55312f7cbbc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::LLLexer::CurPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### ErrorInfo {#a7a18635a0c63778ac1f3453b0297f8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm::LLLexer::ErrorInfo llvm::LLLexer::ErrorInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### IgnoreColonInIdentifiers {#ae0ac8017696c4099af308ec73dc6ea0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLLexer::IgnoreColonInIdentifiers = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### SM {#afcf392b9a897f4b6ab0442169ee4e4a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr&amp; llvm::LLLexer::SM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### StrVal {#a780e62a18337a4a62f94109177c69d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LLLexer::StrVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### TokStart {#ae7e0501e2895f7d6be43693a478c0eab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::LLLexer::TokStart</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### TyVal {#aa61a12ba6eb2d8e0d2958845f9e6bb04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::LLLexer::TyVal = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

### UIntVal {#a02e6a8d2daae5f4a00f72c0b7c299ec2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LLLexer::UIntVal = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lllexer-h">LLLexer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/asmparser/lllexer-cpp">LLLexer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
