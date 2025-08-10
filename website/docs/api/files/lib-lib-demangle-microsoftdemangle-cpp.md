---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/demangle/microsoftdemangle-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MicrosoftDemangle.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemangle-h">llvm/Demangle/MicrosoftDemangle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">llvm/Demangle/Demangle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">llvm/Demangle/DemangleConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">llvm/Demangle/MicrosoftDemangleNodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/stringviewextras-h">llvm/Demangle/StringViewExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/utility-h">llvm/Demangle/Utility.h</a>"
#include &lt;array&gt;
#include &lt;cctype&gt;
#include &lt;cstdio&gt;
#include &lt;optional&gt;
#include &lt;string_view&gt;
#include &lt;tuple&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/nodelist">NodeList</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22a8917194cf1d8c24fea4ec52ab5921">startsWithDigit</a> (std::string_view S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0d37c2182c5c94ec711cf7e826440f5">consumeFront</a> (std::string_view &amp;S, char C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42cd951a260ddc5341a3d35687547f82">consumeFront</a> (std::string_view &amp;S, std::string_view C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefa57717c8f3304e782a6d2973171ea7">consumeFront</a> (std::string_view &amp;S, std::string_view PrefixA, std::string_view PrefixB, bool A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace07c87bbcd4496364846aa8ea29f14e">startsWith</a> (std::string_view S, std::string_view PrefixA, std::string_view PrefixB, bool A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f55b36df4657b04741a7e100eb46f2">isMemberPointer</a> (std::string_view MangledName, bool &amp;Error)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ae4a66b98c39e5894dd537b3fbc724739">SpecialIntrinsicKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b5bac976eaae0f97d4abb7d9fa5130">consumeSpecialIntrinsicKind</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0198b8a6177ee0ed3f77576d720fe38a">startsWithLocalScopePattern</a> (std::string_view S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd4699271bdd50ac2e815a0e67404d7">isTagType</a> (std::string_view S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44c6247169b891828cd88cb0fce681ca">isCustomType</a> (std::string_view S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad969d950c5a9547d63f34890687e7231">isPointerType</a> (std::string_view S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c93f33103cc7dda0f7d310e301a238e">isArrayType</a> (std::string_view S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad91c40c1a68beb7a510c6dd333c7d214">isFunctionType</a> (std::string_view S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9ed9d6a8eaf456e0e58e3304c3d32715">FunctionRefQualifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c0e936ae7540e6a9615b47189ef424">demangleFunctionRefQualifier</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7">Qualifiers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a581dcb7e3f0fe7dc1ab999d965f2af26">PointerAffinity</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7156a5e97f96a62c5eb20e59020dd645">demanglePointerCVQualifiers</a> (std::string_view &amp;MangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/namedidentifiernode">NamedIdentifierNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd139b7bb0b2745ca39c9b428c9ea095">synthesizeNamedIdentifier</a> (ArenaAllocator &amp;Arena, std::string_view Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/qualifiednamenode">QualifiedNameNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3565206476a63db11372b5026c8aa36b">synthesizeQualifiedName</a> (ArenaAllocator &amp;Arena, IdentifierNode *Identifier)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/qualifiednamenode">QualifiedNameNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acea8b7c1fd8914eb9dea2cf614644dcc">synthesizeQualifiedName</a> (ArenaAllocator &amp;Arena, std::string_view Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/variablesymbolnode">VariableSymbolNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a26224ab7a8b8ee812dc3c65f6a914">synthesizeVariable</a> (ArenaAllocator &amp;Arena, TypeNode *Type, std::string_view VariableName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ee3dbc9e4c1c8f7df2b612071336a4">isRebasedHexDigit</a> (char C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab229a2e4c5d284d168789f0a7e417fd0">rebasedHexDigitToNumber</a> (char C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96f3b0d392f346c887ecc66c2695e380">writeHexDigit</a> (char *Buffer, uint8_t Digit)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5de416b84368aa88d67b14e4663e6006">outputHex</a> (OutputBuffer &amp;OB, unsigned C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4031afe383e46383b1bc5cce9e9c0e28">outputEscapedChar</a> (OutputBuffer &amp;OB, unsigned C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2bbbc211e4987b9ef5a0f1737fc262d">countTrailingNullBytes</a> (const uint8_t *StringBytes, int Length)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e16bdee4da65616620334e3cc25ae85">countEmbeddedNulls</a> (const uint8_t *StringBytes, unsigned Length)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0053b0368c4b20d378ba4db4edf9586">guessCharByteSize</a> (const uint8_t *StringBytes, unsigned NumChars, uint64_t NumBytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954f18c9d134adfec5ed0f8a45d1e2da">decodeMultiByteChar</a> (const uint8_t *StringBytes, unsigned CharIndex, unsigned CharBytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/nodearraynode">NodeArrayNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa68e4ee3a5ef683a4cab2799aad55e04">nodeListToNodeArray</a> (ArenaAllocator &amp;Arena, NodeList *Head, size_t Count)</td>
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

