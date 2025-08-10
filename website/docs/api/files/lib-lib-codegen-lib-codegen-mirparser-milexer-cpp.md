---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MILexer.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include &lt;cassert&gt;
#include &lt;cctype&gt;
#include &lt;string&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-milexer-cpp-">anonymous{MILexer.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-milexer-cpp-/cursor">Cursor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class provides a way to iterate and get characters from the source string. <a href="/web-llvm/docs/api/classes/anonymous-milexer-cpp-/cursor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3fdb5af86c8d216e09424fdcd3bf9cd">skipWhitespace</a> (Cursor C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip the leading whitespace characters and return the updated cursor. <a href="#aa3fdb5af86c8d216e09424fdcd3bf9cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f27f361ff2fcd0a9d10701dbe22951c">isNewlineChar</a> (char C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c5042e84885ca59fa0cb59e307f01e">skipComment</a> (Cursor C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip a line comment and return the updated cursor. <a href="#a08c5042e84885ca59fa0cb59e307f01e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97f0d7559c1e0147978f08ea9ac463b2">skipMachineOperandComment</a> (Cursor C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Machine operands can have comments, enclosed between /* and <em>‍/. </em> <a href="#a97f0d7559c1e0147978f08ea9ac463b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab86f566b5a4fa3f73f3873d5caa9e6a5">isIdentifierChar</a> (char C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given character satisfies the following regular expression: [-a-zA-Z$._0-9]. <a href="#ab86f566b5a4fa3f73f3873d5caa9e6a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e63172c1d60457b773a5d356251ce45">unescapeQuotedString</a> (StringRef Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unescapes the given string value. <a href="#a7e63172c1d60457b773a5d356251ce45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc5a949b7276f9015ad9db64478cd46">lexStringConstant</a> (Cursor C, ErrorCallbackType ErrorCallback)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lex a string constant using the following regular expression: "[^"]*". <a href="#a1bc5a949b7276f9015ad9db64478cd46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a> (Cursor C, MIToken &amp;Token, MIToken::TokenKind Type, unsigned PrefixLength, ErrorCallbackType ErrorCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6">MIToken::TokenKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a343545c6308183cfae523bf627eb4373">getIdentifierKind</a> (StringRef Identifier)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e7e252de6ff5a1af41bfb17e92c7764">maybeLexIdentifier</a> (Cursor C, MIToken &amp;Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8a1ef6fb7c2e91c66607669addcbec9">maybeLexMachineBasicBlock</a> (Cursor C, MIToken &amp;Token, ErrorCallbackType ErrorCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcc4cdfb302bc22d1b9cdca6a419f7b7">maybeLexIndex</a> (Cursor C, MIToken &amp;Token, StringRef Rule, MIToken::TokenKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81dc0e46445de327a0956a30e6fc0662">maybeLexIndexAndName</a> (Cursor C, MIToken &amp;Token, StringRef Rule, MIToken::TokenKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a564a55d742dc949dd886dd9da92c0bbf">maybeLexJumpTableIndex</a> (Cursor C, MIToken &amp;Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa38483113957b327d241b4e71cdf3673">maybeLexStackObject</a> (Cursor C, MIToken &amp;Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc94ab461ed98cc2b12045e09cce6d67">maybeLexFixedStackObject</a> (Cursor C, MIToken &amp;Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9fb2421a934ca6abf18452c4cb72706">maybeLexConstantPoolItem</a> (Cursor C, MIToken &amp;Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb41fb2d4d98f026a60d1504d92b5a8c">maybeLexSubRegisterIndex</a> (Cursor C, MIToken &amp;Token, ErrorCallbackType ErrorCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34f0a3b30959de2e7847c340c2b0fea2">maybeLexIRBlock</a> (Cursor C, MIToken &amp;Token, ErrorCallbackType ErrorCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad97f43f2c733ae0b0506f078fb2768e0">maybeLexIRValue</a> (Cursor C, MIToken &amp;Token, ErrorCallbackType ErrorCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9cdd4ae7b2eddf8dcee53587086d900">maybeLexStringConstant</a> (Cursor C, MIToken &amp;Token, ErrorCallbackType ErrorCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68ca6d53c1a7e468c10ff026e307957a">lexVirtualRegister</a> (Cursor C, MIToken &amp;Token)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f93166a59bc27eac4a92002eb285ed3">isRegisterChar</a> (char C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true for a character allowed in a register name. <a href="#a0f93166a59bc27eac4a92002eb285ed3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a751d4b410566e7af9878b48ecb803a62">lexNamedVirtualRegister</a> (Cursor C, MIToken &amp;Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67fb11afc51aa3e8a17d67db0457cdf2">maybeLexRegister</a> (Cursor C, MIToken &amp;Token, ErrorCallbackType ErrorCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad03860fe4db1cfdfe373bf181829fb88">maybeLexGlobalValue</a> (Cursor C, MIToken &amp;Token, ErrorCallbackType ErrorCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaec7640dacf4b818d7a546977ba6463">maybeLexExternalSymbol</a> (Cursor C, MIToken &amp;Token, ErrorCallbackType ErrorCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95bd4c442d09906ba3a98a436150d637">maybeLexMCSymbol</a> (Cursor C, MIToken &amp;Token, ErrorCallbackType ErrorCallback)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ccc48fb47ca955cf7e57dc05fa34041">isValidHexFloatingPointPrefix</a> (char C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af424d285ff5841f2b72740200a19fc52">lexFloatingPointLiteral</a> (Cursor Range, Cursor C, MIToken &amp;Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a681d6dc497d72f781f0d6e37ef92adf6">maybeLexHexadecimalLiteral</a> (Cursor C, MIToken &amp;Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f2a6cc3ecc29db91025a59a8b2719b1">maybeLexNumericalLiteral</a> (Cursor C, MIToken &amp;Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6">MIToken::TokenKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d70692332178cbc52cf13297525771c">getMetadataKeywordKind</a> (StringRef Identifier)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7167f37d6c009e5ab809b1e4a8a7c81f">maybeLexExclaim</a> (Cursor C, MIToken &amp;Token, ErrorCallbackType ErrorCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6">MIToken::TokenKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b858f5e91ffcd108c71029f7171a8ff">symbolToken</a> (char C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4820a34a5c7d00417a38c0cf2321f9f3">maybeLexSymbol</a> (Cursor C, MIToken &amp;Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f361b0c5074bb978be4e17286449842">maybeLexNewline</a> (Cursor C, MIToken &amp;Token)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Cursor</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01f74b24df78737ec2f22b65d2f37c91">maybeLexEscapedIRValue</a> (Cursor C, MIToken &amp;Token, ErrorCallbackType ErrorCallback)</td>
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

