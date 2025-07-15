---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ms-demangle/functionsignaturenode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FunctionSignatureNode` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::ms_demangle::FunctionSignatureNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">llvm/Demangle/MicrosoftDemangleNodes.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode">TypeNode</a></td>
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

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ms-demangle/thunksignaturenode">ThunkSignatureNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38094b555afcf9438b21f5df8ec25510">FunctionSignatureNode</a> (NodeKind K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa171496dc9a874500ce22732ebb5e78f">FunctionSignatureNode</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07ccd063ae170622a6af1ff591868c24">outputPre</a> (OutputBuffer &amp;OB, OutputFlags Flags) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbff64cf38f1b0e11452026e97a7af08">outputPost</a> (OutputBuffer &amp;OB, OutputFlags Flags) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a581dcb7e3f0fe7dc1ab999d965f2af26">PointerAffinity</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad72d4f98f791e8a796d742f40ace9127">Affinity</a> = <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a581dcb7e3f0fe7dc1ab999d965f2af26a6adf97f83acf6453d4a6a4b1070f3754">PointerAffinity::None</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af345ae8cf3d9d55bd40b73141bad8bad">CallConvention</a> = <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a1c7534e329bd2e3760c37d8123909e63a6adf97f83acf6453d4a6a4b1070f3754">CallingConv::None</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f6393713c9b2fad0529c17161c44bc">FunctionClass</a> = <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ad53863aa95fab722d9979b1b38230e7ba280dfbc39e758cbd4fbf94014abf9209">FC_Global</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9ed9d6a8eaf456e0e58e3304c3d32715">FunctionRefQualifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea8e26704f6fa81a8201fa594d246cb5">RefQualifier</a> = <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9ed9d6a8eaf456e0e58e3304c3d32715a6adf97f83acf6453d4a6a4b1070f3754">FunctionRefQualifier::None</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a796c653e2c31156846015a90a0f053cf">ReturnType</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cafa8bca825480b1d2a4c893a7dd506">IsVariadic</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74812d4bb33eb04fc09d7348cb9b25ea">Params</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5fd0a955620ac5a1d85d58bee9e986c">IsNoexcept</a> = false</td>
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


<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionSignatureNode() {#a38094b555afcf9438b21f5df8ec25510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ms_demangle::FunctionSignatureNode::FunctionSignatureNode (<a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a234f091f9559c82176ae3e89447add46">NodeKind</a> K)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode/#a4c498ca8535b565f0cd03672c7f4a55a">llvm::ms_demangle::TypeNode::TypeNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/thunksignaturenode/#aafb952107010c05f69dfc750a42a15c4">llvm::ms_demangle::ThunkSignatureNode::ThunkSignatureNode</a>.</p>

</div>
</div>

### FunctionSignatureNode() {#aa171496dc9a874500ce22732ebb5e78f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ms_demangle::FunctionSignatureNode::FunctionSignatureNode ()</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a234f091f9559c82176ae3e89447add46aa238297af6fa869d4317808ad411b476">llvm::ms_demangle::FunctionSignature</a> and <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode/#a4c498ca8535b565f0cd03672c7f4a55a">llvm::ms_demangle::TypeNode::TypeNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### outputPost() {#acbff64cf38f1b0e11452026e97a7af08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionSignatureNode::outputPost (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93">OutputFlags</a> Flags)</td>
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



<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>, definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ad53863aa95fab722d9979b1b38230e7ba058fded85e073e346582d404697b15f5">llvm::ms_demangle::FC_NoParameterList</a>, <a href="#a53f6393713c9b2fad0529c17161c44bc">FunctionClass</a>, <a href="#aa5fd0a955620ac5a1d85d58bee9e986c">IsNoexcept</a>, <a href="#a7cafa8bca825480b1d2a4c893a7dd506">IsVariadic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93ab32bae4a153de55def56edfbc6455e26">llvm::ms_demangle::OF_NoReturnType</a>, <a href="#a74812d4bb33eb04fc09d7348cb9b25ea">Params</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382caf3ee231db3c8da035f488a9c171b8fb4">llvm::ms_demangle::Q_Const</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382ca73dea877c928d81fd3074a2084ba6eab">llvm::ms_demangle::Q_Restrict</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382ca198cb1c3c5c899ac467fd758a9c2630d">llvm::ms_demangle::Q_Unaligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382ca6d31ffab721f34ac0f0be44421edc31b">llvm::ms_demangle::Q_Volatile</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/typenode/#a52b0ebeb73b31f45a974e773d1d872ec">llvm::ms_demangle::TypeNode::Quals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9ed9d6a8eaf456e0e58e3304c3d32715a63d5049791d9d79d86e9a108b0a999ca">llvm::ms_demangle::Reference</a>, <a href="#aea8e26704f6fa81a8201fa594d246cb5">RefQualifier</a>, <a href="#a796c653e2c31156846015a90a0f053cf">ReturnType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9ed9d6a8eaf456e0e58e3304c3d32715aa68a3262ced5b445f2a5a1953c279116">llvm::ms_demangle::RValueReference</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/thunksignaturenode/#a15c795f45c65d4112db00a4281798f9d">llvm::ms_demangle::ThunkSignatureNode::outputPost</a>.</p>

</div>
</div>

### outputPre() {#a07ccd063ae170622a6af1ff591868c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionSignatureNode::outputPre (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93">OutputFlags</a> Flags)</td>
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



<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>, definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a>.</p>


<p>References <a href="#af345ae8cf3d9d55bd40b73141bad8bad">CallConvention</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ad53863aa95fab722d9979b1b38230e7ba091b1b87ad7595a450478e003cfaf4c0">llvm::ms_demangle::FC_ExternC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ad53863aa95fab722d9979b1b38230e7ba280dfbc39e758cbd4fbf94014abf9209">llvm::ms_demangle::FC_Global</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ad53863aa95fab722d9979b1b38230e7ba8dfb9a91569aa3ca059b2c40375b6070">llvm::ms_demangle::FC_Private</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ad53863aa95fab722d9979b1b38230e7ba1dea526d842543c87c5ec8fdadfc3159">llvm::ms_demangle::FC_Protected</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ad53863aa95fab722d9979b1b38230e7ba94bdf4f3a796125f1c6ca8f0e7a08f20">llvm::ms_demangle::FC_Public</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ad53863aa95fab722d9979b1b38230e7bae363aabcf275eb9edd6c1dc60c8aa9a5">llvm::ms_demangle::FC_Static</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ad53863aa95fab722d9979b1b38230e7ba2f1bba27b60f92aa80cb6ab2f8c61985">llvm::ms_demangle::FC_Virtual</a>, <a href="#a53f6393713c9b2fad0529c17161c44bc">FunctionClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93abd6b95929d313941c4b155813f5f2036">llvm::ms_demangle::OF_NoAccessSpecifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93a5d9fdd8676f8e6f6ceb39ee2032d5ff5">llvm::ms_demangle::OF_NoCallingConvention</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93a49a7c7c80e21a978215e25f1941046bc">llvm::ms_demangle::OF_NoMemberType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9e06032afffbcfd197a80acc92afce93ab32bae4a153de55def56edfbc6455e26">llvm::ms_demangle::OF_NoReturnType</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp/#a141bc818a0114d9c6f5a81666e56dede">outputCallingConvention</a> and <a href="#a796c653e2c31156846015a90a0f053cf">ReturnType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/pointertypenode/#acd7b41bd8a19c92e657a2782d37bc2f2">llvm::ms_demangle::PointerTypeNode::outputPre</a> and <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/thunksignaturenode/#a328bc216e8ea355d57fd7ff5fc69a74a">llvm::ms_demangle::ThunkSignatureNode::outputPre</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Affinity {#ad72d4f98f791e8a796d742f40ace9127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerAffinity llvm::ms_demangle::FunctionSignatureNode::Affinity = <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a581dcb7e3f0fe7dc1ab999d965f2af26a6adf97f83acf6453d4a6a4b1070f3754">PointerAffinity::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>

</div>
</div>

### CallConvention {#af345ae8cf3d9d55bd40b73141bad8bad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallingConv llvm::ms_demangle::FunctionSignatureNode::CallConvention = <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a1c7534e329bd2e3760c37d8123909e63a6adf97f83acf6453d4a6a4b1070f3754">CallingConv::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#a07ccd063ae170622a6af1ff591868c24">outputPre</a> and <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/pointertypenode/#acd7b41bd8a19c92e657a2782d37bc2f2">llvm::ms_demangle::PointerTypeNode::outputPre</a>.</p>

</div>
</div>

### FunctionClass {#a53f6393713c9b2fad0529c17161c44bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncClass llvm::ms_demangle::FunctionSignatureNode::FunctionClass = <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#ad53863aa95fab722d9979b1b38230e7ba280dfbc39e758cbd4fbf94014abf9209">FC_Global</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#acbff64cf38f1b0e11452026e97a7af08">outputPost</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/thunksignaturenode/#a15c795f45c65d4112db00a4281798f9d">llvm::ms_demangle::ThunkSignatureNode::outputPost</a> and <a href="#a07ccd063ae170622a6af1ff591868c24">outputPre</a>.</p>

</div>
</div>

### IsNoexcept {#aa5fd0a955620ac5a1d85d58bee9e986c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ms_demangle::FunctionSignatureNode::IsNoexcept = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#acbff64cf38f1b0e11452026e97a7af08">outputPost</a>.</p>

</div>
</div>

### IsVariadic {#a7cafa8bca825480b1d2a4c893a7dd506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ms_demangle::FunctionSignatureNode::IsVariadic = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#acbff64cf38f1b0e11452026e97a7af08">outputPost</a>.</p>

</div>
</div>

### Params {#a74812d4bb33eb04fc09d7348cb9b25ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeArrayNode* llvm::ms_demangle::FunctionSignatureNode::Params = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#acbff64cf38f1b0e11452026e97a7af08">outputPost</a>.</p>

</div>
</div>

### RefQualifier {#aea8e26704f6fa81a8201fa594d246cb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionRefQualifier llvm::ms_demangle::FunctionSignatureNode::RefQualifier = <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a9ed9d6a8eaf456e0e58e3304c3d32715a6adf97f83acf6453d4a6a4b1070f3754">FunctionRefQualifier::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#acbff64cf38f1b0e11452026e97a7af08">outputPost</a>.</p>

</div>
</div>

### ReturnType {#a796c653e2c31156846015a90a0f053cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeNode* llvm::ms_demangle::FunctionSignatureNode::ReturnType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a>.</p>


<p>Referenced by <a href="#acbff64cf38f1b0e11452026e97a7af08">outputPost</a> and <a href="#a07ccd063ae170622a6af1ff591868c24">outputPre</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">MicrosoftDemangleNodes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