### consumeFront() {#ad0d37c2182c5c94ec711cf7e826440f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool consumeFront (std::string_view &amp; S, char C)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#aefa57717c8f3304e782a6d2973171ea7">consumeFront</a>, <a href="#ae7b5bac976eaae0f97d4abb7d9fa5130">consumeSpecialIntrinsicKind</a>, <a href="#aa5c0e936ae7540e6a9615b47189ef424">demangleFunctionRefQualifier</a>, <a href="#a7156a5e97f96a62c5eb20e59020dd645">demanglePointerCVQualifiers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e1da6c34a3216e370efab344977e0d7">llvm::getArm64ECInsertionPointInMangledName</a>, <a href="#a84f55b36df4657b04741a7e100eb46f2">isMemberPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/ms-demangle/demangler/#a92ceaf0f7302bb57c5c7e1e810c56093">llvm::ms_demangle::Demangler::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/ms-demangle/demangler/#a2e7b39f476fe2783df4d468b8103f7c7">llvm::ms_demangle::Demangler::parseTagUniqueName</a> and <a href="#a0198b8a6177ee0ed3f77576d720fe38a">startsWithLocalScopePattern</a>.</p>

</div>
</div>

### consumeFront() {#a42cd951a260ddc5341a3d35687547f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool consumeFront (std::string_view &amp; S, std::string_view C)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### consumeFront() {#aefa57717c8f3304e782a6d2973171ea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool consumeFront (std::string_view &amp; S, std::string_view PrefixA, std::string_view PrefixB, bool A)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#ad0d37c2182c5c94ec711cf7e826440f5">consumeFront</a>.</p>

</div>
</div>

### consumeSpecialIntrinsicKind() {#ae7b5bac976eaae0f97d4abb7d9fa5130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecialIntrinsicKind consumeSpecialIntrinsicKind (std::string_view &amp; MangledName)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>Reference <a href="#ad0d37c2182c5c94ec711cf7e826440f5">consumeFront</a>.</p>

</div>
</div>

### countEmbeddedNulls() {#a0e16bdee4da65616620334e3cc25ae85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned countEmbeddedNulls (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * StringBytes, unsigned Length)</td>
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



<p>Definition at line 1246 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#afb795990ffc0cb7321e7d1eacc246324a8eea62084ca7e541d918e823422bd82e">llvm::ms_demangle::Result</a>.</p>


<p>Referenced by <a href="#ae0053b0368c4b20d378ba4db4edf9586">guessCharByteSize</a>.</p>

</div>
</div>

### countTrailingNullBytes() {#ac2bbbc211e4987b9ef5a0f1737fc262d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned countTrailingNullBytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * StringBytes, int Length)</td>
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



<p>Definition at line 1235 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>


<p>Referenced by <a href="#ae0053b0368c4b20d378ba4db4edf9586">guessCharByteSize</a>.</p>

</div>
</div>

### decodeMultiByteChar() {#a954f18c9d134adfec5ed0f8a45d1e2da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned decodeMultiByteChar (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * StringBytes, unsigned CharIndex, unsigned CharBytes)</td>
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



<p>Definition at line 1293 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#afb795990ffc0cb7321e7d1eacc246324a8eea62084ca7e541d918e823422bd82e">llvm::ms_demangle::Result</a>.</p>

</div>
</div>

### demangleFunctionRefQualifier() {#aa5c0e936ae7540e6a9615b47189ef424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionRefQualifier demangleFunctionRefQualifier (std::string_view &amp; MangledName)</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>Reference <a href="#ad0d37c2182c5c94ec711cf7e826440f5">consumeFront</a>.</p>

</div>
</div>