## Functions

### getIdentifierKind() {#a343545c6308183cfae523bf627eb4373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIToken::TokenKind getIdentifierKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Identifier)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a0943c04acc16f5a20793de60d48cfc93">llvm::MIToken::kw_addrspace</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a356311228b5226914a5e28765271885b">llvm::MIToken::kw_afn</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2b36847798e6a577ff1a459d436716cc">llvm::MIToken::kw_align</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a645f437737bb0546525fb281fcc101fe">llvm::MIToken::kw_arcp</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8fa817130e25e7d76dba39a1bd0962ee">llvm::MIToken::kw_basealign</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a36279270727e3d0a5a71ed49bc937df8">llvm::MIToken::kw_bb_id</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aff7ad41fba511dad3cf8ed9165271232">llvm::MIToken::kw_bbsections</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a59ea063561870edcff0bdd8f0d95b1a2">llvm::MIToken::kw_bfloat</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a10b64d0278daea287b892ac95f4a70c1">llvm::MIToken::kw_blockaddress</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a706a66b904c74b059eb4094498c964fc">llvm::MIToken::kw_call_entry</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a294c5581d42ad37196ca937c31e8598e">llvm::MIToken::kw_call_frame_size</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a312a88bc3c813a44c29c661d9e981769">llvm::MIToken::kw_cfi_aarch64_negate_ra_sign_state</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9741536facc1c8c790ac0929276d2bef">llvm::MIToken::kw_cfi_aarch64_negate_ra_sign_state_with_pc</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa4c84979e85e8fa30a9d33d7ebe59ca5">llvm::MIToken::kw_cfi_adjust_cfa_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa94c3b98223057a43e6d39505f4a6e5f">llvm::MIToken::kw_cfi_def_cfa</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aaec8c69ba4f771177000277c8e2403b3">llvm::MIToken::kw_cfi_def_cfa_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9b449f07ddab22c2e49164fc2aee112c">llvm::MIToken::kw_cfi_def_cfa_register</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa99f8585275a495b73a9319979194b5a">llvm::MIToken::kw_cfi_escape</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a3cc78b122a3960aed2a370a5241e6015">llvm::MIToken::kw_cfi_llvm_def_aspace_cfa</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4cefddc97b52262ec3ca131128079be4">llvm::MIToken::kw_cfi_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8f3b8e825a1b96c0feb33b74c56eb891">llvm::MIToken::kw_cfi_register</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a94740fe117708e6e5de35dea49614ad0">llvm::MIToken::kw_cfi_rel_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae264c83e0df5209a1dfcd322b0d0e74a">llvm::MIToken::kw_cfi_remember_state</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a836ad743b6d5b6e1d0bd80e05f42812c">llvm::MIToken::kw_cfi_restore</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aee2c9ff26df9a29da2a3b5409cfde779">llvm::MIToken::kw_cfi_restore_state</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9d9cd9b85ae5fce2a539f56fb037766a">llvm::MIToken::kw_cfi_same_value</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8a6dea4150203fad21673ccf124a968b">llvm::MIToken::kw_cfi_type</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7bb4c83768ee2a94a0a21aa1a0815752">llvm::MIToken::kw_cfi_undefined</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a712ca0bbf0925efcb0f451e6a53357ed">llvm::MIToken::kw_cfi_window_save</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a76138fb77b2f732e63b38f1e7065d383">llvm::MIToken::kw_constant_pool</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1629a3eb67efd22303ce5458746b3cab">llvm::MIToken::kw_contract</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab93677f69d0041e06070c90910dcc30b">llvm::MIToken::kw_custom</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a44c287f7c3c0e3293241bde17a716828">llvm::MIToken::kw_dbg_instr_ref</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a3c27c3f12ff5eac92e28e03d48af0a58">llvm::MIToken::kw_dead</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae3b209d9029d0e9a79026e60f8328f23">llvm::MIToken::kw_debug_instr_number</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6afae5d39056b30c2d5219236ee0650abc">llvm::MIToken::kw_debug_location</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a6edca770467a61b3a5750a36b7c7731e">llvm::MIToken::kw_debug_use</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6addae3c49cf7e04a1535a29021ae91423">llvm::MIToken::kw_def</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa622b3d50d254c6f16b5f0dc2693f9ac">llvm::MIToken::kw_dereferenceable</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a89d38b3de95683fdb108fd90739bc2d6">llvm::MIToken::kw_disjoint</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2c5805b066544ecd04f444556adedb6c">llvm::MIToken::kw_distinct</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7ae1acf31fbbb0badf28636cabfb713d">llvm::MIToken::kw_double</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4cb41f854136268b98f0a3b6f8b7d0b9">llvm::MIToken::kw_early_clobber</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a94a48b5a62dbb5e2a2842729175252c2">llvm::MIToken::kw_ehfunclet_entry</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2e51bdf9f9a4d99c231cb04936d662ee">llvm::MIToken::kw_exact</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a00d4edc540b86353fb2bbb5873454baa">llvm::MIToken::kw_float</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abcdb15858b72e3e47c8fef5fc016f9e6">llvm::MIToken::kw_floatpred</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae03198c8736faa98f11254fde262dfa5">llvm::MIToken::kw_fp128</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7b38cb8a87ef0744995be2e4f5c86889">llvm::MIToken::kw_frame_destroy</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2da019279f6be2a1e52e64b02217e585">llvm::MIToken::kw_frame_setup</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ace222a16b52ad3ea7a399d31fd100d21">llvm::MIToken::kw_got</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a0b7a365eb84a10bcbe39e8a2603d1199">llvm::MIToken::kw_half</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6afe193166e332234f73dabc8d161a364e">llvm::MIToken::kw_heap_alloc_marker</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab206051858a3a8aec9100cc51e5cfcb5">llvm::MIToken::kw_implicit</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa6a826947733d28faf3db46eb2924cbd">llvm::MIToken::kw_implicit_define</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8fe59ab747442928d520456cead79f7c">llvm::MIToken::kw_inlineasm_br_indirect_target</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae7fa8038ec793e64852ab7942c2bf5f0">llvm::MIToken::kw_internal</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8e3daba81bd1d6ca3888c15382de1861">llvm::MIToken::kw_intpred</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2034e311c1521d501ce4310e1a1ff6c5">llvm::MIToken::kw_intrinsic</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa82f97904d6c89ebe2d24b97cc8c9b3f">llvm::MIToken::kw_invariant</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af0d89f9b8ae87326fdcc19e5b8b17450">llvm::MIToken::kw_ir_block_address_taken</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a5c9a5d789f0256a1c4af7a366c8a83a8">llvm::MIToken::kw_jump_table</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae6c29e07f6ec069203986ffe91d9bb63">llvm::MIToken::kw_killed</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a061c7ab03098b9fa400aeaf9b0e668f7">llvm::MIToken::kw_landing_pad</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a5956125b492bac740985726d73b707c3">llvm::MIToken::kw_liveins</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aac74710d2bd4bbd53711b6ab4bfd2f28">llvm::MIToken::kw_liveout</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab98be0dc02a2cf82b6c6e1a7e0e8f15f">llvm::MIToken::kw_machine_block_address_taken</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4895873b179e53092adfcb78ecaf4c4e">llvm::MIToken::kw_ninf</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a5dab1bbaccfcc0f825c02c6bc07b718b">llvm::MIToken::kw_nnan</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a3d5a4f076e9d02c6a8442e8dac212739">llvm::MIToken::kw_nneg</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6afc85d5b4d96997c181119e628f8727ae">llvm::MIToken::kw_noconvergent</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af051439152848664affc6acb1cee98c9">llvm::MIToken::kw_nofpexcept</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8d5d15b10a5a1d9cf253d722eb2a6089">llvm::MIToken::kw_non_temporal</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa43cbf2f0fd916c8e375be900f2634a0">llvm::MIToken::kw_nsw</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a813ceb01fe154d09fe9001a3ec15da3b">llvm::MIToken::kw_nsz</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a57eb6203065d03300e8be639a2abc363">llvm::MIToken::kw_nusw</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2b004204e9f6bd48039ec378d4026fa8">llvm::MIToken::kw_nuw</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae79b65c3955b6b96bd3e16a9691b0718">llvm::MIToken::kw_pcsections</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aea446ae4c2ab038ada07483d17fa8fd3">llvm::MIToken::kw_post_instr_symbol</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a891e978963b68a2dbc9d02c116407fa0">llvm::MIToken::kw_ppc_fp128</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a16baa8a695f87a8d642a0271f9c8bb4b">llvm::MIToken::kw_pre_instr_symbol</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac4bf254327260d60f099867840655305">llvm::MIToken::kw_reassoc</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abd8994d7aa807f0fc7a79bc0bd49ae51">llvm::MIToken::kw_renamable</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac912d10c1757f7123cb0967e5d7231a8">llvm::MIToken::kw_samesign</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af964d58ac7722e837d761dbff9598883">llvm::MIToken::kw_shufflemask</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1005b6baed24c36e03431f6b02a184b0">llvm::MIToken::kw_stack</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac906e38f5901242459dd9fc47e3696f8">llvm::MIToken::kw_successors</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a030a2c5533093a46e7531c32906e5f3b">llvm::MIToken::kw_target_flags</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa260bb514add2a91dc5689d2e3d0097b">llvm::MIToken::kw_target_index</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a61a7c9d358791d8e1d5fea11c59d8b81">llvm::MIToken::kw_tied_def</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af21fe671190c392445d0b4f6809403da">llvm::MIToken::kw_undef</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af13ae889d1ef5322dcc99aa328e20f6f">llvm::MIToken::kw_unknown_address</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abe977bfd868e054053a14b23da6252d7">llvm::MIToken::kw_unknown_size</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a65b31b4ccf793c70d51b6d5c1527af40">llvm::MIToken::kw_unpredictable</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1ede3539864c36bc93493e09f7b0fdec">llvm::MIToken::kw_volatile</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a217dd3c7155a23f5fd9f0592c0d19d4a">llvm::MIToken::kw_x86_fp80</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1fcbf573b686db8220b374ddfce6bbdc">llvm::MIToken::underscore</a>.</p>


