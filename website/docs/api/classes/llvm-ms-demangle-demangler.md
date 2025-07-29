---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ms-demangle/demangler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Demangler` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ms_demangle::Demangler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">llvm/Demangle/MicrosoftDemangle.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00ab77724bdd2d5f6a3495e69600d3ad">llvm::getArm64ECInsertionPointInMangledName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d787d0b1cc5fee84a59d5297e7bc13">Demangler</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942ff5c66c6c2139e0bf561ee8aceb8e">~Demangler</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/symbolnode">SymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92ceaf0f7302bb57c5c7e1e810c56093">parse</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/tagtypenode">TagTypeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e7b39f476fe2783df4d468b8103f7c7">parseTagUniqueName</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64ec0c9c49acf91da4f0c361e7c2a76">dumpBackReferences</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/symbolnode">SymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c38c0a2a534b22d347f09158557fa6c">demangleEncodedSymbol</a> (std::string_view &amp;MangledName, QualifiedNameNode *QN)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/symbolnode">SymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3436542f930536fb92f866b588e43e41">demangleDeclarator</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/symbolnode">SymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef56414be9f6f3a133c65ddf4dd0fb2b">demangleMD5Name</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/symbolnode">SymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2785c9875cdb4334ffe16ec8502c7a14">demangleTypeinfoName</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/variablesymbolnode">VariableSymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a031df90ac78bddee3abdb9e689417">demangleVariableEncoding</a> (std::string_view &amp;MangledName, StorageClass SC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/functionsymbolnode">FunctionSymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c3df036838108887d90790cb25810a1">demangleFunctionEncoding</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382c">Qualifiers</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ffd038ea8fef89868021db605f49c1d">demanglePointerExtQualifiers</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode">TypeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28cb13333ecdb95b9e0f1d5f3f158e72">demangleType</a> (std::string_view &amp;MangledName, QualifierMangleMode QMM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/primitivetypenode">PrimitiveTypeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba044817cd8a07e4de60ff72b5bd0727">demanglePrimitiveType</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/customtypenode">CustomTypeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfc0244bd42ec5853305826f0bfa0594">demangleCustomType</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/tagtypenode">TagTypeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e82baa7e91145b188bf25520d4ef358">demangleClassType</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/pointertypenode">PointerTypeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a532a0124a64fe3a14cc396f604a14fc5">demanglePointerType</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/pointertypenode">PointerTypeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f4886822d556cd3671a665c98f6fd8">demangleMemberPointerType</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/functionsignaturenode">FunctionSignatureNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeede616338cc712198e67c2b3cc149de">demangleFunctionType</a> (std::string_view &amp;MangledName, bool HasThisQuals)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/arraytypenode">ArrayTypeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3a851148c1a0351e63932a043336098">demangleArrayType</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/nodearraynode">NodeArrayNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e31150e411b667d7b69175d274c19a7">demangleFunctionParameterList</a> (std::string_view &amp;MangledName, bool &amp;IsVariadic)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/nodearraynode">NodeArrayNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec3a611da83a8af35d770c8c2f646bf">demangleTemplateParameterList</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65a65044c2b2c0ec5c7e23a5e4b1b840">demangleNumber</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096d07aabbdafabe85eae35b8212aef8">demangleUnsigned</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab7db0868aae652606418659050103d9">demangleSigned</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b6cdad234fe05af48ebd489e83e05b">memorizeString</a> (std::string_view s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbc2e6fe3a86150cdb6803db96a2c63a">memorizeIdentifier</a> (IdentifierNode *Identifier)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string_view</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4827ab0143a58397c4d3d8d04c78d47d">copyString</a> (std::string_view Borrowed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a copy of <span class="doxyComputerOutput">Borrowed</span> into memory that we own. <a href="#a4827ab0143a58397c4d3d8d04c78d47d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/qualifiednamenode">QualifiedNameNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0b21f4fd7312e3be629c2a9606f78ec">demangleFullyQualifiedTypeName</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/qualifiednamenode">QualifiedNameNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8937ab6142dee2aeca34c873d8a6049d">demangleFullyQualifiedSymbolName</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/identifiernode">IdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a531b60e714d5e2b04392bc9e32b94df5">demangleUnqualifiedTypeName</a> (std::string_view &amp;MangledName, bool Memorize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/identifiernode">IdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5529cc2067df0861226a5731deb79461">demangleUnqualifiedSymbolName</a> (std::string_view &amp;MangledName, NameBackrefBehavior NBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/qualifiednamenode">QualifiedNameNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88af2fb3dda75ad371ca286bd5cc5fc">demangleNameScopeChain</a> (std::string_view &amp;MangledName, IdentifierNode *UnqualifiedName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/identifiernode">IdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99731c50cb5e44bd044403488c2085d6">demangleNameScopePiece</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/namedidentifiernode">NamedIdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba40d4252bd4a277eb2778b43ff41a1">demangleBackRefName</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/identifiernode">IdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d9813b44f6e03a33e7221387c2b609a">demangleTemplateInstantiationName</a> (std::string_view &amp;MangledName, NameBackrefBehavior NBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a851a17f7dc73f9988807242926dcc645">IntrinsicFunctionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2975159a91e9de03a192267601f26971">translateIntrinsicFunctionCode</a> (char CH, FunctionIdentifierCodeGroup Group)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/identifiernode">IdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93919864728bbb73144fcfe345bd7efa">demangleFunctionIdentifierCode</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/identifiernode">IdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46a701162182ff283e75b0c36462e9bc">demangleFunctionIdentifierCode</a> (std::string_view &amp;MangledName, FunctionIdentifierCodeGroup Group)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/structoridentifiernode">StructorIdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af318197b0d2fc44fc4ab93dc278b54d7">demangleStructorIdentifier</a> (std::string_view &amp;MangledName, bool IsDestructor)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/conversionoperatoridentifiernode">ConversionOperatorIdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32596befbd16a35d41eda63729f8660d">demangleConversionOperatorIdentifier</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/literaloperatoridentifiernode">LiteralOperatorIdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40e695ec8fb99816d20039d51845e2ad">demangleLiteralOperatorIdentifier</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/symbolnode">SymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af144a40c65febae2e165409e0d3b7748">demangleSpecialIntrinsic</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/specialtablesymbolnode">SpecialTableSymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ae0ef7492c1bdab2a324d2643549886">demangleSpecialTableSymbolNode</a> (std::string_view &amp;MangledName, SpecialIntrinsicKind SIK)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/localstaticguardvariablenode">LocalStaticGuardVariableNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af453af0ef7820d7aba6835e885a08737">demangleLocalStaticGuard</a> (std::string_view &amp;MangledName, bool IsThread)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/variablesymbolnode">VariableSymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c3739c318914517497c3803f1df0edc">demangleUntypedVariable</a> (ArenaAllocator &amp;Arena, std::string_view &amp;MangledName, std::string_view VariableName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/variablesymbolnode">VariableSymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa03d8bb48a96d68f414c1d1c6a0ceaa2">demangleRttiBaseClassDescriptorNode</a> (ArenaAllocator &amp;Arena, std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/functionsymbolnode">FunctionSymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a69023bb3587fbb0e7f300e7acaa5a">demangleInitFiniStub</a> (std::string_view &amp;MangledName, bool IsDestructor)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/namedidentifiernode">NamedIdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1486e15a9f326fc7a7175796354ba216">demangleSimpleName</a> (std::string_view &amp;MangledName, bool Memorize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/namedidentifiernode">NamedIdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81b5c1b2ab9d0b0fe6365b67d31b89cf">demangleAnonymousNamespaceName</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/namedidentifiernode">NamedIdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afed2357f386f4832b3c4837715f03d0c">demangleLocallyScopedNamePiece</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/encodedstringliteralnode">EncodedStringLiteralNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ec14a3a00ee57d6f2b8929788c46486">demangleStringLiteral</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/functionsymbolnode">FunctionSymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac05d8fd7300da96c1b573305ea98c00a">demangleVcallThunkNode</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string_view</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3868ba864e6433a251151d8526bf60ba">demangleSimpleString</a> (std::string_view &amp;MangledName, bool Memorize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ad53863aa95fab722d9979b1b38230e7b">FuncClass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a42cc66467c4539f69406e46a8d5895">demangleFunctionClass</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a1c7534e329bd2e3760c37d8123909e63">CallingConv</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a471b4db3efd5782f0d2fe615e9c7551b">demangleCallingConvention</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ae868dcbebdf0e8890ff2942c9367fa65">StorageClass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac262c5e41f8edcacbd7cd01b21a87e18">demangleVariableStorageClass</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aa95178bf32f58a40bcf2cd203243e5">demangleThrowSpecification</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">wchar_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6942d7137d4504fece8201199b284c4f">demangleWcharLiteral</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fa27c5bba5cb28f963f51884764a419">demangleCharLiteral</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382c">Qualifiers</a>, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad587a39b2912fd5aafa0be8ae98b3672">demangleQualifiers</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3736a2dc172d32fe98674a1fac7ded8">Error</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator">ArenaAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75c7fa522cfe7c3325ec88057e9fbdc2">Arena</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/backrefcontext">BackrefContext</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a885580464d7985942215b1349ffed267">Backrefs</a></td>
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


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>.</p>


<div class="doxySectionDef">

## Friends

### llvm::getArm64ECInsertionPointInMangledName {#a00ab77724bdd2d5f6a3495e69600d3ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend std::optional&lt; size_t &gt; std::string_view MangledName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Demangler() {#a05d787d0b1cc5fee84a59d5297e7bc13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ms_demangle::Demangler::Demangler ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Demangler() {#a942ff5c66c6c2139e0bf561ee8aceb8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::ms_demangle::Demangler::~Demangler ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dumpBackReferences() {#ae64ec0c9c49acf91da4f0c361e7c2a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Demangler::dumpBackReferences ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 2404 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93a1f4a074fef8b57c73c4b2885e1a36b57">llvm::ms_demangle::OF_Default</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### parse() {#a92ceaf0f7302bb57c5c7e1e810c56093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolNode * Demangler::parse (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 846 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp/#ad0d37c2182c5c94ec711cf7e826440f5">consumeFront</a> and <a href="#ac3736a2dc172d32fe98674a1fac7ded8">Error</a>.</p>

</div>
</div>

### parseTagUniqueName() {#a2e7b39f476fe2783df4d468b8103f7c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagTypeNode * Demangler::parseTagUniqueName (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 872 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp/#ad0d37c2182c5c94ec711cf7e826440f5">consumeFront</a> and <a href="#ac3736a2dc172d32fe98674a1fac7ded8">Error</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### copyString() {#a4827ab0143a58397c4d3d8d04c78d47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string_view Demangler::copyString (std::string_view Borrowed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a copy of <span class="doxyComputerOutput">Borrowed</span> into memory that we own.</p>

<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleAnonymousNamespaceName() {#a81b5c1b2ab9d0b0fe6365b67d31b89cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedIdentifierNode * Demangler::demangleAnonymousNamespaceName (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1460 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleArrayType() {#ab3a851148c1a0351e63932a043336098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayTypeNode * Demangler::demangleArrayType (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 2145 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleBackRefName() {#a1ba40d4252bd4a277eb2778b43ff41a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedIdentifierNode * Demangler::demangleBackRefName (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleCallingConvention() {#a471b4db3efd5782f0d2fe615e9c7551b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallingConv Demangler::demangleCallingConvention (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1734 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleCharLiteral() {#a3fa27c5bba5cb28f963f51884764a419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t Demangler::demangleCharLiteral (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1081 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleClassType() {#a2e82baa7e91145b188bf25520d4ef358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagTypeNode * Demangler::demangleClassType (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 2051 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleConversionOperatorIdentifier() {#a32596befbd16a35d41eda63729f8660d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConversionOperatorIdentifierNode * Demangler::demangleConversionOperatorIdentifier (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleCustomType() {#acfc0244bd42ec5853305826f0bfa0594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CustomTypeNode * Demangler::demangleCustomType (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1969 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleDeclarator() {#a3436542f930536fb92f866b588e43e41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolNode * Demangler::demangleDeclarator (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 774 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleEncodedSymbol() {#a0c38c0a2a534b22d347f09158557fa6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolNode * Demangler::demangleEncodedSymbol (std::string_view &amp; MangledName, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/qualifiednamenode">QualifiedNameNode</a> * QN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleFullyQualifiedSymbolName() {#a8937ab6142dee2aeca34c873d8a6049d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QualifiedNameNode * Demangler::demangleFullyQualifiedSymbolName (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1528 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleFullyQualifiedTypeName() {#ab0b21f4fd7312e3be629c2a9606f78ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QualifiedNameNode * Demangler::demangleFullyQualifiedTypeName (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1510 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleFunctionClass() {#a7a42cc66467c4539f69406e46a8d5895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncClass Demangler::demangleFunctionClass (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1646 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleFunctionEncoding() {#a6c3df036838108887d90790cb25810a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSymbolNode * Demangler::demangleFunctionEncoding (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1917 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleFunctionIdentifierCode() {#a93919864728bbb73144fcfe345bd7efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IdentifierNode * Demangler::demangleFunctionIdentifierCode (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleFunctionIdentifierCode() {#a46a701162182ff283e75b0c36462e9bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IdentifierNode * Demangler::demangleFunctionIdentifierCode (std::string_view &amp; MangledName, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a03674045d0444f4d01342d81d202da35">FunctionIdentifierCodeGroup</a> Group)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleFunctionParameterList() {#a6e31150e411b667d7b69175d274c19a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeArrayNode * Demangler::demangleFunctionParameterList (std::string_view &amp; MangledName, bool &amp; IsVariadic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 2191 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleFunctionType() {#aeede616338cc712198e67c2b3cc149de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSignatureNode * Demangler::demangleFunctionType (std::string_view &amp; MangledName, bool HasThisQuals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1890 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleInitFiniStub() {#a05a69023bb3587fbb0e7f300e7acaa5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSymbolNode * Demangler::demangleInitFiniStub (std::string_view &amp; MangledName, bool IsDestructor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleLiteralOperatorIdentifier() {#a40e695ec8fb99816d20039d51845e2ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiteralOperatorIdentifierNode * Demangler::demangleLiteralOperatorIdentifier (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleLocallyScopedNamePiece() {#afed2357f386f4832b3c4837715f03d0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedIdentifierNode * Demangler::demangleLocallyScopedNamePiece (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1478 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleLocalStaticGuard() {#af453af0ef7820d7aba6835e885a08737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocalStaticGuardVariableNode * Demangler::demangleLocalStaticGuard (std::string_view &amp; MangledName, bool IsThread)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleMD5Name() {#aef56414be9f6f3a133c65ddf4dd0fb2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolNode * Demangler::demangleMD5Name (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 798 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleMemberPointerType() {#a16f4886822d556cd3671a665c98f6fd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerTypeNode * Demangler::demangleMemberPointerType (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 2102 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleNameScopeChain() {#ae88af2fb3dda75ad371ca286bd5cc5fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QualifiedNameNode * Demangler::demangleNameScopeChain (std::string_view &amp; MangledName, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/identifiernode">IdentifierNode</a> * UnqualifiedName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1615 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleNameScopePiece() {#a99731c50cb5e44bd044403488c2085d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IdentifierNode * Demangler::demangleNameScopePiece (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1586 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleNumber() {#a65a65044c2b2c0ec5c7e23a5e4b1b840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, bool &gt; Demangler::demangleNumber (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demanglePointerExtQualifiers() {#a1ffd038ea8fef89868021db605f49c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Qualifiers Demangler::demanglePointerExtQualifiers (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 2133 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demanglePointerType() {#a532a0124a64fe3a14cc396f604a14fc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerTypeNode * Demangler::demanglePointerType (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 2083 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demanglePrimitiveType() {#aba044817cd8a07e4de60ff72b5bd0727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PrimitiveTypeNode * Demangler::demanglePrimitiveType (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1984 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleQualifiers() {#ad587a39b2912fd5aafa0be8ae98b3672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Qualifiers, bool &gt; Demangler::demangleQualifiers (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1797 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleRttiBaseClassDescriptorNode() {#aa03d8bb48a96d68f414c1d1c6a0ceaa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariableSymbolNode * Demangler::demangleRttiBaseClassDescriptorNode (<a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator">ArenaAllocator</a> &amp; Arena, std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleSigned() {#aab7db0868aae652606418659050103d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t Demangler::demangleSigned (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 982 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleSimpleName() {#a1486e15a9f326fc7a7175796354ba216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedIdentifierNode * Demangler::demangleSimpleName (std::string_view &amp; MangledName, bool Memorize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1064 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleSimpleString() {#a3868ba864e6433a251151d8526bf60ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string_view Demangler::demangleSimpleString (std::string_view &amp; MangledName, bool Memorize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1439 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleSpecialIntrinsic() {#af144a40c65febae2e165409e0d3b7748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolNode * Demangler::demangleSpecialIntrinsic (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleSpecialTableSymbolNode() {#a7ae0ef7492c1bdab2a324d2643549886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecialTableSymbolNode * Demangler::demangleSpecialTableSymbolNode (std::string_view &amp; MangledName, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ae4a66b98c39e5894dd537b3fbc724739">SpecialIntrinsicKind</a> SIK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleStringLiteral() {#a5ec14a3a00ee57d6f2b8929788c46486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EncodedStringLiteralNode * Demangler::demangleStringLiteral (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1326 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleStructorIdentifier() {#af318197b0d2fc44fc4ab93dc278b54d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructorIdentifierNode * Demangler::demangleStructorIdentifier (std::string_view &amp; MangledName, bool IsDestructor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleTemplateInstantiationName() {#a6d9813b44f6e03a33e7221387c2b609a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IdentifierNode * Demangler::demangleTemplateInstantiationName (std::string_view &amp; MangledName, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ab932b4e3b27a81db21a963a06da55f1f">NameBackrefBehavior</a> NBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1030 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleTemplateParameterList() {#abec3a611da83a8af35d770c8c2f646bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeArrayNode * Demangler::demangleTemplateParameterList (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 2257 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleThrowSpecification() {#a8aa95178bf32f58a40bcf2cd203243e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Demangler::demangleThrowSpecification (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1879 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleType() {#a28cb13333ecdb95b9e0f1d5f3f158e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeNode * Demangler::demangleType (std::string_view &amp; MangledName, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#afb795990ffc0cb7321e7d1eacc246324">QualifierMangleMode</a> QMM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1831 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleTypeinfoName() {#a2785c9875cdb4334ffe16ec8502c7a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolNode * Demangler::demangleTypeinfoName (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleUnqualifiedSymbolName() {#a5529cc2067df0861226a5731deb79461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IdentifierNode * Demangler::demangleUnqualifiedSymbolName (std::string_view &amp; MangledName, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ab932b4e3b27a81db21a963a06da55f1f">NameBackrefBehavior</a> NBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1574 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleUnqualifiedTypeName() {#a531b60e714d5e2b04392bc9e32b94df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IdentifierNode * Demangler::demangleUnqualifiedTypeName (std::string_view &amp; MangledName, bool Memorize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1558 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleUnsigned() {#a096d07aabbdafabe85eae35b8212aef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Demangler::demangleUnsigned (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleUntypedVariable() {#a4c3739c318914517497c3803f1df0edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariableSymbolNode * Demangler::demangleUntypedVariable (<a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator">ArenaAllocator</a> &amp; Arena, std::string_view &amp; MangledName, std::string_view VariableName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleVariableEncoding() {#a24a031df90ac78bddee3abdb9e689417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariableSymbolNode * Demangler::demangleVariableEncoding (std::string_view &amp; MangledName, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ae868dcbebdf0e8890ff2942c9367fa65">StorageClass</a> SC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 894 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleVariableStorageClass() {#ac262c5e41f8edcacbd7cd01b21a87e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StorageClass Demangler::demangleVariableStorageClass (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1776 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleVcallThunkNode() {#ac05d8fd7300da96c1b573305ea98c00a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSymbolNode * Demangler::demangleVcallThunkNode (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1307 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### demangleWcharLiteral() {#a6942d7137d4504fece8201199b284c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wchar_t Demangler::demangleWcharLiteral (std::string_view &amp; MangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1139 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### memorizeIdentifier() {#afbc2e6fe3a86150cdb6803db96a2c63a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Demangler::memorizeIdentifier (<a href="/web-llvm/docs/api/structs/llvm/ms-demangle/identifiernode">IdentifierNode</a> * Identifier)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 1019 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### memorizeString() {#a31b6cdad234fe05af48ebd489e83e05b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Demangler::memorizeString (std::string_view s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### translateIntrinsicFunctionCode() {#a2975159a91e9de03a192267601f26971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrinsicFunctionKind Demangler::translateIntrinsicFunctionCode (char CH, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a03674045d0444f4d01342d81d202da35">FunctionIdentifierCodeGroup</a> Group)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>, definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Error {#ac3736a2dc172d32fe98674a1fac7ded8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ms_demangle::Demangler::Error = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>.</p>


<p>Referenced by <a href="#a92ceaf0f7302bb57c5c7e1e810c56093">parse</a> and <a href="#a2e7b39f476fe2783df4d468b8103f7c7">parseTagUniqueName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Arena {#a75c7fa522cfe7c3325ec88057e9fbdc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArenaAllocator llvm::ms_demangle::Demangler::Arena</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>.</p>

</div>
</div>

### Backrefs {#a885580464d7985942215b1349ffed267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BackrefContext llvm::ms_demangle::Demangler::Backrefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">MicrosoftDemangle.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