### demanglePointerCVQualifiers() {#a7156a5e97f96a62c5eb20e59020dd645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Qualifiers, PointerAffinity &gt; demanglePointerCVQualifiers (std::string_view &amp; MangledName)</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="#ad0d37c2182c5c94ec711cf7e826440f5">consumeFront</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h/#ae4a4b6b609be6808e094304ae8d981f7">DEMANGLE_UNREACHABLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382caf3ee231db3c8da035f488a9c171b8fb4">llvm::ms_demangle::Q_Const</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382ca2b725449feac20f84854006281d4bd2d">llvm::ms_demangle::Q_None</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382ca6d31ffab721f34ac0f0be44421edc31b">llvm::ms_demangle::Q_Volatile</a>.</p>

</div>
</div>

### guessCharByteSize() {#ae0053b0368c4b20d378ba4db4edf9586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned guessCharByteSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * StringBytes, unsigned NumChars, uint64_t NumBytes)</td>
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



<p>Definition at line 1259 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0e16bdee4da65616620334e3cc25ae85">countEmbeddedNulls</a> and <a href="#ac2bbbc211e4987b9ef5a0f1737fc262d">countTrailingNullBytes</a>.</p>

</div>
</div>

### isArrayType() {#a0c93f33103cc7dda0f7d310e301a238e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isArrayType (std::string_view S)</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### isCustomType() {#a44c6247169b891828cd88cb0fce681ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCustomType (std::string_view S)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### isFunctionType() {#ad91c40c1a68beb7a510c6dd333c7d214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFunctionType (std::string_view S)</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### isMemberPointer() {#a84f55b36df4657b04741a7e100eb46f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isMemberPointer (std::string_view MangledName, bool &amp; Error)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="#ad0d37c2182c5c94ec711cf7e826440f5">consumeFront</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h/#ae4a4b6b609be6808e094304ae8d981f7">DEMANGLE_UNREACHABLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a22a8917194cf1d8c24fea4ec52ab5921">startsWithDigit</a>.</p>

</div>
</div>

### isPointerType() {#ad969d950c5a9547d63f34890687e7231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isPointerType (std::string_view S)</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### isRebasedHexDigit() {#aa5ee3dbc9e4c1c8f7df2b612071336a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRebasedHexDigit (char C)</td>
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



<p>Definition at line 1074 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#ab229a2e4c5d284d168789f0a7e417fd0">rebasedHexDigitToNumber</a>.</p>

</div>
</div>

### isTagType() {#afbd4699271bdd50ac2e815a0e67404d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isTagType (std::string_view S)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>

</div>
</div>

### nodeListToNodeArray() {#aa68e4ee3a5ef683a4cab2799aad55e04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeArrayNode * nodeListToNodeArray (<a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator">ArenaAllocator</a> &amp; Arena, <a href="/web-llvm/docs/api/structs/nodelist">NodeList</a> * Head, size_t Count)</td>
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



<p>Definition at line 1602 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator/#a68c5ae418fcf0a7ea3873c534821889e">llvm::ms_demangle::ArenaAllocator::alloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator/#add7764f5fc091f27879341e17684b9ed">llvm::ms_demangle::ArenaAllocator::allocArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/structs/nodelist/#a05622943acd03b46a52dd9938ecb5937">NodeList::N</a> and <a href="/web-llvm/docs/api/structs/nodelist/#ab6f2d6b8d8b536bb62278d1320cedfe2">NodeList::Next</a>.</p>

</div>
</div>

### outputEscapedChar() {#a4031afe383e46383b1bc5cce9e9c0e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void outputEscapedChar (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, unsigned C)</td>
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



<p>Definition at line 1187 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a5de416b84368aa88d67b14e4663e6006">outputHex</a>.</p>

</div>
</div>

### outputHex() {#a5de416b84368aa88d67b14e4663e6006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void outputHex (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, unsigned C)</td>
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



<p>Definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a96f3b0d392f346c887ecc66c2695e380">writeHexDigit</a>.</p>


<p>Referenced by <a href="#a4031afe383e46383b1bc5cce9e9c0e28">outputEscapedChar</a>.</p>

</div>
</div>

### rebasedHexDigitToNumber() {#ab229a2e4c5d284d168789f0a7e417fd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t rebasedHexDigitToNumber (char C)</td>
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



<p>Definition at line 1076 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#aa5ee3dbc9e4c1c8f7df2b612071336a4">isRebasedHexDigit</a>.</p>