<p>Referenced by <a href="#a9e7e252de6ff5a1af41bfb17e92c7764">maybeLexIdentifier</a>.</p>

</div>
</div>

### getMetadataKeywordKind() {#a9d70692332178cbc52cf13297525771c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIToken::TokenKind getMetadataKeywordKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Identifier)</td>
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



<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a695bb4e1c6c5b89177aeb0f0cf489580">llvm::MIToken::Error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a16fa35720e09effc00ef5f5ad17a53dc">llvm::MIToken::md_alias_scope</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a44e938a244ddbf730937be8d17272feb">llvm::MIToken::md_diexpr</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abc4fb36ac618caf2a11cb6c74f598d07">llvm::MIToken::md_dilocation</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aaede05e6d1ec29188d1d6e0741a9e60f">llvm::MIToken::md_noalias</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab66c1639a1e0b1b014352f33e42c0fbc">llvm::MIToken::md_range</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aeca7cae50fb8dd8c7776861ce14cc24d">llvm::MIToken::md_tbaa</a>.</p>


<p>Referenced by <a href="#a7167f37d6c009e5ab809b1e4a8a7c81f">maybeLexExclaim</a>.</p>

</div>
</div>

### isIdentifierChar() {#ab86f566b5a4fa3f73f3873d5caa9e6a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isIdentifierChar (char C)</td>
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

