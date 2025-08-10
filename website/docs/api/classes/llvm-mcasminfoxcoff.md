---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcasminfoxcoff
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCAsmInfoXCOFF` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCAsmInfoXCOFF { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfoxcoff-h">llvm/MC/MCAsmInfoXCOFF.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is intended to be used as a base class for asm properties and features specific to the target. <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppcxcoffmcasminfo">PPCXCOFFMCAsmInfo</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad17f2ee0f3955579c9e7a953bb2503e5">MCAsmInfoXCOFF</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafa2f7fa06a53fe4907c81c1c7f36951">isAcceptableChar</a> (char C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if C is an acceptable character inside a symbol name. <a href="#aafa2f7fa06a53fe4907c81c1c7f36951">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55851e637853f57eef0be5635a27b6c">anchor</a> ()</td>
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


<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfoxcoff-h">MCAsmInfoXCOFF.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### MCAsmInfoXCOFF() {#ad17f2ee0f3955579c9e7a953bb2503e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmInfoXCOFF::MCAsmInfoXCOFF ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfoxcoff-h">MCAsmInfoXCOFF.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasminfoxcoff-cpp">MCAsmInfoXCOFF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ae0a2d87aa9c2d59f6c38b3d55f530fd9ad1ecc712b2ab5b0f004b0935208910f5">llvm::MCAsmInfo::ACLS_SingleQuotePrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a7e6bb0931a72759d39514aa924b420bc">llvm::AIX</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a20ecadae9aa8ee83587c9fcaedf6578a">llvm::MCAsmInfo::AsciiDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ad8520723e634e656d2a8219e0cf19ba7">llvm::MCAsmInfo::AscizDirective</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44aa5bd521ebe67ddf0e90f1a9e540a6d43">llvm::cl::BOU_UNSET</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac20dd7cbe582d9769786c7bb1da99b3e">llvm::MCAsmInfo::CharacterLiteralSyntax</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac0079bf3834ce7ee765d437aae0a8a69">llvm::MCAsmInfo::COMMDirectiveAlignmentIsInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a035c98c0423e6dd21ec2ea039f762440">llvm::MCAsmInfo::Data16bitsDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a620b2ebe9e68a34106b7bdcc4220c6b2">llvm::MCAsmInfo::Data32bitsDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a500ba2b2c0203d1d53b83a649551a6b5">llvm::MCAsmInfo::ExceptionsType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a7c3b8692b75d4808f7c888e61f01e1c8">llvm::MCAsmInfo::HasDotTypeDotSizeDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aea43d3be695d00d0aee461b828142cdf">llvm::MCAsmInfo::HasLEB128Directives</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a093fab9654b4d8829128e983d0fb4e1d">llvm::MCAsmInfo::IsAIX</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#adfd724f11ba125f30c3bb516be0bb06f">llvm::MCAsmInfo::IsLittleEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a6f7c7ae850927432e251d9a5f8bb0537">llvm::MCAsmInfo::LCOMMDirectiveAlignmentType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lcomm/#aae933cd10a930a5312da96502035e331adce83244e971c1aeafe5840c91d9be0b">llvm::LCOMM::Log2Alignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a8d77ee124165d600e83bda2aa3f43eb6">llvm::MCAsmInfo::ParseInlineAsmUsingAsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a5384e7b6526e6d9c7744c07e1136b7b8">llvm::MCAsmInfo::PrivateGlobalPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a721901796262520ac70998c9323686cb">llvm::MCAsmInfo::PrivateLabelPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ad6636ff34629b06e7f639d338c81bdf5">llvm::MCAsmInfo::SupportsQuotedNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3662550aa37c97ad75954715f0515a6">llvm::UseLEB128Directives</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#acf84c6bd03a785a251784cad666d9ee1">llvm::MCAsmInfo::ZeroDirective</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isAcceptableChar() {#aafa2f7fa06a53fe4907c81c1c7f36951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmInfoXCOFF::isAcceptableChar (char C)</td>
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

<p>Return true if C is an acceptable character inside a symbol name.</p>

<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfoxcoff-h">MCAsmInfoXCOFF.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasminfoxcoff-cpp">MCAsmInfoXCOFF.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#af55851e637853f57eef0be5635a27b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmInfoXCOFF::anchor ()</td>
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



<p>Declaration at line 17 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfoxcoff-h">MCAsmInfoXCOFF.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasminfoxcoff-cpp">MCAsmInfoXCOFF.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfoxcoff-h">MCAsmInfoXCOFF.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcasminfoxcoff-cpp">MCAsmInfoXCOFF.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