</div>
</div>

### startsWith() {#ace07c87bbcd4496364846aa8ea29f14e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool startsWith (std::string_view S, std::string_view PrefixA, std::string_view PrefixB, bool A)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

### startsWithDigit() {#a22a8917194cf1d8c24fea4ec52ab5921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool startsWithDigit (std::string_view S)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>Referenced by <a href="#a84f55b36df4657b04741a7e100eb46f2">isMemberPointer</a>.</p>

</div>
</div>

### startsWithLocalScopePattern() {#a0198b8a6177ee0ed3f77576d720fe38a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool startsWithLocalScopePattern (std::string_view S)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>Reference <a href="#ad0d37c2182c5c94ec711cf7e826440f5">consumeFront</a>.</p>

</div>
</div>

### synthesizeNamedIdentifier() {#acd139b7bb0b2745ca39c9b428c9ea095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedIdentifierNode * synthesizeNamedIdentifier (<a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator">ArenaAllocator</a> &amp; Arena, std::string_view Name)</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator/#a68c5ae418fcf0a7ea3873c534821889e">llvm::ms_demangle::ArenaAllocator::alloc</a>.</p>


<p>Referenced by <a href="#acea8b7c1fd8914eb9dea2cf614644dcc">synthesizeQualifiedName</a>.</p>

</div>
</div>

### synthesizeQualifiedName() {#a3565206476a63db11372b5026c8aa36b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QualifiedNameNode * synthesizeQualifiedName (<a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator">ArenaAllocator</a> &amp; Arena, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/identifiernode">IdentifierNode</a> * Identifier)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator/#a68c5ae418fcf0a7ea3873c534821889e">llvm::ms_demangle::ArenaAllocator::alloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator/#add7764f5fc091f27879341e17684b9ed">llvm::ms_demangle::ArenaAllocator::allocArray</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/qualifiednamenode/#af88db6a51a5b059c8dcd153723e1f267">llvm::ms_demangle::QualifiedNameNode::Components</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/nodearraynode/#a1cc8362a39aaa446752ba45479170809">llvm::ms_demangle::NodeArrayNode::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a234f091f9559c82176ae3e89447add46a29ee5d1ebcc033234938a5234f1f2075">llvm::ms_demangle::Identifier</a> and <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/nodearraynode/#ab8e32cdeda1d9ca1fa7498abab41c01d">llvm::ms_demangle::NodeArrayNode::Nodes</a>.</p>


<p>Referenced by <a href="#acea8b7c1fd8914eb9dea2cf614644dcc">synthesizeQualifiedName</a> and <a href="#a89a26224ab7a8b8ee812dc3c65f6a914">synthesizeVariable</a>.</p>

</div>
</div>

### synthesizeQualifiedName() {#acea8b7c1fd8914eb9dea2cf614644dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QualifiedNameNode * synthesizeQualifiedName (<a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator">ArenaAllocator</a> &amp; Arena, std::string_view Name)</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="#acd139b7bb0b2745ca39c9b428c9ea095">synthesizeNamedIdentifier</a> and <a href="#a3565206476a63db11372b5026c8aa36b">synthesizeQualifiedName</a>.</p>

</div>
</div>

### synthesizeVariable() {#a89a26224ab7a8b8ee812dc3c65f6a914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariableSymbolNode * synthesizeVariable (<a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator">ArenaAllocator</a> &amp; Arena, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode">TypeNode</a> * Type, std::string_view VariableName)</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ms-demangle/arenaallocator/#a68c5ae418fcf0a7ea3873c534821889e">llvm::ms_demangle::ArenaAllocator::alloc</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/symbolnode/#aa1d11772833419f459f5036c8f6ec09a">llvm::ms_demangle::SymbolNode::Name</a>, <a href="#a3565206476a63db11372b5026c8aa36b">synthesizeQualifiedName</a> and <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/variablesymbolnode/#ad1d792f8b908621f2084554e394a9ac4">llvm::ms_demangle::VariableSymbolNode::Type</a>.</p>

</div>
</div>

### writeHexDigit() {#a96f3b0d392f346c887ecc66c2695e380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeHexDigit (char * Buffer, uint8_t Digit)</td>
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



<p>Definition at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp">MicrosoftDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a5de416b84368aa88d67b14e4663e6006">outputHex</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