<p>Return true if the given character satisfies the following regular expression: [-a-zA-Z$._0-9].</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a0f93166a59bc27eac4a92002eb285ed3">isRegisterChar</a>, <a href="#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a>, <a href="#a7167f37d6c009e5ab809b1e4a8a7c81f">maybeLexExclaim</a>, <a href="#a9e7e252de6ff5a1af41bfb17e92c7764">maybeLexIdentifier</a>, <a href="#a81dc0e46445de327a0956a30e6fc0662">maybeLexIndexAndName</a>, <a href="#ae8a1ef6fb7c2e91c66607669addcbec9">maybeLexMachineBasicBlock</a> and <a href="#a95bd4c442d09906ba3a98a436150d637">maybeLexMCSymbol</a>.</p>

</div>
</div>

### isNewlineChar() {#a1f27f361ff2fcd0a9d10701dbe22951c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNewlineChar (char C)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a1bc5a949b7276f9015ad9db64478cd46">lexStringConstant</a>, <a href="#a01f74b24df78737ec2f22b65d2f37c91">maybeLexEscapedIRValue</a>, <a href="#a8f361b0c5074bb978be4e17286449842">maybeLexNewline</a> and <a href="#a08c5042e84885ca59fa0cb59e307f01e">skipComment</a>.</p>

