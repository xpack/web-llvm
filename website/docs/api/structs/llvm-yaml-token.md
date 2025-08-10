---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/token
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Token` Struct

<p><a href="/web-llvm/docs/api/structs/llvm/yaml/token">Token</a> - A single YAML token. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::Token { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TokenKind { <a href="#a160e10c0839740601f1138548ddb0531">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a874f164b5e8b48969251c1830af6cd40">Token</a> ()=default</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#a160e10c0839740601f1138548ddb0531">llvm::yaml::Token::TokenKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a396e0f47847aa197379fa2883e602a24">Kind</a> = <a href="#a160e10c0839740601f1138548ddb0531a5d1fec5f8be79dd4c5956a2503aa2843">TK_Error</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2bc3dca5761a105ee575a8dc5ef36a0">Range</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A string of length 0 or more whose <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#acf3240e230e3dacea7826794a4e2f84b">begin()</a> points to the logical location of the token in the input. <a href="#ab2bc3dca5761a105ee575a8dc5ef36a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a480a8849b94d5c4e51a391177659736f">Value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The value of a block scalar node. <a href="#a480a8849b94d5c4e51a391177659736f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/yaml/token">Token</a> - A single YAML token.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### TokenKind {#a160e10c0839740601f1138548ddb0531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::yaml::Token::TokenKind </td>
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
<td class="doxyEnumItemName">TK_Error<a id="a160e10c0839740601f1138548ddb0531a5d1fec5f8be79dd4c5956a2503aa2843"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_StreamStart<a id="a160e10c0839740601f1138548ddb0531a4ab51119e996b4867f2f3a9c5df14736"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_StreamEnd<a id="a160e10c0839740601f1138548ddb0531a063fd4366f9e152640f754222924b499"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_VersionDirective<a id="a160e10c0839740601f1138548ddb0531a335f55bc2fc296e2875607b7c86a6c1e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_TagDirective<a id="a160e10c0839740601f1138548ddb0531ac294a41f675a4da4f03622c3fab68458"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_DocumentStart<a id="a160e10c0839740601f1138548ddb0531a21388bc616a0c79332f06f17ad2a63da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_DocumentEnd<a id="a160e10c0839740601f1138548ddb0531a966a8a0467d033c2aab7df3b93f7abb6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_BlockEntry<a id="a160e10c0839740601f1138548ddb0531a740ebe1fc34dc71512527c688b6adf76"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_BlockEnd<a id="a160e10c0839740601f1138548ddb0531a7f83863c476433568203d2a37dfaefc1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_BlockSequenceStart<a id="a160e10c0839740601f1138548ddb0531a077c62971dd7272d6c4ccac9307d27ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_BlockMappingStart<a id="a160e10c0839740601f1138548ddb0531a06e9aa56b4f6ec622a31dc0e72b0e3be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_FlowEntry<a id="a160e10c0839740601f1138548ddb0531a1814af059afd1fc841c6bcd0e8c92995"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_FlowSequenceStart<a id="a160e10c0839740601f1138548ddb0531abed63dce168b5d595a7f1d3d3626dd0c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_FlowSequenceEnd<a id="a160e10c0839740601f1138548ddb0531ac4125146ea96c10a281bf1e07dd2d661"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_FlowMappingStart<a id="a160e10c0839740601f1138548ddb0531addfdb5bdb33bcce24a5d5b7ecc5538f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_FlowMappingEnd<a id="a160e10c0839740601f1138548ddb0531ac9c8081f0d5e401295fe53e081c1e7df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_Key<a id="a160e10c0839740601f1138548ddb0531a537b5ded27736279783b16d2f4b670ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_Value<a id="a160e10c0839740601f1138548ddb0531a220bc8a613a1eceb652b17a9f1f4fe80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_Scalar<a id="a160e10c0839740601f1138548ddb0531a91391f278be4723a401519886e49ca6e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_BlockScalar<a id="a160e10c0839740601f1138548ddb0531a71734af33e74dd7b68c4980ed1f766d8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_Alias<a id="a160e10c0839740601f1138548ddb0531ae06ceae74093cd37f3091e1e154f39a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_Anchor<a id="a160e10c0839740601f1138548ddb0531a8340baa944a2841ca03501f13630074b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TK_Tag<a id="a160e10c0839740601f1138548ddb0531a2c0c59b4b92d3d0269d2062f8e6853e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Token() {#a874f164b5e8b48969251c1830af6cd40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Token::Token ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Kind {#a396e0f47847aa197379fa2883e602a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::yaml::Token::TokenKind llvm::yaml::Token::Kind = <a href="#a160e10c0839740601f1138548ddb0531a5d1fec5f8be79dd4c5956a2503aa2843">TK_Error</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#ab423b6588650879f12890d97837328ba">llvm::yaml::KeyValueNode::getKey</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a1294ccf387b5a8f26c64b492fcc38d22">llvm::yaml::KeyValueNode::getValue</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/document/#a195e6cd6c71f2fabbd3d99a61627abee">llvm::yaml::Document::parseBlockNode</a>.</p>

</div>
</div>

### Range {#ab2bc3dca5761a105ee575a8dc5ef36a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::yaml::Token::Range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A string of length 0 or more whose <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#acf3240e230e3dacea7826794a4e2f84b">begin()</a> points to the logical location of the token in the input.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/document/#a195e6cd6c71f2fabbd3d99a61627abee">llvm::yaml::Document::parseBlockNode</a>.</p>

</div>
</div>

### Value {#a480a8849b94d5c4e51a391177659736f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::yaml::Token::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The value of a block scalar node.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
