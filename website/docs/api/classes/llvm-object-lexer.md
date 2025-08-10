---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/lexer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Lexer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::object::Lexer { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae323f663bf93fc7bd67877f6bb72649f">Lexer</a> (StringRef S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/object/token">Token</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f4fa1946ef0ac461232bc74e92dd921">lex</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa17b28cdae8e92b1e16973a0b79d26">Buf</a></td>
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


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffmoduledefinition-cpp">COFFModuleDefinition.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Lexer() {#ae323f663bf93fc7bd67877f6bb72649f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::Lexer::Lexer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffmoduledefinition-cpp">COFFModuleDefinition.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### lex() {#a0f4fa1946ef0ac461232bc74e92dd921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token llvm::object::Lexer::lex ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffmoduledefinition-cpp">COFFModuleDefinition.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47af4af7d56c18513fbef4667deac644cfa">llvm::object::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47a3618142b73b733ca487b0290a3d4b84f">llvm::object::Eof</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47a21197b49151a350ee6714622ed988cc7">llvm::object::Equal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47a59b445edee3e34e12b0643ddc4aa1d4a">llvm::object::EqualEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47acfaaa2f9ff08c82a08d647efc1a2964b">llvm::object::Identifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47ac81418a782f6186a4eaf400b435ba924">llvm::object::KwBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47afaa37ff231f5f028eb7d6c06d8a1170b">llvm::object::KwConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47a70f857dca5332720e07335dba9b9ae09">llvm::object::KwData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47a7394d934893d7e5781008586d38d7ae7">llvm::object::KwExportAs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47adfaae62956fcd44134e2d0f3b715d4f2">llvm::object::KwExports</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47a878de279cd6f9e59cf0cb3d0e77c923d">llvm::object::KwHeapsize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47a91f91326bbe0ab28acef6b2fc6f8f624">llvm::object::KwLibrary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47abfea6ddf5fe76d65c2566f633fab1f0d">llvm::object::KwName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47a9ca603383062e8074d8b0e43b1db9315">llvm::object::KwNoname</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47a725c758db4cca3fe89bd02baf22560cc">llvm::object::KwPrivate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47a117cc2dcc993bca9ea6fe1d9400e618c">llvm::object::KwStacksize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a42e5b6ee6f67085d2115b2ea44588c47afa8a262ef632b51ef28aa8c1246177b2">llvm::object::KwVersion</a>, <a href="#a0f4fa1946ef0ac461232bc74e92dd921">lex</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="#a0f4fa1946ef0ac461232bc74e92dd921">lex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buf {#afaa17b28cdae8e92b1e16973a0b79d26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::Lexer::Buf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffmoduledefinition-cpp">COFFModuleDefinition.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/coffmoduledefinition-cpp">COFFModuleDefinition.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