</div>
</div>

### isRegisterChar() {#a0f93166a59bc27eac4a92002eb285ed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRegisterChar (char C)</td>
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

<p>Returns true for a character allowed in a register name.</p>

<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ab86f566b5a4fa3f73f3873d5caa9e6a5">isIdentifierChar</a>.</p>


<p>Referenced by <a href="#a751d4b410566e7af9878b48ecb803a62">lexNamedVirtualRegister</a> and <a href="#a67fb11afc51aa3e8a17d67db0457cdf2">maybeLexRegister</a>.</p>

</div>
</div>

### isValidHexFloatingPointPrefix() {#a2ccc48fb47ca955cf7e57dc05fa34041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isValidHexFloatingPointPrefix (char C)</td>
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



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a681d6dc497d72f781f0d6e37ef92adf6">maybeLexHexadecimalLiteral</a>.</p>

</div>
</div>

### lexFloatingPointLiteral() {#af424d285ff5841f2b72740200a19fc52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor lexFloatingPointLiteral (Cursor Range, Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token)</td>
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



<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a6eb3a607d6c59086dc0bdfd74a10e6a4">llvm::MIToken::FloatingPointLiteral</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a>.</p>


<p>Referenced by <a href="#a6f2a6cc3ecc29db91025a59a8b2719b1">maybeLexNumericalLiteral</a>.</p>

</div>
</div>

### lexName() {#ac158810c8b2357fd343d90fb8d82f5a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor lexName (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6">MIToken::TokenKind</a> Type, unsigned PrefixLength, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a695bb4e1c6c5b89177aeb0f0cf489580">llvm::MIToken::Error</a>, <a href="#ab86f566b5a4fa3f73f3873d5caa9e6a5">isIdentifierChar</a>, <a href="#a1bc5a949b7276f9015ad9db64478cd46">lexStringConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ae1c883d2616acba40d12a921840a3a0a">llvm::MIToken::setOwnedStringValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a0a6c1c13ddbd40786b667a40ac3b48de">llvm::MIToken::setStringValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a> and <a href="#a7e63172c1d60457b773a5d356251ce45">unescapeQuotedString</a>.</p>


<p>Referenced by <a href="#aaaec7640dacf4b818d7a546977ba6463">maybeLexExternalSymbol</a>, <a href="#ad03860fe4db1cfdfe373bf181829fb88">maybeLexGlobalValue</a>, <a href="#a34f0a3b30959de2e7847c340c2b0fea2">maybeLexIRBlock</a>, <a href="#ad97f43f2c733ae0b0506f078fb2768e0">maybeLexIRValue</a>, <a href="#ae9cdd4ae7b2eddf8dcee53587086d900">maybeLexStringConstant</a> and <a href="#aeb41fb2d4d98f026a60d1504d92b5a8c">maybeLexSubRegisterIndex</a>.</p>

</div>
</div>

### lexNamedVirtualRegister() {#a751d4b410566e7af9878b48ecb803a62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor lexNamedVirtualRegister (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token)</td>
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



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a0f93166a59bc27eac4a92002eb285ed3">isRegisterChar</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4bb75c93c34ebe814b2500733ed2cbe2">llvm::MIToken::NamedVirtualRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a0a6c1c13ddbd40786b667a40ac3b48de">llvm::MIToken::setStringValue</a>.</p>


<p>Referenced by <a href="#a67fb11afc51aa3e8a17d67db0457cdf2">maybeLexRegister</a>.</p>

</div>
</div>

### lexStringConstant() {#a1bc5a949b7276f9015ad9db64478cd46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor lexStringConstant (Cursor C, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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

<p>Lex a string constant using the following regular expression: "[^"]*".</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a1f27f361ff2fcd0a9d10701dbe22951c">isNewlineChar</a>.</p>


