---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/demangle/microsoftdemanglenodes-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MicrosoftDemangleNodes.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/microsoftdemanglenodes-h">llvm/Demangle/MicrosoftDemangleNodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/utility-h">llvm/Demangle/Utility.h</a>"
#include &lt;cctype&gt;
#include &lt;string&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf65acd60cfe638347e29d174d4b5c77">outputSpaceIfNecessary</a> (OutputBuffer &amp;OB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd46f0ede0fbd766a09fae94b5d046d">outputSingleQualifier</a> (OutputBuffer &amp;OB, Qualifiers Q)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71cadf8f9bc797657ee6080d1da9f21e">outputQualifierIfPresent</a> (OutputBuffer &amp;OB, Qualifiers Q, Qualifiers Mask, bool NeedSpace)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e879fc145b1a29b5e6e304b32bc4848">outputQualifiers</a> (OutputBuffer &amp;OB, Qualifiers Q, bool SpaceBefore, bool SpaceAfter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a141bc818a0114d9c6f5a81666e56dede">outputCallingConvention</a> (OutputBuffer &amp;OB, CallingConv CC)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a466fa40be0d81cf6c0c12d5402439b91">OUTPUT_ENUM_CLASS_VALUE</a>(Enum, Value, Desc)&nbsp;&nbsp;&nbsp;...</td>
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

### outputCallingConvention() {#a141bc818a0114d9c6f5a81666e56dede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void outputCallingConvention (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a1c7534e329bd2e3760c37d8123909e63">CallingConv</a> CC)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#adf65acd60cfe638347e29d174d4b5c77">outputSpaceIfNecessary</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca2740493172a4ce246941c8cff95e0f83">llvm::CallingConv::Swift</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/functionsignaturenode/#a07ccd063ae170622a6af1ff591868c24">llvm::ms_demangle::FunctionSignatureNode::outputPre</a> and <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/pointertypenode/#acd7b41bd8a19c92e657a2782d37bc2f2">llvm::ms_demangle::PointerTypeNode::outputPre</a>.</p>

</div>
</div>

### outputQualifierIfPresent() {#a71cadf8f9bc797657ee6080d1da9f21e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool outputQualifierIfPresent (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7">Qualifiers</a> Q, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7">Qualifiers</a> Mask, bool NeedSpace)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a>.</p>


<p>Reference <a href="#a6fd46f0ede0fbd766a09fae94b5d046d">outputSingleQualifier</a>.</p>


<p>Referenced by <a href="#a9e879fc145b1a29b5e6e304b32bc4848">outputQualifiers</a>.</p>

</div>
</div>

### outputQualifiers() {#a9e879fc145b1a29b5e6e304b32bc4848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void outputQualifiers (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7">Qualifiers</a> Q, bool SpaceBefore, bool SpaceAfter)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a>.</p>


<p>References <a href="#a71cadf8f9bc797657ee6080d1da9f21e">outputQualifierIfPresent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382caf3ee231db3c8da035f488a9c171b8fb4">llvm::ms_demangle::Q_Const</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382ca2b725449feac20f84854006281d4bd2d">llvm::ms_demangle::Q_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382ca73dea877c928d81fd3074a2084ba6eab">llvm::ms_demangle::Q_Restrict</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382ca6d31ffab721f34ac0f0be44421edc31b">llvm::ms_demangle::Q_Volatile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/specialtablesymbolnode/#ab0dd98430680b2d81c821e69c0b7ba0b">llvm::ms_demangle::SpecialTableSymbolNode::output</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/arraytypenode/#adb561cd6826e27947db2c1b98fdd2752">llvm::ms_demangle::ArrayTypeNode::outputPre</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/pointertypenode/#acd7b41bd8a19c92e657a2782d37bc2f2">llvm::ms_demangle::PointerTypeNode::outputPre</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/primitivetypenode/#a88fdf21e5fba4ee1f1e45d5fbd5decda">llvm::ms_demangle::PrimitiveTypeNode::outputPre</a> and <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/tagtypenode/#ad705bfae4de090c2ed75411366c492e4">llvm::ms_demangle::TagTypeNode::outputPre</a>.</p>

</div>
</div>

### outputSingleQualifier() {#a6fd46f0ede0fbd766a09fae94b5d046d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void outputSingleQualifier (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7">Qualifiers</a> Q)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382caf3ee231db3c8da035f488a9c171b8fb4">llvm::ms_demangle::Q_Const</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382ca73dea877c928d81fd3074a2084ba6eab">llvm::ms_demangle::Q_Restrict</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#a763fe714f87aa4f54dfa246ab2cc382ca6d31ffab721f34ac0f0be44421edc31b">llvm::ms_demangle::Q_Volatile</a>.</p>


<p>Referenced by <a href="#a71cadf8f9bc797657ee6080d1da9f21e">outputQualifierIfPresent</a>.</p>

</div>
</div>

### outputSpaceIfNecessary() {#adf65acd60cfe638347e29d174d4b5c77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void outputSpaceIfNecessary (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; OB)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/functionsymbolnode/#aa972e46b2d6b7dd38b1baa74877c6b71">llvm::ms_demangle::FunctionSymbolNode::output</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/variablesymbolnode/#a085968880d0919fcc24fde0651973144">llvm::ms_demangle::VariableSymbolNode::output</a>, <a href="#a141bc818a0114d9c6f5a81666e56dede">outputCallingConvention</a> and <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/pointertypenode/#acd7b41bd8a19c92e657a2782d37bc2f2">llvm::ms_demangle::PointerTypeNode::outputPre</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### OUTPUT\_ENUM\_CLASS\_VALUE {#a466fa40be0d81cf6c0c12d5402439b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OUTPUT_ENUM_CLASS_VALUE(Enum, Value, Desc)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case Enum::Value:                                                            \
    OB &lt;&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a4de98a9acffcef5bb4b31862cb8c72ac">Desc</a>;                                                                \
    <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp/#a91cf6fbebedd86150a36e5ac3d5d3bfc">break</a>;
</div>
</dd>
</dl>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemanglenodes-cpp">MicrosoftDemangleNodes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/intrinsicfunctionidentifiernode/#a83bd8188b45a397822081023a2a88d34">llvm::ms_demangle::IntrinsicFunctionIdentifierNode::output</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/primitivetypenode/#a88fdf21e5fba4ee1f1e45d5fbd5decda">llvm::ms_demangle::PrimitiveTypeNode::outputPre</a> and <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/tagtypenode/#ad705bfae4de090c2ed75411366c492e4">llvm::ms_demangle::TagTypeNode::outputPre</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
