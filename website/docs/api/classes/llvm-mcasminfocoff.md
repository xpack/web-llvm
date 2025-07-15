---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcasminfocoff
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCAsmInfoCOFF` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCAsmInfoCOFF { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfocoff-h">llvm/MC/MCAsmInfoCOFF.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasminfognucoff">MCAsmInfoGNUCOFF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasminfomicrosoft">MCAsmInfoMicrosoft</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aede3b5538359ee7e3169f832a673186e">MCAsmInfoCOFF</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51cdb7ab909819bac009b70310013f72">anchor</a> ()</td>
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


<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfocoff-h">MCAsmInfoCOFF.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### MCAsmInfoCOFF() {#aede3b5538359ee7e3169f832a673186e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmInfoCOFF::MCAsmInfoCOFF ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfocoff-h">MCAsmInfoCOFF.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasminfocoff-cpp">MCAsmInfoCOFF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a4ba4b1aaa416d3db5d4005e2d6e799d1">llvm::MCAsmInfo::AvoidWeakIfComdat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lcomm/#aae933cd10a930a5312da96502035e331a310fe8dc05086ce23b6826ccb3c37fc7">llvm::LCOMM::ByteAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac0079bf3834ce7ee765d437aae0a8a69">llvm::MCAsmInfo::COMMDirectiveAlignmentIsInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a8a5c80f10fed34bd7d0c3dc5c0e83e92">llvm::MCAsmInfo::HasCOFFAssociativeComdats</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a703953ac365547dfb14bcb5aa89ebdc3">llvm::MCAsmInfo::HasCOFFComdatConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a7c3b8692b75d4808f7c888e61f01e1c8">llvm::MCAsmInfo::HasDotTypeDotSizeDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ab74c767922c89f683dec73c5b9a7b87a">llvm::MCAsmInfo::HasSingleParameterDotFile</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aaccbddd4af6a81c7bf3a53e30289bb17">llvm::MCAsmInfo::HiddenDeclarationVisibilityAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aef1537a18c53520abe7cb7026e10cb92">llvm::MCAsmInfo::HiddenVisibilityAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a6f7c7ae850927432e251d9a5f8bb0537">llvm::MCAsmInfo::LCOMMDirectiveAlignmentType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243af3367f8319e21bf0779da14146221c55">llvm::MCSA_Invalid</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a051d22777a039124dc106b8b3ba73676">llvm::MCAsmInfo::NeedsDwarfSectionOffsetDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a1de3b3906f70f4952617056881437120">llvm::MCAsmInfo::ProtectedVisibilityAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a98f40236cfff7278d4b57633fad2245d">llvm::MCAsmInfo::SupportsDebugInformation</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a68d0ce091e24acdd9c867990f7a94b56">llvm::MCAsmInfo::UseLogicalShr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a72118878aeadcae71da2d5d179aebb81">llvm::MCAsmInfo::WeakRefDirective</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a51cdb7ab909819bac009b70310013f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCAsmInfoCOFF::anchor ()</td>
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



<p>Declaration at line 17 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfocoff-h">MCAsmInfoCOFF.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasminfocoff-cpp">MCAsmInfoCOFF.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfocoff-h">MCAsmInfoCOFF.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcasminfocoff-cpp">MCAsmInfoCOFF.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