<p>Referenced by <a href="#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a> and <a href="#a95bd4c442d09906ba3a98a436150d637">maybeLexMCSymbol</a>.</p>

</div>
</div>

### lexVirtualRegister() {#a68ca6d53c1a7e468c10ff026e307957a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor lexVirtualRegister (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token)</td>
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



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#aafe77831f41912b2cd227484d30ae81d">llvm::MIToken::setIntegerValue</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aad89006e07a1b4b432094251dafeb05e">llvm::MIToken::VirtualRegister</a>.</p>


<p>Referenced by <a href="#a67fb11afc51aa3e8a17d67db0457cdf2">maybeLexRegister</a>.</p>

</div>
</div>

### maybeLexConstantPoolItem() {#af9fb2421a934ca6abf18452c4cb72706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexConstantPoolItem (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token)</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a33dab87da238f19cc21814c491b2d6af">llvm::MIToken::ConstantPoolItem</a> and <a href="#afcc4cdfb302bc22d1b9cdca6a419f7b7">maybeLexIndex</a>.</p>

</div>
</div>

### maybeLexEscapedIRValue() {#a01f74b24df78737ec2f22b65d2f37c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexEscapedIRValue (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a695bb4e1c6c5b89177aeb0f0cf489580">llvm::MIToken::Error</a>, <a href="#a1f27f361ff2fcd0a9d10701dbe22951c">isNewlineChar</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae8d68bd011115d762d74f4fa23c3d46e">llvm::MIToken::QuotedIRValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a0a6c1c13ddbd40786b667a40ac3b48de">llvm::MIToken::setStringValue</a>.</p>

</div>
</div>

### maybeLexExclaim() {#a7167f37d6c009e5ab809b1e4a8a7c81f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexExclaim (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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



<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae9b7e1e40ac9f787f763b636479f00d6">llvm::MIToken::exclaim</a>, <a href="#a9d70692332178cbc52cf13297525771c">getMetadataKeywordKind</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac2deed85c7c9addd45a26ff489684677">llvm::MIToken::isError</a>, <a href="#ab86f566b5a4fa3f73f3873d5caa9e6a5">isIdentifierChar</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ae748f46851917c5a8bbd2b6cd9e6c7b4">llvm::MIToken::location</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a>.</p>

</div>
</div>

### maybeLexExternalSymbol() {#aaaec7640dacf4b818d7a546977ba6463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexExternalSymbol (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abde8ba21041eb8328acc02146a3a0d77">llvm::MIToken::ExternalSymbol</a> and <a href="#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a>.</p>

</div>
</div>

### maybeLexFixedStackObject() {#adc94ab461ed98cc2b12045e09cce6d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexFixedStackObject (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token)</td>
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



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9d8e09e328411c8dbdbd11f38bf1ff5b">llvm::MIToken::FixedStackObject</a> and <a href="#afcc4cdfb302bc22d1b9cdca6a419f7b7">maybeLexIndex</a>.</p>

</div>
</div>

### maybeLexGlobalValue() {#ad03860fe4db1cfdfe373bf181829fb88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexGlobalValue (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a850ebe3ac4c626d9ea0cb6f26e7c904e">llvm::MIToken::GlobalValue</a>, <a href="#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a26360791c68fa9d21c6ea07375867965">llvm::MIToken::NamedGlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#aafe77831f41912b2cd227484d30ae81d">llvm::MIToken::setIntegerValue</a>.</p>

</div>
</div>

### maybeLexHexadecimalLiteral() {#a681d6dc497d72f781f0d6e37ef92adf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexHexadecimalLiteral (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token)</td>
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



<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a6eb3a607d6c59086dc0bdfd74a10e6a4">llvm::MIToken::FloatingPointLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab7084e2fd8ea5e2682facafa33c2abc6">llvm::MIToken::HexLiteral</a>, <a href="#a2ccc48fb47ca955cf7e57dc05fa34041">isValidHexFloatingPointPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a>.</p>

</div>
</div>

### maybeLexIdentifier() {#a9e7e252de6ff5a1af41bfb17e92c7764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexIdentifier (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token)</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a343545c6308183cfae523bf627eb4373">getIdentifierKind</a>, <a href="#ab86f566b5a4fa3f73f3873d5caa9e6a5">isIdentifierChar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a0a6c1c13ddbd40786b667a40ac3b48de">llvm::MIToken::setStringValue</a>.</p>

</div>
</div>

