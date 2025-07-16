---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/asmtoken
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AsmToken` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> independent representation for an assembler token. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AsmToken { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">llvm/MC/MCAsmMacro.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TokenKind { <a href="#ab4316e41520ea53f789582c25bbec039">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae76ec036542a3f4ed1ff0a643e678d2c">AsmToken</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a11c05498e7fc8781b3841dfce28d47">AsmToken</a> (TokenKind Kind, StringRef Str, APInt IntVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83a17242ac80912325857beaabddc006">AsmToken</a> (TokenKind Kind, StringRef Str, int64_t IntVal=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab4316e41520ea53f789582c25bbec039">TokenKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a792392c4dfe6e57615554204b0c51a2e">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a710e72de4b87af42e7605679d1fb2c24">is</a> (TokenKind K) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f492d3c8c226803c571528284a95d36">isNot</a> (TokenKind K) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16611db1be4d04f03c570d9302504c04">getLoc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e6496a765eb2a14512ca0d5f48185fa">getEndLoc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7c6d7b4ff05167be0f9ede415eedaf5">getLocRange</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60d076b08aaef1dbf93f0ed5f8cf9d01">getStringContents</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the contents of a string token (without quotes). <a href="#a60d076b08aaef1dbf93f0ed5f8cf9d01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefa517e84a358fccd59fb1815b87fa44">getIdentifier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the identifier string for the current token, which should be an identifier or a string. <a href="#aefa517e84a358fccd59fb1815b87fa44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3168618a19701d0fb78aefb4d4e664de">getString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the string for the current token, this includes all characters (for example, the quotes on strings) in the token. <a href="#a3168618a19701d0fb78aefb4d4e664de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a270e1171db01008f862ffbc34f8476fc">getIntVal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa960a124e1daa86328571e633f8f8dd5">getAPIntVal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8e74c88aca8715d0c131ce35b75387">dump</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab4316e41520ea53f789582c25bbec039">TokenKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c9d0bc4177fbc1e5ee83a9dc8cc982">Kind</a> = <a href="#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">TokenKind::Eof</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa072360b8e99ab9b78d2719dfe0ef3e9">Str</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to the entire token contents; this is always a pointer into a memory buffer owned by the source manager. <a href="#aa072360b8e99ab9b78d2719dfe0ef3e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0482ac3537eae4aab7f6645e242c2700">IntVal</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> independent representation for an assembler token.</p>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### TokenKind {#ab4316e41520ea53f789582c25bbec039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AsmToken::TokenKind </td>
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
<td class="doxyEnumItemName">Eof<a id="ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Error<a id="ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Identifier<a id="ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">String<a id="ab4316e41520ea53f789582c25bbec039a18d693ac4253b089ce44aa602246fe58"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Integer<a id="ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BigNum<a id="ab4316e41520ea53f789582c25bbec039a8792e8ff663b631c3d0069d1655c7b45"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Real<a id="ab4316e41520ea53f789582c25bbec039ad1efc309b8dfe9289db5493d71569f0b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Comment<a id="ab4316e41520ea53f789582c25bbec039a0765774402d06b304b3f4bee2e6231ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HashDirective<a id="ab4316e41520ea53f789582c25bbec039a5ed906a629ca3518e4b230146dff4c7a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndOfStatement<a id="ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Colon<a id="ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Space<a id="ab4316e41520ea53f789582c25bbec039a1ff20331fe667c9bf3a49cc28516155e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Plus<a id="ab4316e41520ea53f789582c25bbec039ac97d79769cee46bf3915460c278d5de6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Minus<a id="ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Tilde<a id="ab4316e41520ea53f789582c25bbec039a151c8770a1290c7713e3a8490ee09471"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Slash<a id="ab4316e41520ea53f789582c25bbec039a9416ef6f33208f9c76db8f44ca45e61a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BackSlash<a id="ab4316e41520ea53f789582c25bbec039a3690783ddbc5a9d0f0f3c94f48dcf052"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LParen<a id="ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RParen<a id="ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LBrac<a id="ab4316e41520ea53f789582c25bbec039a33f6b27b4c0cd2e6d1e970ea90de765d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RBrac<a id="ab4316e41520ea53f789582c25bbec039a23ee1110c9b68d6faa5a6823d1a90740"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LCurly<a id="ab4316e41520ea53f789582c25bbec039a940bbb142e7bb0990d40889426def99c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RCurly<a id="ab4316e41520ea53f789582c25bbec039a3847b0adce89a393ecf0b359d8ff8646"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Question<a id="ab4316e41520ea53f789582c25bbec039a5ee2ae41fbe7fbaa6e0d98b06e85ca4e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Star<a id="ab4316e41520ea53f789582c25bbec039a871b85a46f471e616995b722df807211"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dot<a id="ab4316e41520ea53f789582c25bbec039ae95926c6ea560f4332395213cc7519e9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Comma<a id="ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dollar<a id="ab4316e41520ea53f789582c25bbec039aaf57ac1b90bbb375414e2fd3fc15bf4c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Equal<a id="ab4316e41520ea53f789582c25bbec039aaf27951b9eea060afd2ae6a01e8a8e0e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EqualEqual<a id="ab4316e41520ea53f789582c25bbec039a8d7d001fb130f9f7daa5b8f1b3ca3044"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pipe<a id="ab4316e41520ea53f789582c25bbec039a7da9940ae6624563c0ff853d5fa7abc5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PipePipe<a id="ab4316e41520ea53f789582c25bbec039aa74a0718c3470a543bb0b0a865d3fc68"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Caret<a id="ab4316e41520ea53f789582c25bbec039a37166ce08fbc1f81e0b1637575f3f116"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Amp<a id="ab4316e41520ea53f789582c25bbec039a829ba931cbc81b6741c399abca551130"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AmpAmp<a id="ab4316e41520ea53f789582c25bbec039a4f6152e3e4d07396f01fcee52f9e6a8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Exclaim<a id="ab4316e41520ea53f789582c25bbec039af475f82c0aa5e42ef5751dcdc3bee49f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExclaimEqual<a id="ab4316e41520ea53f789582c25bbec039ad8f908421e23922e29e64df58fb3f61f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Percent<a id="ab4316e41520ea53f789582c25bbec039a3307eed2aff3782f3d420aebbe433486"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Hash<a id="ab4316e41520ea53f789582c25bbec039a8008076fe2821cf033daf56965fd748b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Less<a id="ab4316e41520ea53f789582c25bbec039a8ed7ac51e3a2326ae92b40e8154d0e6b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LessEqual<a id="ab4316e41520ea53f789582c25bbec039a42a1d2e47b0e72229b4527397e7bd3f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LessLess<a id="ab4316e41520ea53f789582c25bbec039a2cd2ef0141924332a5db5c4d67a58d76"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LessGreater<a id="ab4316e41520ea53f789582c25bbec039a75b12bfe9ad391209f61bd77d198ac3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Greater<a id="ab4316e41520ea53f789582c25bbec039a0bf4b7df9c117d60974b94c95d778fc3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GreaterEqual<a id="ab4316e41520ea53f789582c25bbec039a59fc39402b39f6d595004effefd091c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GreaterGreater<a id="ab4316e41520ea53f789582c25bbec039aa196e2a16fa7cc608b18b2bb7c0db3c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">At<a id="ab4316e41520ea53f789582c25bbec039a4aeb4b633eccde6dcae9b02af09c8302"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MinusGreater<a id="ab4316e41520ea53f789582c25bbec039ab7565cea737f907e6d9d8a66b2f20a19"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentCall16<a id="ab4316e41520ea53f789582c25bbec039a00c4e8d8fb246b6b7aeed5c7b53ee299"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentCall_Hi<a id="ab4316e41520ea53f789582c25bbec039a707c1a6ff33be3833fa784e55c72d356"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentCall_Lo<a id="ab4316e41520ea53f789582c25bbec039a074f871580c44c082aa24aaafd8a238a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentDtprel_Hi<a id="ab4316e41520ea53f789582c25bbec039a267b3c56c189ca7b2c22f3f5a29647fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentDtprel_Lo<a id="ab4316e41520ea53f789582c25bbec039aa8b764c71f0045677baab76623a52bcd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentGot<a id="ab4316e41520ea53f789582c25bbec039a00774b22629d30aaa48e1c2bd537028b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentGot_Disp<a id="ab4316e41520ea53f789582c25bbec039af1f8ea5e121b4bc15a5df42c055bd6d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentGot_Hi<a id="ab4316e41520ea53f789582c25bbec039ab0762694eece06d0f7a3a2079a4a4fc8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentGot_Lo<a id="ab4316e41520ea53f789582c25bbec039a0c1d09e9bf3105cc4a9f0fdbd353573e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentGot_Ofst<a id="ab4316e41520ea53f789582c25bbec039ad1e2f5b48c997464f7959fc57dffc5f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentGot_Page<a id="ab4316e41520ea53f789582c25bbec039a92f6b21bb33e8fed87795f60509087b9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentGottprel<a id="ab4316e41520ea53f789582c25bbec039a0605e7b15189ad4dbaf2de310d8d71d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentGp_Rel<a id="ab4316e41520ea53f789582c25bbec039aceac274aaa62864ab0b60654281e237a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentHi<a id="ab4316e41520ea53f789582c25bbec039a07aadc6194c34b01c1dbc32579382c1e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentHigher<a id="ab4316e41520ea53f789582c25bbec039a1889a8a107d7a02053f669a752290d2d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentHighest<a id="ab4316e41520ea53f789582c25bbec039ab00380bcbfc11a24a06d6ff70619f9fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentLo<a id="ab4316e41520ea53f789582c25bbec039ad3c8fae162d44bb21f7f39c853e85eca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentNeg<a id="ab4316e41520ea53f789582c25bbec039afe3b827d1ceee6cf5aaf0bb61cc1e77f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentPcrel_Hi<a id="ab4316e41520ea53f789582c25bbec039a28be2810a4857bb3b0aad6844d80176e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentPcrel_Lo<a id="ab4316e41520ea53f789582c25bbec039a7aa2c1d1de0fe4ef4d1d2275632aa6a1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentTlsgd<a id="ab4316e41520ea53f789582c25bbec039a8f666b660d975090f718938ee00fe9fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentTlsldm<a id="ab4316e41520ea53f789582c25bbec039a91a7f91ec2b3a0618572a821556591cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentTprel_Hi<a id="ab4316e41520ea53f789582c25bbec039a8df6f192abb2cb6a173a7a2aa91bd8a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PercentTprel_Lo<a id="ab4316e41520ea53f789582c25bbec039a63518ba1849d2eb240372e55b9a04436"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AsmToken() {#ae76ec036542a3f4ed1ff0a643e678d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AsmToken::AsmToken ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>

</div>
</div>

### AsmToken() {#a5a11c05498e7fc8781b3841dfce28d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AsmToken::AsmToken (<a href="#ab4316e41520ea53f789582c25bbec039">TokenKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> IntVal)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### AsmToken() {#a83a17242ac80912325857beaabddc006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AsmToken::AsmToken (<a href="#ab4316e41520ea53f789582c25bbec039">TokenKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, int64_t IntVal=0)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a9e8e74c88aca8715d0c131ce35b75387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AsmToken::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmlexer-cpp">MCAsmLexer.cpp</a>.</p>


<p>References <a href="#ab4316e41520ea53f789582c25bbec039a829ba931cbc81b6741c399abca551130">Amp</a>, <a href="#ab4316e41520ea53f789582c25bbec039a4f6152e3e4d07396f01fcee52f9e6a8d">AmpAmp</a>, <a href="#ab4316e41520ea53f789582c25bbec039a4aeb4b633eccde6dcae9b02af09c8302">At</a>, <a href="#ab4316e41520ea53f789582c25bbec039a3690783ddbc5a9d0f0f3c94f48dcf052">BackSlash</a>, <a href="#ab4316e41520ea53f789582c25bbec039a8792e8ff663b631c3d0069d1655c7b45">BigNum</a>, <a href="#ab4316e41520ea53f789582c25bbec039a37166ce08fbc1f81e0b1637575f3f116">Caret</a>, <a href="#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">Colon</a>, <a href="#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">Comma</a>, <a href="#ab4316e41520ea53f789582c25bbec039a0765774402d06b304b3f4bee2e6231ed">Comment</a>, <a href="#ab4316e41520ea53f789582c25bbec039aaf57ac1b90bbb375414e2fd3fc15bf4c">Dollar</a>, <a href="#ab4316e41520ea53f789582c25bbec039ae95926c6ea560f4332395213cc7519e9">Dot</a>, <a href="#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">EndOfStatement</a>, <a href="#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">Eof</a>, <a href="#ab4316e41520ea53f789582c25bbec039aaf27951b9eea060afd2ae6a01e8a8e0e">Equal</a>, <a href="#ab4316e41520ea53f789582c25bbec039a8d7d001fb130f9f7daa5b8f1b3ca3044">EqualEqual</a>, <a href="#ab4316e41520ea53f789582c25bbec039a1a7046e38c86395ad911f3f0d86b1012">Error</a>, <a href="#ab4316e41520ea53f789582c25bbec039af475f82c0aa5e42ef5751dcdc3bee49f">Exclaim</a>, <a href="#ab4316e41520ea53f789582c25bbec039ad8f908421e23922e29e64df58fb3f61f">ExclaimEqual</a>, <a href="#a3168618a19701d0fb78aefb4d4e664de">getString</a>, <a href="#ab4316e41520ea53f789582c25bbec039a0bf4b7df9c117d60974b94c95d778fc3">Greater</a>, <a href="#ab4316e41520ea53f789582c25bbec039a59fc39402b39f6d595004effefd091c3">GreaterEqual</a>, <a href="#ab4316e41520ea53f789582c25bbec039aa196e2a16fa7cc608b18b2bb7c0db3c3">GreaterGreater</a>, <a href="#ab4316e41520ea53f789582c25bbec039a8008076fe2821cf033daf56965fd748b">Hash</a>, <a href="#ab4316e41520ea53f789582c25bbec039a5ed906a629ca3518e4b230146dff4c7a">HashDirective</a>, <a href="#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">Identifier</a>, <a href="#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">Integer</a>, <a href="#ab4316e41520ea53f789582c25bbec039a33f6b27b4c0cd2e6d1e970ea90de765d">LBrac</a>, <a href="#ab4316e41520ea53f789582c25bbec039a940bbb142e7bb0990d40889426def99c">LCurly</a>, <a href="#ab4316e41520ea53f789582c25bbec039a8ed7ac51e3a2326ae92b40e8154d0e6b">Less</a>, <a href="#ab4316e41520ea53f789582c25bbec039a42a1d2e47b0e72229b4527397e7bd3f6">LessEqual</a>, <a href="#ab4316e41520ea53f789582c25bbec039a75b12bfe9ad391209f61bd77d198ac3d">LessGreater</a>, <a href="#ab4316e41520ea53f789582c25bbec039a2cd2ef0141924332a5db5c4d67a58d76">LessLess</a>, <a href="#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">LParen</a>, <a href="#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">Minus</a>, <a href="#ab4316e41520ea53f789582c25bbec039ab7565cea737f907e6d9d8a66b2f20a19">MinusGreater</a>, <a href="#ab4316e41520ea53f789582c25bbec039a3307eed2aff3782f3d420aebbe433486">Percent</a>, <a href="#ab4316e41520ea53f789582c25bbec039a00c4e8d8fb246b6b7aeed5c7b53ee299">PercentCall16</a>, <a href="#ab4316e41520ea53f789582c25bbec039a707c1a6ff33be3833fa784e55c72d356">PercentCall_Hi</a>, <a href="#ab4316e41520ea53f789582c25bbec039a074f871580c44c082aa24aaafd8a238a">PercentCall_Lo</a>, <a href="#ab4316e41520ea53f789582c25bbec039a267b3c56c189ca7b2c22f3f5a29647fe">PercentDtprel_Hi</a>, <a href="#ab4316e41520ea53f789582c25bbec039aa8b764c71f0045677baab76623a52bcd">PercentDtprel_Lo</a>, <a href="#ab4316e41520ea53f789582c25bbec039a00774b22629d30aaa48e1c2bd537028b">PercentGot</a>, <a href="#ab4316e41520ea53f789582c25bbec039af1f8ea5e121b4bc15a5df42c055bd6d7">PercentGot_Disp</a>, <a href="#ab4316e41520ea53f789582c25bbec039ab0762694eece06d0f7a3a2079a4a4fc8">PercentGot_Hi</a>, <a href="#ab4316e41520ea53f789582c25bbec039a0c1d09e9bf3105cc4a9f0fdbd353573e">PercentGot_Lo</a>, <a href="#ab4316e41520ea53f789582c25bbec039ad1e2f5b48c997464f7959fc57dffc5f8">PercentGot_Ofst</a>, <a href="#ab4316e41520ea53f789582c25bbec039a92f6b21bb33e8fed87795f60509087b9">PercentGot_Page</a>, <a href="#ab4316e41520ea53f789582c25bbec039a0605e7b15189ad4dbaf2de310d8d71d6">PercentGottprel</a>, <a href="#ab4316e41520ea53f789582c25bbec039aceac274aaa62864ab0b60654281e237a">PercentGp_Rel</a>, <a href="#ab4316e41520ea53f789582c25bbec039a07aadc6194c34b01c1dbc32579382c1e">PercentHi</a>, <a href="#ab4316e41520ea53f789582c25bbec039a1889a8a107d7a02053f669a752290d2d">PercentHigher</a>, <a href="#ab4316e41520ea53f789582c25bbec039ab00380bcbfc11a24a06d6ff70619f9fa">PercentHighest</a>, <a href="#ab4316e41520ea53f789582c25bbec039ad3c8fae162d44bb21f7f39c853e85eca">PercentLo</a>, <a href="#ab4316e41520ea53f789582c25bbec039afe3b827d1ceee6cf5aaf0bb61cc1e77f">PercentNeg</a>, <a href="#ab4316e41520ea53f789582c25bbec039a28be2810a4857bb3b0aad6844d80176e">PercentPcrel_Hi</a>, <a href="#ab4316e41520ea53f789582c25bbec039a7aa2c1d1de0fe4ef4d1d2275632aa6a1">PercentPcrel_Lo</a>, <a href="#ab4316e41520ea53f789582c25bbec039a8f666b660d975090f718938ee00fe9fc">PercentTlsgd</a>, <a href="#ab4316e41520ea53f789582c25bbec039a91a7f91ec2b3a0618572a821556591cf">PercentTlsldm</a>, <a href="#ab4316e41520ea53f789582c25bbec039a8df6f192abb2cb6a173a7a2aa91bd8a2">PercentTprel_Hi</a>, <a href="#ab4316e41520ea53f789582c25bbec039a63518ba1849d2eb240372e55b9a04436">PercentTprel_Lo</a>, <a href="#ab4316e41520ea53f789582c25bbec039a7da9940ae6624563c0ff853d5fa7abc5">Pipe</a>, <a href="#ab4316e41520ea53f789582c25bbec039aa74a0718c3470a543bb0b0a865d3fc68">PipePipe</a>, <a href="#ab4316e41520ea53f789582c25bbec039ac97d79769cee46bf3915460c278d5de6">Plus</a>, <a href="#ab4316e41520ea53f789582c25bbec039a5ee2ae41fbe7fbaa6e0d98b06e85ca4e">Question</a>, <a href="#ab4316e41520ea53f789582c25bbec039a23ee1110c9b68d6faa5a6823d1a90740">RBrac</a>, <a href="#ab4316e41520ea53f789582c25bbec039a3847b0adce89a393ecf0b359d8ff8646">RCurly</a>, <a href="#ab4316e41520ea53f789582c25bbec039ad1efc309b8dfe9289db5493d71569f0b">Real</a>, <a href="#ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322">RParen</a>, <a href="#ab4316e41520ea53f789582c25bbec039a9416ef6f33208f9c76db8f44ca45e61a">Slash</a>, <a href="#ab4316e41520ea53f789582c25bbec039a1ff20331fe667c9bf3a49cc28516155e">Space</a>, <a href="#ab4316e41520ea53f789582c25bbec039a871b85a46f471e616995b722df807211">Star</a>, <a href="#ab4316e41520ea53f789582c25bbec039a18d693ac4253b089ce44aa602246fe58">String</a>, <a href="#ab4316e41520ea53f789582c25bbec039a151c8770a1290c7713e3a8490ee09471">Tilde</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a5ba2ece4b959bae02752c34b784ba087">llvm::raw_ostream::write_escaped</a>.</p>

</div>
</div>

### getAPIntVal() {#aa960a124e1daa86328571e633f8f8dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::AsmToken::getAPIntVal ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab4316e41520ea53f789582c25bbec039a8792e8ff663b631c3d0069d1655c7b45">BigNum</a> and <a href="#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">Integer</a>.</p>

</div>
</div>

### getEndLoc() {#a9e6496a765eb2a14512ca0d5f48185fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AsmToken::getEndLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmlexer-cpp">MCAsmLexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>.</p>


<p>Referenced by <a href="#ad7c6d7b4ff05167be0f9ede415eedaf5">getLocRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1c8f1c479ef06f41b1f2010afd80b43a">anonymous{AsmParser.cpp}::AsmParser::parseParenExprOfDepth</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a61115ff1360e15d4f0eb3f12d757d7c1">anonymous{MasmParser.cpp}::MasmParser::parseParenExprOfDepth</a> and <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a9b009cbb00b2beb18520fa257b674a9c">anonymous{ARMAsmParser.cpp}::ARMAsmParser::parseRegister</a>.</p>

</div>
</div>

### getIdentifier() {#aefa517e84a358fccd59fb1815b87fa44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AsmToken::getIdentifier ()</td>
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

<p>Get the identifier string for the current token, which should be an identifier or a string.</p>


<p>This gets the portion of the string which should be used as the identifier, e.g., it does not include the quotes on strings.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>


<p>References <a href="#a3168618a19701d0fb78aefb4d4e664de">getString</a>, <a href="#a60d076b08aaef1dbf93f0ed5f8cf9d01">getStringContents</a> and <a href="#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">Identifier</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp/#a21988b6120a3252f50bd655296f7903d">isSDKVersionToken</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a5a86255e1b22fdc61781627d840204c5">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#adf59b005b7771f4aa72204093c13c804">anonymous{ARMAsmParser.cpp}::ARMAsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#acb92a6ad259468a1081b2942e9ce8930">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a0e9209ef161dfa2b45ab9f122f2ada34">anonymous{PPCAsmParser.cpp}::PPCAsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#a605f317c5671abb87131f5dcb6b2fe4a">anonymous{X86AsmParser.cpp}::X86AsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a3390881f203f23dca9f40c151f89d581">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#aa91d3c1b093e3561b948794724961f4b">anonymous{AsmParser.cpp}::AsmParser::parseIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#af6dea9845d70ac952115bdbe378dbea1">anonymous{MasmParser.cpp}::MasmParser::parseIdentifier</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a0cacf6ffb7a5ce2195bd33f0e9c0087c">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseInstruction</a>.</p>

</div>
</div>

### getIntVal() {#a270e1171db01008f862ffbc34f8476fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AsmToken::getIntVal ()</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">Integer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#ae70fbaacac6a12bfc3904b3e1af622bb">llvm::MCAsmParser::parseGNUAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a8d9acbc65c25f0330cd2d8d6baded980">llvm::MCAsmParser::parseIntToken</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a>.</p>

</div>
</div>

### getKind() {#a792392c4dfe6e57615554204b0c51a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TokenKind llvm::AsmToken::getKind ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#aada8db353e1a724d98d761da7e2cb94a">llvm::MCAsmLexer::getKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4e07e3e64caa97fc5dbc73fe0b20d311">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a0cacf6ffb7a5ce2195bd33f0e9c0087c">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a7fe5bbdb7d87187478d77f3a1d5a2a93">llvm::MCAsmParser::parseOptionalToken</a>.</p>

</div>
</div>

### getLoc() {#a16611db1be4d04f03c570d9302504c04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AsmToken::getLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmlexer-cpp">MCAsmLexer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#aaad2cdef1825867940a59ecba856e9db">anonymous{WasmAsmParser.cpp}::WasmAsmParser::error</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4dbe1fe753904593c38938d748ced651">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::error</a>, <a href="#ad7c6d7b4ff05167be0f9ede415eedaf5">getLocRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#aa74c2b313cfce997872aafabddf9866c">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::isLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a5a86255e1b22fdc61781627d840204c5">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#adf59b005b7771f4aa72204093c13c804">anonymous{ARMAsmParser.cpp}::ARMAsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#acb92a6ad259468a1081b2942e9ce8930">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a0e9209ef161dfa2b45ab9f122f2ada34">anonymous{PPCAsmParser.cpp}::PPCAsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#a605f317c5671abb87131f5dcb6b2fe4a">anonymous{X86AsmParser.cpp}::X86AsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a3390881f203f23dca9f40c151f89d581">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a0478394229fb5470e1489709c8711643">llvm::MCTargetAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#ae70fbaacac6a12bfc3904b3e1af622bb">llvm::MCAsmParser::parseGNUAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#aa91d3c1b093e3561b948794724961f4b">anonymous{AsmParser.cpp}::AsmParser::parseIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#af6dea9845d70ac952115bdbe378dbea1">anonymous{MasmParser.cpp}::MasmParser::parseIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a9d095012b8efc8795fe4403722dcf9d4">llvm::MCTargetAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a9b009cbb00b2beb18520fa257b674a9c">anonymous{ARMAsmParser.cpp}::ARMAsmParser::parseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#adfe743277c072b490a3f6bfc7dd593d1">llvm::MCAsmParser::parseTokenLoc</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#a7bdaa9e163b23aed343a6a8f7589d008">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::splitIdentifier</a>.</p>

</div>
</div>

### getLocRange() {#ad7c6d7b4ff05167be0f9ede415eedaf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMRange AsmToken::getLocRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmlexer-cpp">MCAsmLexer.cpp</a>.</p>


<p>References <a href="#a9e6496a765eb2a14512ca0d5f48185fa">getEndLoc</a> and <a href="#a16611db1be4d04f03c570d9302504c04">getLoc</a>.</p>

</div>
</div>

### getString() {#a3168618a19701d0fb78aefb4d4e664de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AsmToken::getString ()</td>
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

<p>Get the string for the current token, this includes all characters (for example, the quotes on strings) in the token.</p>


<p>The returned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> points into the source manager's memory buffer, and is safe to store across calls to Lex().</p>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>


<p>Referenced by <a href="#a9e8e74c88aca8715d0c131ce35b75387">dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#aaad2cdef1825867940a59ecba856e9db">anonymous{WasmAsmParser.cpp}::WasmAsmParser::error</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4dbe1fe753904593c38938d748ced651">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::error</a>, <a href="#aefa517e84a358fccd59fb1815b87fa44">getIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#aa74c2b313cfce997872aafabddf9866c">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::isLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab69ace2a64f183c1e0600a4155b0a976">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isNamedOperandModifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#af3d4af20be9f94cbdad904d45cafbefa">anonymous{AsmParser.cpp}::AsmParser::Lex</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#afa801ffa70e7cd238829a01fa92d71c4">anonymous{MasmParser.cpp}::MasmParser::Lex</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a52dd8abe6dc2354306df33d817dc3101">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4e07e3e64caa97fc5dbc73fe0b20d311">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#a64ef2d014c82249a7bc8cb033757d7f1">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#abdaa8ae9b3e01099946066f89a8e10ad">anonymous{AsmParser.cpp}::AsmParser::parseRealValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a1c3ac00eab4ed0328bc8c8942957c83b">anonymous{MasmParser.cpp}::MasmParser::parseRealValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#a7bdaa9e163b23aed343a6a8f7589d008">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::splitIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a3836dbcbb0e7b8207e5b1f40a85269af">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParsePrefetch</a>.</p>

</div>
</div>

### getStringContents() {#a60d076b08aaef1dbf93f0ed5f8cf9d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AsmToken::getStringContents ()</td>
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

<p>Get the contents of a string token (without quotes).</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab4316e41520ea53f789582c25bbec039a18d693ac4253b089ce44aa602246fe58">String</a>.</p>


<p>Referenced by <a href="#aefa517e84a358fccd59fb1815b87fa44">getIdentifier</a>.</p>

</div>
</div>

### is() {#a710e72de4b87af42e7605679d1fb2c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AsmToken::is (<a href="#ab4316e41520ea53f789582c25bbec039">TokenKind</a> K)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#ad9a2ad2c78d9254fe58140aef128b6ab">llvm::MCAsmLexer::is</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a3740088be499ac1b2813ea1d6904ef15">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isModifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab69ace2a64f183c1e0600a4155b0a976">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isNamedOperandModifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a9a76b985d6b897a055389b82198509ee">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isOpcodeModifierWithVal</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aae8e311d01222d265293e010df5bc7f5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isOperandModifier</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/darwinasmparser-cpp/#a21988b6120a3252f50bd655296f7903d">isSDKVersionToken</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#af3d4af20be9f94cbdad904d45cafbefa">anonymous{AsmParser.cpp}::AsmParser::Lex</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#afa801ffa70e7cd238829a01fa92d71c4">anonymous{MasmParser.cpp}::MasmParser::Lex</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#a64ef2d014c82249a7bc8cb033757d7f1">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#a18e95622dd1cef434cddeae8612854d8">llvm::AsmLexer::peekTokens</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a3836dbcbb0e7b8207e5b1f40a85269af">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParsePrefetch</a>.</p>

</div>
</div>

### isNot() {#a2f492d3c8c226803c571528284a95d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AsmToken::isNot (<a href="#ab4316e41520ea53f789582c25bbec039">TokenKind</a> K)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmlexer/#a274996965acf3447ca933ddeba9145ce">llvm::MCAsmLexer::isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#ae70fbaacac6a12bfc3904b3e1af622bb">llvm::MCAsmParser::parseGNUAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#af6dea9845d70ac952115bdbe378dbea1">anonymous{MasmParser.cpp}::MasmParser::parseIdentifier</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a3836dbcbb0e7b8207e5b1f40a85269af">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParsePrefetch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IntVal {#a0482ac3537eae4aab7f6645e242c2700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::AsmToken::IntVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>

</div>
</div>

### Kind {#ae8c9d0bc4177fbc1e5ee83a9dc8cc982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TokenKind llvm::AsmToken::Kind = <a href="#ab4316e41520ea53f789582c25bbec039a14d71ecb88bb35bca6ec98ef99813bad">TokenKind::Eof</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>

</div>
</div>

### Str {#aa072360b8e99ab9b78d2719dfe0ef3e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AsmToken::Str</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A reference to the entire token contents; this is always a pointer into a memory buffer owned by the source manager.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmmacro-h">MCAsmMacro.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/mcasmlexer-cpp">MCAsmLexer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
