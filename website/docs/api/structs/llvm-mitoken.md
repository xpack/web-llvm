---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mitoken
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MIToken` Struct Reference

<p>A token produced by the machine instruction lexer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MIToken { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">CodeGen/MIRParser/MILexer.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TokenKind { <a href="#a826fc5728ce5ed55eef1807bf32e02a6">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd2f79ac3bdafaa1f8e9b87f58e7f36">MIToken</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1edd22e2655350cb4c4fcbb196675ee">reset</a> (TokenKind Kind, StringRef Range)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a6c1c13ddbd40786b667a40ac3b48de">setStringValue</a> (StringRef StrVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1c883d2616acba40d12a921840a3a0a">setOwnedStringValue</a> (std::string StrVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafe77831f41912b2cd227484d30ae81d">setIntegerValue</a> (APSInt IntVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a826fc5728ce5ed55eef1807bf32e02a6">TokenKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dca48803924924232858ce24ee03c9a">kind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2deed85c7c9addd45a26ff489684677">isError</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4107bf4a0e5f0f679bce7c091947a447">isNewlineOrEOF</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb561c9239fe4dfe771fa55dd88446f1">isErrorOrEOF</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa500122720f4bd103478353e6a6fc114">isRegister</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0627b5671af49734d35148f15c18f51a">isRegisterFlag</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756421c5cd5513bf888855e29269756a">isMemoryOperandFlag</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6390be713bc6ca27dfadffc3ca549542">is</a> (TokenKind K) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d3f762500f257cd21c7ab6703e7669d">isNot</a> (TokenKind K) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae748f46851917c5a8bbd2b6cd9e6c7b4">location</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82fdc67c3d7bd8c6fb7278d4fc0accda">range</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c73a2b1eeb149f6d2b8ef7568fbb045">stringValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the token's string value. <a href="#a7c73a2b1eeb149f6d2b8ef7568fbb045">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa2a600dde7f9ae95c2255973ad25286">integerValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d787045053ab1b2de9daae0f5ed5c0">hasIntegerValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a826fc5728ce5ed55eef1807bf32e02a6">TokenKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af09936b6a34e7fd588e1dd58dd95c89b">Kind</a> = <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a428ef0c0c385d56f1c4cce5d568027b9">Range</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f99fbc993507137aab559913de6b94e">StringValue</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1ba0f6a2c20b890414f776fcbd1d5b6">StringValueStorage</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3be929b866d6c9b8f54caa60505f39a">IntVal</a></td>
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

<p>A token produced by the machine instruction lexer.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### TokenKind {#a826fc5728ce5ed55eef1807bf32e02a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MIToken::TokenKind </td>
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
<td class="doxyEnumItemName">Eof<a id="a826fc5728ce5ed55eef1807bf32e02a6a9451d22efb0e7385c6b73ca7799b1d70"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Error<a id="a826fc5728ce5ed55eef1807bf32e02a6a695bb4e1c6c5b89177aeb0f0cf489580"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Newline<a id="a826fc5728ce5ed55eef1807bf32e02a6a38401c9f9d25b14c3ca4a36214b5f290"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">comma<a id="a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">equal<a id="a826fc5728ce5ed55eef1807bf32e02a6ab3c838fbfa1a8d60a66b3fe4aa360af9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">underscore<a id="a826fc5728ce5ed55eef1807bf32e02a6a1fcbf573b686db8220b374ddfce6bbdc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">colon<a id="a826fc5728ce5ed55eef1807bf32e02a6ac56884d19c1537e43044a3078cac0004"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">coloncolon<a id="a826fc5728ce5ed55eef1807bf32e02a6a73e49b39421c784a08abf178343da0bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">dot<a id="a826fc5728ce5ed55eef1807bf32e02a6a73902454a32cbf1ad7ceac917df4bbd4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">exclaim<a id="a826fc5728ce5ed55eef1807bf32e02a6ae9b7e1e40ac9f787f763b636479f00d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">lparen<a id="a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">rparen<a id="a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">lbrace<a id="a826fc5728ce5ed55eef1807bf32e02a6a7ec17f6a52a8e82ff01425357cd53bb6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">rbrace<a id="a826fc5728ce5ed55eef1807bf32e02a6a1b4d75865bc6f7723d3f2cae13c8b651"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">plus<a id="a826fc5728ce5ed55eef1807bf32e02a6a80a791797a5aa271f17b100dc2915658"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">minus<a id="a826fc5728ce5ed55eef1807bf32e02a6a95a262807a0e29e6c8da9c780b5cd489"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">less<a id="a826fc5728ce5ed55eef1807bf32e02a6a4e7dadb5d20a08f47b6c4b6f6c28451a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">greater<a id="a826fc5728ce5ed55eef1807bf32e02a6a4706e21cf646fba2fb2044291a31ddd4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_implicit<a id="a826fc5728ce5ed55eef1807bf32e02a6ab206051858a3a8aec9100cc51e5cfcb5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_implicit_define<a id="a826fc5728ce5ed55eef1807bf32e02a6aa6a826947733d28faf3db46eb2924cbd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_def<a id="a826fc5728ce5ed55eef1807bf32e02a6addae3c49cf7e04a1535a29021ae91423"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_dead<a id="a826fc5728ce5ed55eef1807bf32e02a6a3c27c3f12ff5eac92e28e03d48af0a58"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_dereferenceable<a id="a826fc5728ce5ed55eef1807bf32e02a6aa622b3d50d254c6f16b5f0dc2693f9ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_killed<a id="a826fc5728ce5ed55eef1807bf32e02a6ae6c29e07f6ec069203986ffe91d9bb63"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_undef<a id="a826fc5728ce5ed55eef1807bf32e02a6af21fe671190c392445d0b4f6809403da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_internal<a id="a826fc5728ce5ed55eef1807bf32e02a6ae7fa8038ec793e64852ab7942c2bf5f0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_early_clobber<a id="a826fc5728ce5ed55eef1807bf32e02a6a4cb41f854136268b98f0a3b6f8b7d0b9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_debug_use<a id="a826fc5728ce5ed55eef1807bf32e02a6a6edca770467a61b3a5750a36b7c7731e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_renamable<a id="a826fc5728ce5ed55eef1807bf32e02a6abd8994d7aa807f0fc7a79bc0bd49ae51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_tied_def<a id="a826fc5728ce5ed55eef1807bf32e02a6a61a7c9d358791d8e1d5fea11c59d8b81"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_frame_setup<a id="a826fc5728ce5ed55eef1807bf32e02a6a2da019279f6be2a1e52e64b02217e585"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_frame_destroy<a id="a826fc5728ce5ed55eef1807bf32e02a6a7b38cb8a87ef0744995be2e4f5c86889"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_nnan<a id="a826fc5728ce5ed55eef1807bf32e02a6a5dab1bbaccfcc0f825c02c6bc07b718b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_ninf<a id="a826fc5728ce5ed55eef1807bf32e02a6a4895873b179e53092adfcb78ecaf4c4e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_nsz<a id="a826fc5728ce5ed55eef1807bf32e02a6a813ceb01fe154d09fe9001a3ec15da3b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_arcp<a id="a826fc5728ce5ed55eef1807bf32e02a6a645f437737bb0546525fb281fcc101fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_contract<a id="a826fc5728ce5ed55eef1807bf32e02a6a1629a3eb67efd22303ce5458746b3cab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_afn<a id="a826fc5728ce5ed55eef1807bf32e02a6a356311228b5226914a5e28765271885b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_reassoc<a id="a826fc5728ce5ed55eef1807bf32e02a6ac4bf254327260d60f099867840655305"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_nusw<a id="a826fc5728ce5ed55eef1807bf32e02a6a57eb6203065d03300e8be639a2abc363"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_nuw<a id="a826fc5728ce5ed55eef1807bf32e02a6a2b004204e9f6bd48039ec378d4026fa8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_nsw<a id="a826fc5728ce5ed55eef1807bf32e02a6aa43cbf2f0fd916c8e375be900f2634a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_exact<a id="a826fc5728ce5ed55eef1807bf32e02a6a2e51bdf9f9a4d99c231cb04936d662ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_nofpexcept<a id="a826fc5728ce5ed55eef1807bf32e02a6af051439152848664affc6acb1cee98c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_unpredictable<a id="a826fc5728ce5ed55eef1807bf32e02a6a65b31b4ccf793c70d51b6d5c1527af40"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_nneg<a id="a826fc5728ce5ed55eef1807bf32e02a6a3d5a4f076e9d02c6a8442e8dac212739"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_disjoint<a id="a826fc5728ce5ed55eef1807bf32e02a6a89d38b3de95683fdb108fd90739bc2d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_samesign<a id="a826fc5728ce5ed55eef1807bf32e02a6ac912d10c1757f7123cb0967e5d7231a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_debug_location<a id="a826fc5728ce5ed55eef1807bf32e02a6afae5d39056b30c2d5219236ee0650abc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_debug_instr_number<a id="a826fc5728ce5ed55eef1807bf32e02a6ae3b209d9029d0e9a79026e60f8328f23"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_dbg_instr_ref<a id="a826fc5728ce5ed55eef1807bf32e02a6a44c287f7c3c0e3293241bde17a716828"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_same_value<a id="a826fc5728ce5ed55eef1807bf32e02a6a9d9cd9b85ae5fce2a539f56fb037766a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_offset<a id="a826fc5728ce5ed55eef1807bf32e02a6a4cefddc97b52262ec3ca131128079be4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_rel_offset<a id="a826fc5728ce5ed55eef1807bf32e02a6a94740fe117708e6e5de35dea49614ad0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_def_cfa_register<a id="a826fc5728ce5ed55eef1807bf32e02a6a9b449f07ddab22c2e49164fc2aee112c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_def_cfa_offset<a id="a826fc5728ce5ed55eef1807bf32e02a6aaec8c69ba4f771177000277c8e2403b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_adjust_cfa_offset<a id="a826fc5728ce5ed55eef1807bf32e02a6aa4c84979e85e8fa30a9d33d7ebe59ca5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_escape<a id="a826fc5728ce5ed55eef1807bf32e02a6aa99f8585275a495b73a9319979194b5a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_def_cfa<a id="a826fc5728ce5ed55eef1807bf32e02a6aa94c3b98223057a43e6d39505f4a6e5f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_llvm_def_aspace_cfa<a id="a826fc5728ce5ed55eef1807bf32e02a6a3cc78b122a3960aed2a370a5241e6015"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_register<a id="a826fc5728ce5ed55eef1807bf32e02a6a8f3b8e825a1b96c0feb33b74c56eb891"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_remember_state<a id="a826fc5728ce5ed55eef1807bf32e02a6ae264c83e0df5209a1dfcd322b0d0e74a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_restore<a id="a826fc5728ce5ed55eef1807bf32e02a6a836ad743b6d5b6e1d0bd80e05f42812c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_restore_state<a id="a826fc5728ce5ed55eef1807bf32e02a6aee2c9ff26df9a29da2a3b5409cfde779"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_undefined<a id="a826fc5728ce5ed55eef1807bf32e02a6a7bb4c83768ee2a94a0a21aa1a0815752"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_window_save<a id="a826fc5728ce5ed55eef1807bf32e02a6a712ca0bbf0925efcb0f451e6a53357ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_aarch64_negate_ra_sign_state<a id="a826fc5728ce5ed55eef1807bf32e02a6a312a88bc3c813a44c29c661d9e981769"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_aarch64_negate_ra_sign_state_with_pc<a id="a826fc5728ce5ed55eef1807bf32e02a6a9741536facc1c8c790ac0929276d2bef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_blockaddress<a id="a826fc5728ce5ed55eef1807bf32e02a6a10b64d0278daea287b892ac95f4a70c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_intrinsic<a id="a826fc5728ce5ed55eef1807bf32e02a6a2034e311c1521d501ce4310e1a1ff6c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_target_index<a id="a826fc5728ce5ed55eef1807bf32e02a6aa260bb514add2a91dc5689d2e3d0097b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_half<a id="a826fc5728ce5ed55eef1807bf32e02a6a0b7a365eb84a10bcbe39e8a2603d1199"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_bfloat<a id="a826fc5728ce5ed55eef1807bf32e02a6a59ea063561870edcff0bdd8f0d95b1a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_float<a id="a826fc5728ce5ed55eef1807bf32e02a6a00d4edc540b86353fb2bbb5873454baa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_double<a id="a826fc5728ce5ed55eef1807bf32e02a6a7ae1acf31fbbb0badf28636cabfb713d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_x86_fp80<a id="a826fc5728ce5ed55eef1807bf32e02a6a217dd3c7155a23f5fd9f0592c0d19d4a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_fp128<a id="a826fc5728ce5ed55eef1807bf32e02a6ae03198c8736faa98f11254fde262dfa5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_ppc_fp128<a id="a826fc5728ce5ed55eef1807bf32e02a6a891e978963b68a2dbc9d02c116407fa0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_target_flags<a id="a826fc5728ce5ed55eef1807bf32e02a6a030a2c5533093a46e7531c32906e5f3b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_volatile<a id="a826fc5728ce5ed55eef1807bf32e02a6a1ede3539864c36bc93493e09f7b0fdec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_non_temporal<a id="a826fc5728ce5ed55eef1807bf32e02a6a8d5d15b10a5a1d9cf253d722eb2a6089"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_invariant<a id="a826fc5728ce5ed55eef1807bf32e02a6aa82f97904d6c89ebe2d24b97cc8c9b3f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_align<a id="a826fc5728ce5ed55eef1807bf32e02a6a2b36847798e6a577ff1a459d436716cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_basealign<a id="a826fc5728ce5ed55eef1807bf32e02a6a8fa817130e25e7d76dba39a1bd0962ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_addrspace<a id="a826fc5728ce5ed55eef1807bf32e02a6a0943c04acc16f5a20793de60d48cfc93"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_stack<a id="a826fc5728ce5ed55eef1807bf32e02a6a1005b6baed24c36e03431f6b02a184b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_got<a id="a826fc5728ce5ed55eef1807bf32e02a6ace222a16b52ad3ea7a399d31fd100d21"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_jump_table<a id="a826fc5728ce5ed55eef1807bf32e02a6a5c9a5d789f0256a1c4af7a366c8a83a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_constant_pool<a id="a826fc5728ce5ed55eef1807bf32e02a6a76138fb77b2f732e63b38f1e7065d383"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_call_entry<a id="a826fc5728ce5ed55eef1807bf32e02a6a706a66b904c74b059eb4094498c964fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_custom<a id="a826fc5728ce5ed55eef1807bf32e02a6ab93677f69d0041e06070c90910dcc30b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_liveout<a id="a826fc5728ce5ed55eef1807bf32e02a6aac74710d2bd4bbd53711b6ab4bfd2f28"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_landing_pad<a id="a826fc5728ce5ed55eef1807bf32e02a6a061c7ab03098b9fa400aeaf9b0e668f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_inlineasm_br_indirect_target<a id="a826fc5728ce5ed55eef1807bf32e02a6a8fe59ab747442928d520456cead79f7c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_ehfunclet_entry<a id="a826fc5728ce5ed55eef1807bf32e02a6a94a48b5a62dbb5e2a2842729175252c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_liveins<a id="a826fc5728ce5ed55eef1807bf32e02a6a5956125b492bac740985726d73b707c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_successors<a id="a826fc5728ce5ed55eef1807bf32e02a6ac906e38f5901242459dd9fc47e3696f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_floatpred<a id="a826fc5728ce5ed55eef1807bf32e02a6abcdb15858b72e3e47c8fef5fc016f9e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_intpred<a id="a826fc5728ce5ed55eef1807bf32e02a6a8e3daba81bd1d6ca3888c15382de1861"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_shufflemask<a id="a826fc5728ce5ed55eef1807bf32e02a6af964d58ac7722e837d761dbff9598883"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_pre_instr_symbol<a id="a826fc5728ce5ed55eef1807bf32e02a6a16baa8a695f87a8d642a0271f9c8bb4b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_post_instr_symbol<a id="a826fc5728ce5ed55eef1807bf32e02a6aea446ae4c2ab038ada07483d17fa8fd3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_heap_alloc_marker<a id="a826fc5728ce5ed55eef1807bf32e02a6afe193166e332234f73dabc8d161a364e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_pcsections<a id="a826fc5728ce5ed55eef1807bf32e02a6ae79b65c3955b6b96bd3e16a9691b0718"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_cfi_type<a id="a826fc5728ce5ed55eef1807bf32e02a6a8a6dea4150203fad21673ccf124a968b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_bbsections<a id="a826fc5728ce5ed55eef1807bf32e02a6aff7ad41fba511dad3cf8ed9165271232"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_bb_id<a id="a826fc5728ce5ed55eef1807bf32e02a6a36279270727e3d0a5a71ed49bc937df8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_unknown_size<a id="a826fc5728ce5ed55eef1807bf32e02a6abe977bfd868e054053a14b23da6252d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_unknown_address<a id="a826fc5728ce5ed55eef1807bf32e02a6af13ae889d1ef5322dcc99aa328e20f6f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_ir_block_address_taken<a id="a826fc5728ce5ed55eef1807bf32e02a6af0d89f9b8ae87326fdcc19e5b8b17450"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_machine_block_address_taken<a id="a826fc5728ce5ed55eef1807bf32e02a6ab98be0dc02a2cf82b6c6e1a7e0e8f15f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_call_frame_size<a id="a826fc5728ce5ed55eef1807bf32e02a6a294c5581d42ad37196ca937c31e8598e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_noconvergent<a id="a826fc5728ce5ed55eef1807bf32e02a6afc85d5b4d96997c181119e628f8727ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kw_distinct<a id="a826fc5728ce5ed55eef1807bf32e02a6a2c5805b066544ecd04f444556adedb6c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">md_tbaa<a id="a826fc5728ce5ed55eef1807bf32e02a6aeca7cae50fb8dd8c7776861ce14cc24d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">md_alias_scope<a id="a826fc5728ce5ed55eef1807bf32e02a6a16fa35720e09effc00ef5f5ad17a53dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">md_noalias<a id="a826fc5728ce5ed55eef1807bf32e02a6aaede05e6d1ec29188d1d6e0741a9e60f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">md_range<a id="a826fc5728ce5ed55eef1807bf32e02a6ab66c1639a1e0b1b014352f33e42c0fbc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">md_diexpr<a id="a826fc5728ce5ed55eef1807bf32e02a6a44e938a244ddbf730937be8d17272feb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">md_dilocation<a id="a826fc5728ce5ed55eef1807bf32e02a6abc4fb36ac618caf2a11cb6c74f598d07"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Identifier<a id="a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NamedRegister<a id="a826fc5728ce5ed55eef1807bf32e02a6ada1e13f84d573245c05460a99ef47607"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NamedVirtualRegister<a id="a826fc5728ce5ed55eef1807bf32e02a6a4bb75c93c34ebe814b2500733ed2cbe2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachineBasicBlockLabel<a id="a826fc5728ce5ed55eef1807bf32e02a6a7e5c1b1fdcdabc0c2d3ed5941308db6c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachineBasicBlock<a id="a826fc5728ce5ed55eef1807bf32e02a6a3f519613749a65e91b6dfe908aaf554e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StackObject<a id="a826fc5728ce5ed55eef1807bf32e02a6a02ea7320381cc7361f5f3530892eb3e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FixedStackObject<a id="a826fc5728ce5ed55eef1807bf32e02a6a9d8e09e328411c8dbdbd11f38bf1ff5b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NamedGlobalValue<a id="a826fc5728ce5ed55eef1807bf32e02a6a26360791c68fa9d21c6ea07375867965"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GlobalValue<a id="a826fc5728ce5ed55eef1807bf32e02a6a850ebe3ac4c626d9ea0cb6f26e7c904e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExternalSymbol<a id="a826fc5728ce5ed55eef1807bf32e02a6abde8ba21041eb8328acc02146a3a0d77"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCSymbol<a id="a826fc5728ce5ed55eef1807bf32e02a6ad3d487e3a5ce2baa29da23330ebbedc5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntegerLiteral<a id="a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FloatingPointLiteral<a id="a826fc5728ce5ed55eef1807bf32e02a6a6eb3a607d6c59086dc0bdfd74a10e6a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HexLiteral<a id="a826fc5728ce5ed55eef1807bf32e02a6ab7084e2fd8ea5e2682facafa33c2abc6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VectorLiteral<a id="a826fc5728ce5ed55eef1807bf32e02a6a50593567ca4d719101b61c0cfe107eba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VirtualRegister<a id="a826fc5728ce5ed55eef1807bf32e02a6aad89006e07a1b4b432094251dafeb05e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ConstantPoolItem<a id="a826fc5728ce5ed55eef1807bf32e02a6a33dab87da238f19cc21814c491b2d6af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">JumpTableIndex<a id="a826fc5728ce5ed55eef1807bf32e02a6af1ed79b968bc264cdbc86258d8566f0c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NamedIRBlock<a id="a826fc5728ce5ed55eef1807bf32e02a6a8b71950fb9a704439e1752de75ef57af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRBlock<a id="a826fc5728ce5ed55eef1807bf32e02a6ab80383451bf22665b8b1e7deec8dba7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NamedIRValue<a id="a826fc5728ce5ed55eef1807bf32e02a6a95e22b395cd577a493f41e1bc9f66857"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRValue<a id="a826fc5728ce5ed55eef1807bf32e02a6a56f6273627f38aacd8af4fe49a4dbab8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QuotedIRValue<a id="a826fc5728ce5ed55eef1807bf32e02a6ae8d68bd011115d762d74f4fa23c3d46e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SubRegisterIndex<a id="a826fc5728ce5ed55eef1807bf32e02a6a2d9fa763e09f66fdd3f9f6a94c1b58e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StringConstant<a id="a826fc5728ce5ed55eef1807bf32e02a6a7dcd0f9b261114fe964552407f110a04"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MIToken() {#a6fd2f79ac3bdafaa1f8e9b87f58e7f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MIToken::MIToken ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>Reference <a href="#a6fd2f79ac3bdafaa1f8e9b87f58e7f36">MIToken</a>.</p>


<p>Referenced by <a href="#a6fd2f79ac3bdafaa1f8e9b87f58e7f36">MIToken</a>, <a href="#ac1edd22e2655350cb4c4fcbb196675ee">reset</a>, <a href="#aafe77831f41912b2cd227484d30ae81d">setIntegerValue</a>, <a href="#ae1c883d2616acba40d12a921840a3a0a">setOwnedStringValue</a> and <a href="#a0a6c1c13ddbd40786b667a40ac3b48de">setStringValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### hasIntegerValue() {#a46d787045053ab1b2de9daae0f5ed5c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIToken::hasIntegerValue ()</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>References <a href="#a826fc5728ce5ed55eef1807bf32e02a6a33dab87da238f19cc21814c491b2d6af">ConstantPoolItem</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6a9d8e09e328411c8dbdbd11f38bf1ff5b">FixedStackObject</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6a850ebe3ac4c626d9ea0cb6f26e7c904e">GlobalValue</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">IntegerLiteral</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6ab80383451bf22665b8b1e7deec8dba7e">IRBlock</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6a56f6273627f38aacd8af4fe49a4dbab8">IRValue</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6af1ed79b968bc264cdbc86258d8566f0c">JumpTableIndex</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6a3f519613749a65e91b6dfe908aaf554e">MachineBasicBlock</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6a7e5c1b1fdcdabc0c2d3ed5941308db6c">MachineBasicBlockLabel</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6a02ea7320381cc7361f5f3530892eb3e1">StackObject</a> and <a href="#a826fc5728ce5ed55eef1807bf32e02a6aad89006e07a1b4b432094251dafeb05e">VirtualRegister</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a54d4f384d80faf60cae54184adc6dcb4">getUnsigned</a>.</p>

</div>
</div>

### integerValue() {#afa2a600dde7f9ae95c2255973ad25286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APSInt &amp; llvm::MIToken::integerValue ()</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a54d4f384d80faf60cae54184adc6dcb4">getUnsigned</a>.</p>

</div>
</div>

### is() {#a6390be713bc6ca27dfadffc3ca549542}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIToken::is (<a href="#a826fc5728ce5ed55eef1807bf32e02a6">TokenKind</a> K)</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a5e3a9067624454f77d0c2bc55bcdaf89">getHexUint</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a54d4f384d80faf60cae54184adc6dcb4">getUnsigned</a>.</p>

</div>
</div>

### isError() {#ac2deed85c7c9addd45a26ff489684677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIToken::isError ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>Reference <a href="#a826fc5728ce5ed55eef1807bf32e02a6a695bb4e1c6c5b89177aeb0f0cf489580">Error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a7167f37d6c009e5ab809b1e4a8a7c81f">maybeLexExclaim</a>.</p>

</div>
</div>

### isErrorOrEOF() {#abb561c9239fe4dfe771fa55dd88446f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIToken::isErrorOrEOF ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>References <a href="#a826fc5728ce5ed55eef1807bf32e02a6a9451d22efb0e7385c6b73ca7799b1d70">Eof</a> and <a href="#a826fc5728ce5ed55eef1807bf32e02a6a695bb4e1c6c5b89177aeb0f0cf489580">Error</a>.</p>

</div>
</div>

### isMemoryOperandFlag() {#a756421c5cd5513bf888855e29269756a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIToken::isMemoryOperandFlag ()</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>References <a href="#a826fc5728ce5ed55eef1807bf32e02a6aa622b3d50d254c6f16b5f0dc2693f9ac">kw_dereferenceable</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6aa82f97904d6c89ebe2d24b97cc8c9b3f">kw_invariant</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6a8d5d15b10a5a1d9cf253d722eb2a6089">kw_non_temporal</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6a1ede3539864c36bc93493e09f7b0fdec">kw_volatile</a> and <a href="#a826fc5728ce5ed55eef1807bf32e02a6a7dcd0f9b261114fe964552407f110a04">StringConstant</a>.</p>

</div>
</div>

### isNewlineOrEOF() {#a4107bf4a0e5f0f679bce7c091947a447}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIToken::isNewlineOrEOF ()</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>References <a href="#a826fc5728ce5ed55eef1807bf32e02a6a9451d22efb0e7385c6b73ca7799b1d70">Eof</a> and <a href="#a826fc5728ce5ed55eef1807bf32e02a6a38401c9f9d25b14c3ca4a36214b5f290">Newline</a>.</p>

</div>
</div>

### isNot() {#a4d3f762500f257cd21c7ab6703e7669d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIToken::isNot (<a href="#a826fc5728ce5ed55eef1807bf32e02a6">TokenKind</a> K)</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>

</div>
</div>

### isRegister() {#aa500122720f4bd103478353e6a6fc114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIToken::isRegister ()</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>References <a href="#a826fc5728ce5ed55eef1807bf32e02a6ada1e13f84d573245c05460a99ef47607">NamedRegister</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6a4bb75c93c34ebe814b2500733ed2cbe2">NamedVirtualRegister</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6a1fcbf573b686db8220b374ddfce6bbdc">underscore</a> and <a href="#a826fc5728ce5ed55eef1807bf32e02a6aad89006e07a1b4b432094251dafeb05e">VirtualRegister</a>.</p>

</div>
</div>

### isRegisterFlag() {#a0627b5671af49734d35148f15c18f51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIToken::isRegisterFlag ()</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>References <a href="#a826fc5728ce5ed55eef1807bf32e02a6a3c27c3f12ff5eac92e28e03d48af0a58">kw_dead</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6a6edca770467a61b3a5750a36b7c7731e">kw_debug_use</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6addae3c49cf7e04a1535a29021ae91423">kw_def</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6a4cb41f854136268b98f0a3b6f8b7d0b9">kw_early_clobber</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6ab206051858a3a8aec9100cc51e5cfcb5">kw_implicit</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6aa6a826947733d28faf3db46eb2924cbd">kw_implicit_define</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6ae7fa8038ec793e64852ab7942c2bf5f0">kw_internal</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6ae6c29e07f6ec069203986ffe91d9bb63">kw_killed</a>, <a href="#a826fc5728ce5ed55eef1807bf32e02a6abd8994d7aa807f0fc7a79bc0bd49ae51">kw_renamable</a> and <a href="#a826fc5728ce5ed55eef1807bf32e02a6af21fe671190c392445d0b4f6809403da">kw_undef</a>.</p>

</div>
</div>

### kind() {#a3dca48803924924232858ce24ee03c9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TokenKind llvm::MIToken::kind ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#ad9f5610f1837c8d9df4a404f2b880b63">parseGlobalValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a35017776f5e9dd9dbc7f71d56a77135a">parseIRValue</a>.</p>

</div>
</div>

### location() {#ae748f46851917c5a8bbd2b6cd9e6c7b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator llvm::MIToken::location ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a54d4f384d80faf60cae54184adc6dcb4">getUnsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a7167f37d6c009e5ab809b1e4a8a7c81f">maybeLexExclaim</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#ad9f5610f1837c8d9df4a404f2b880b63">parseGlobalValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a35017776f5e9dd9dbc7f71d56a77135a">parseIRValue</a>.</p>

</div>
</div>

### range() {#a82fdc67c3d7bd8c6fb7278d4fc0accda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MIToken::range ()</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a5e3a9067624454f77d0c2bc55bcdaf89">getHexUint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#ad9f5610f1837c8d9df4a404f2b880b63">parseGlobalValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a35017776f5e9dd9dbc7f71d56a77135a">parseIRValue</a>.</p>

</div>
</div>

### reset() {#ac1edd22e2655350cb4c4fcbb196675ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIToken &amp; MIToken::reset (<a href="#a826fc5728ce5ed55eef1807bf32e02a6">TokenKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>Reference <a href="#a6fd2f79ac3bdafaa1f8e9b87f58e7f36">MIToken</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#af424d285ff5841f2b72740200a19fc52">lexFloatingPointLiteral</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a751d4b410566e7af9878b48ecb803a62">lexNamedVirtualRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a68ca6d53c1a7e468c10ff026e307957a">lexVirtualRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a01f74b24df78737ec2f22b65d2f37c91">maybeLexEscapedIRValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a7167f37d6c009e5ab809b1e4a8a7c81f">maybeLexExclaim</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#ad03860fe4db1cfdfe373bf181829fb88">maybeLexGlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a681d6dc497d72f781f0d6e37ef92adf6">maybeLexHexadecimalLiteral</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a9e7e252de6ff5a1af41bfb17e92c7764">maybeLexIdentifier</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#afcc4cdfb302bc22d1b9cdca6a419f7b7">maybeLexIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a81dc0e46445de327a0956a30e6fc0662">maybeLexIndexAndName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#ae8a1ef6fb7c2e91c66607669addcbec9">maybeLexMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a95bd4c442d09906ba3a98a436150d637">maybeLexMCSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a8f361b0c5074bb978be4e17286449842">maybeLexNewline</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a6f2a6cc3ecc29db91025a59a8b2719b1">maybeLexNumericalLiteral</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a67fb11afc51aa3e8a17d67db0457cdf2">maybeLexRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a4820a34a5c7d00417a38c0cf2321f9f3">maybeLexSymbol</a>.</p>

</div>
</div>

### setIntegerValue() {#aafe77831f41912b2cd227484d30ae81d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIToken &amp; MIToken::setIntegerValue (<a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> IntVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>Reference <a href="#a6fd2f79ac3bdafaa1f8e9b87f58e7f36">MIToken</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a68ca6d53c1a7e468c10ff026e307957a">lexVirtualRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#ad03860fe4db1cfdfe373bf181829fb88">maybeLexGlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#afcc4cdfb302bc22d1b9cdca6a419f7b7">maybeLexIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a81dc0e46445de327a0956a30e6fc0662">maybeLexIndexAndName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#ae8a1ef6fb7c2e91c66607669addcbec9">maybeLexMachineBasicBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a6f2a6cc3ecc29db91025a59a8b2719b1">maybeLexNumericalLiteral</a>.</p>

</div>
</div>

### setOwnedStringValue() {#ae1c883d2616acba40d12a921840a3a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIToken &amp; MIToken::setOwnedStringValue (std::string StrVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>Reference <a href="#a6fd2f79ac3bdafaa1f8e9b87f58e7f36">MIToken</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a95bd4c442d09906ba3a98a436150d637">maybeLexMCSymbol</a>.</p>

</div>
</div>

### setStringValue() {#a0a6c1c13ddbd40786b667a40ac3b48de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIToken &amp; MIToken::setStringValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StrVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a>.</p>


<p>Reference <a href="#a6fd2f79ac3bdafaa1f8e9b87f58e7f36">MIToken</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#ac158810c8b2357fd343d90fb8d82f5a1">lexName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a751d4b410566e7af9878b48ecb803a62">lexNamedVirtualRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a01f74b24df78737ec2f22b65d2f37c91">maybeLexEscapedIRValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a9e7e252de6ff5a1af41bfb17e92c7764">maybeLexIdentifier</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a81dc0e46445de327a0956a30e6fc0662">maybeLexIndexAndName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#ae8a1ef6fb7c2e91c66607669addcbec9">maybeLexMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a95bd4c442d09906ba3a98a436150d637">maybeLexMCSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a67fb11afc51aa3e8a17d67db0457cdf2">maybeLexRegister</a>.</p>

</div>
</div>

### stringValue() {#a7c73a2b1eeb149f6d2b8ef7568fbb045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MIToken::stringValue ()</td>
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

<p>Return the token's string value.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#ad9f5610f1837c8d9df4a404f2b880b63">parseGlobalValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a35017776f5e9dd9dbc7f71d56a77135a">parseIRValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IntVal {#ac3be929b866d6c9b8f54caa60505f39a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::MIToken::IntVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>

</div>
</div>

### Kind {#af09936b6a34e7fd588e1dd58dd95c89b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TokenKind llvm::MIToken::Kind = <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>

</div>
</div>

### Range {#a428ef0c0c385d56f1c4cce5d568027b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MIToken::Range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>

</div>
</div>

### StringValue {#a7f99fbc993507137aab559913de6b94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MIToken::StringValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>

</div>
</div>

### StringValueStorage {#ab1ba0f6a2c20b890414f776fcbd1d5b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MIToken::StringValueStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp">MILexer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-h">MILexer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