### maybeLexIndex() {#afcc4cdfb302bc22d1b9cdca6a419f7b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexIndex (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Rule, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6">MIToken::TokenKind</a> Kind)</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#aafe77831f41912b2cd227484d30ae81d">llvm::MIToken::setIntegerValue</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#af9fb2421a934ca6abf18452c4cb72706">maybeLexConstantPoolItem</a>, <a href="#adc94ab461ed98cc2b12045e09cce6d67">maybeLexFixedStackObject</a>, <a href="#a34f0a3b30959de2e7847c340c2b0fea2">maybeLexIRBlock</a>, <a href="#ad97f43f2c733ae0b0506f078fb2768e0">maybeLexIRValue</a> and <a href="#a564a55d742dc949dd886dd9da92c0bbf">maybeLexJumpTableIndex</a>.</p>

</div>
</div>

### maybeLexIndexAndName() {#a81dc0e46445de327a0956a30e6fc0662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexIndexAndName (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Rule, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6">MIToken::TokenKind</a> Kind)</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ab86f566b5a4fa3f73f3873d5caa9e6a5">isIdentifierChar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfab2ee912b91d69b435159c7c3f6df7f5f">llvm::Number</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#aafe77831f41912b2cd227484d30ae81d">llvm::MIToken::setIntegerValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a0a6c1c13ddbd40786b667a40ac3b48de">llvm::MIToken::setStringValue</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#aa38483113957b327d241b4e71cdf3673">maybeLexStackObject</a>.</p>

</div>
</div>

### maybeLexIRBlock() {#a34f0a3b30959de2e7847c340c2b0fea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexIRBlock (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab80383451bf22665b8b1e7deec8dba7e">llvm::MIToken::IRBlock</a>, <a href="#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a>, <a href="#afcc4cdfb302bc22d1b9cdca6a419f7b7">maybeLexIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8b71950fb9a704439e1752de75ef57af">llvm::MIToken::NamedIRBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### maybeLexIRValue() {#ad97f43f2c733ae0b0506f078fb2768e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexIRValue (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a56f6273627f38aacd8af4fe49a4dbab8">llvm::MIToken::IRValue</a>, <a href="#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a>, <a href="#afcc4cdfb302bc22d1b9cdca6a419f7b7">maybeLexIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a95e22b395cd577a493f41e1bc9f66857">llvm::MIToken::NamedIRValue</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### maybeLexJumpTableIndex() {#a564a55d742dc949dd886dd9da92c0bbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexJumpTableIndex (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token)</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af1ed79b968bc264cdbc86258d8566f0c">llvm::MIToken::JumpTableIndex</a> and <a href="#afcc4cdfb302bc22d1b9cdca6a419f7b7">maybeLexIndex</a>.</p>

</div>
</div>

### maybeLexMachineBasicBlock() {#ae8a1ef6fb7c2e91c66607669addcbec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexMachineBasicBlock (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a695bb4e1c6c5b89177aeb0f0cf489580">llvm::MIToken::Error</a>, <a href="#ab86f566b5a4fa3f73f3873d5caa9e6a5">isIdentifierChar</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a3f519613749a65e91b6dfe908aaf554e">llvm::MIToken::MachineBasicBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7e5c1b1fdcdabc0c2d3ed5941308db6c">llvm::MIToken::MachineBasicBlockLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfab2ee912b91d69b435159c7c3f6df7f5f">llvm::Number</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#aafe77831f41912b2cd227484d30ae81d">llvm::MIToken::setIntegerValue</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a0a6c1c13ddbd40786b667a40ac3b48de">llvm::MIToken::setStringValue</a>.</p>

</div>
</div>

### maybeLexMCSymbol() {#a95bd4c442d09906ba3a98a436150d637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexMCSymbol (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a695bb4e1c6c5b89177aeb0f0cf489580">llvm::MIToken::Error</a>, <a href="#ab86f566b5a4fa3f73f3873d5caa9e6a5">isIdentifierChar</a>, <a href="#a1bc5a949b7276f9015ad9db64478cd46">lexStringConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ad3d487e3a5ce2baa29da23330ebbedc5">llvm::MIToken::MCSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ae1c883d2616acba40d12a921840a3a0a">llvm::MIToken::setOwnedStringValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a0a6c1c13ddbd40786b667a40ac3b48de">llvm::MIToken::setStringValue</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a> and <a href="#a7e63172c1d60457b773a5d356251ce45">unescapeQuotedString</a>.</p>

</div>
</div>

### maybeLexNewline() {#a8f361b0c5074bb978be4e17286449842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexNewline (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token)</td>
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



<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a1f27f361ff2fcd0a9d10701dbe22951c">isNewlineChar</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a38401c9f9d25b14c3ca4a36214b5f290">llvm::MIToken::Newline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a>.</p>

</div>
</div>

### maybeLexNumericalLiteral() {#a6f2a6cc3ecc29db91025a59a8b2719b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexNumericalLiteral (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token)</td>
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



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="#af424d285ff5841f2b72740200a19fc52">lexFloatingPointLiteral</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#aafe77831f41912b2cd227484d30ae81d">llvm::MIToken::setIntegerValue</a>.</p>

</div>
</div>

### maybeLexRegister() {#a67fb11afc51aa3e8a17d67db0457cdf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexRegister (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a0f93166a59bc27eac4a92002eb285ed3">isRegisterChar</a>, <a href="#a751d4b410566e7af9878b48ecb803a62">lexNamedVirtualRegister</a>, <a href="#a68ca6d53c1a7e468c10ff026e307957a">lexVirtualRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ada1e13f84d573245c05460a99ef47607">llvm::MIToken::NamedRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a0a6c1c13ddbd40786b667a40ac3b48de">llvm::MIToken::setStringValue</a>.</p>

</div>
</div>

### maybeLexStackObject() {#aa38483113957b327d241b4e71cdf3673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexStackObject (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token)</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a81dc0e46445de327a0956a30e6fc0662">maybeLexIndexAndName</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a02ea7320381cc7361f5f3530892eb3e1">llvm::MIToken::StackObject</a>.</p>

</div>
</div>

### maybeLexStringConstant() {#ae9cdd4ae7b2eddf8dcee53587086d900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexStringConstant (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7dcd0f9b261114fe964552407f110a04">llvm::MIToken::StringConstant</a>.</p>

</div>
</div>

### maybeLexSubRegisterIndex() {#aeb41fb2d4d98f026a60d1504d92b5a8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexSubRegisterIndex (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#aa75d630697803d6c8a29d588e83bb29f">ErrorCallbackType</a> ErrorCallback)</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2d9fa763e09f66fdd3f9f6a94c1b58e2">llvm::MIToken::SubRegisterIndex</a>.</p>

</div>
</div>

### maybeLexSymbol() {#a4820a34a5c7d00417a38c0cf2321f9f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor maybeLexSymbol (Cursor C, <a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp; Token)</td>
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



<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a73e49b39421c784a08abf178343da0bc">llvm::MIToken::coloncolon</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a695bb4e1c6c5b89177aeb0f0cf489580">llvm::MIToken::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#ac1edd22e2655350cb4c4fcbb196675ee">llvm::MIToken::reset</a> and <a href="#a2b858f5e91ffcd108c71029f7171a8ff">symbolToken</a>.</p>

</div>
</div>

### skipComment() {#a08c5042e84885ca59fa0cb59e307f01e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor skipComment (Cursor C)</td>
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

<p>Skip a line comment and return the updated cursor.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a1f27f361ff2fcd0a9d10701dbe22951c">isNewlineChar</a>.</p>

</div>
</div>

### skipMachineOperandComment() {#a97f0d7559c1e0147978f08ea9ac463b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor skipMachineOperandComment (Cursor C)</td>
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

<p>Machine operands can have comments, enclosed between /* and <em>‍/. </em></p>


<p>This eats up all tokens, including / and *‍/.</p>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### skipWhitespace() {#aa3fdb5af86c8d216e09424fdcd3bf9cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor skipWhitespace (Cursor C)</td>
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

<p>Skip the leading whitespace characters and return the updated cursor.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### symbolToken() {#a2b858f5e91ffcd108c71029f7171a8ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIToken::TokenKind symbolToken (char C)</td>
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



<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac56884d19c1537e43044a3078cac0004">llvm::MIToken::colon</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a73902454a32cbf1ad7ceac917df4bbd4">llvm::MIToken::dot</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab3c838fbfa1a8d60a66b3fe4aa360af9">llvm::MIToken::equal</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a695bb4e1c6c5b89177aeb0f0cf489580">llvm::MIToken::Error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4706e21cf646fba2fb2044291a31ddd4">llvm::MIToken::greater</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7ec17f6a52a8e82ff01425357cd53bb6">llvm::MIToken::lbrace</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4e7dadb5d20a08f47b6c4b6f6c28451a">llvm::MIToken::less</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a95a262807a0e29e6c8da9c780b5cd489">llvm::MIToken::minus</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a80a791797a5aa271f17b100dc2915658">llvm::MIToken::plus</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1b4d75865bc6f7723d3f2cae13c8b651">llvm::MIToken::rbrace</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>.</p>


<p>Referenced by <a href="#a4820a34a5c7d00417a38c0cf2321f9f3">maybeLexSymbol</a>.</p>

</div>
</div>

### unescapeQuotedString() {#a7e63172c1d60457b773a5d356251ce45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string unescapeQuotedString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
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

<p>Unescapes the given string value.</p>


<p>Expects the string value to be quoted.</p>


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a> and <a href="#a95bd4c442d09906ba3a98a436150d637">maybeLexMCSymbol</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
