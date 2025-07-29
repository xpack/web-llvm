---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/targetparser/armtargetparser-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ARMTargetParser.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">llvm/TargetParser/ARMTargetParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparsercommon-h">llvm/TargetParser/ARMTargetParserCommon.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;cctype&gt;
#include "llvm/TargetParser/ARMTargetParser.def"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c5b47f454cbf71aed5ac9dbc0f566b">getHWDivSynonym</a> (StringRef HWDiv)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ac2456158e5acb44477d8ecfa2d04dbde">ARM::ProfileKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc63544c9d29e08202e6e196a2dfcafc">getProfileKind</a> (ARM::ArchKind AK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4e31382e5e1a22b808da4b02b67a7d2">stripNegationPrefix</a> (StringRef &amp;Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a7ec47cecec400dff032e3b34a3630129">ARM::FPUKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adae37657f827f24d47e8d69bc6a32b2b">findDoublePrecisionFPU</a> (ARM::FPUKind InputFPUKind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a7ec47cecec400dff032e3b34a3630129">ARM::FPUKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40651a426e93c95af35349e804ff01e8">findSinglePrecisionFPU</a> (ARM::FPUKind InputFPUKind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabe89a04d653c539596c27503e9f25e6">ARM_CPU_NAME</a>(NAME, ID, DEFAULT_FPU, IS_DEFAULT, DEFAULT_EXT)&nbsp;&nbsp;&nbsp;  .Case(NAME, DEFAULT_FPU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f9e19ecc658ace8903ded36a6c4077">ARM_CPU_NAME</a>(NAME, ID, DEFAULT_FPU, IS_DEFAULT, DEFAULT_EXT)&nbsp;&nbsp;&nbsp;...</td>
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

### findDoublePrecisionFPU() {#adae37657f827f24d47e8d69bc6a32b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARM::FPUKind findDoublePrecisionFPU (<a href="/web-llvm/docs/api/namespaces/llvm/arm/#a7ec47cecec400dff032e3b34a3630129">ARM::FPUKind</a> InputFPUKind)</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp">ARMTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a454feabe0a86be1361d2b4f97239ee10">llvm::ARM::FPUNames</a>, <a href="/web-llvm/docs/api/structs/llvm/arm/fpuname/#a9421e38dee3194c89006ecf3f0c18228">llvm::ARM::FPUName::FPUVer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ab4fbf76a94daa86a4a96bb1bbdec6c98">llvm::ARM::has32Regs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#abc2e47b2a23fc692a1a7bffc76bc34e4">llvm::ARM::isDoublePrecision</a>, <a href="/web-llvm/docs/api/structs/llvm/arm/fpuname/#aaa5260cbae9c072c87aecfdcc40896ce">llvm::ARM::FPUName::NeonSupport</a> and <a href="/web-llvm/docs/api/structs/llvm/arm/fpuname/#a725739d3acc705903464c90d0fb7772c">llvm::ARM::FPUName::Restriction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a77eb768ac8911a56c80449a4e98d3467">llvm::ARM::appendArchExtFeatures</a>.</p>

</div>
</div>

### findSinglePrecisionFPU() {#a40651a426e93c95af35349e804ff01e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARM::FPUKind findSinglePrecisionFPU (<a href="/web-llvm/docs/api/namespaces/llvm/arm/#a7ec47cecec400dff032e3b34a3630129">ARM::FPUKind</a> InputFPUKind)</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp">ARMTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a454feabe0a86be1361d2b4f97239ee10">llvm::ARM::FPUNames</a>, <a href="/web-llvm/docs/api/structs/llvm/arm/fpuname/#a9421e38dee3194c89006ecf3f0c18228">llvm::ARM::FPUName::FPUVer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ab4fbf76a94daa86a4a96bb1bbdec6c98">llvm::ARM::has32Regs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#abc2e47b2a23fc692a1a7bffc76bc34e4">llvm::ARM::isDoublePrecision</a>, <a href="/web-llvm/docs/api/structs/llvm/arm/fpuname/#aaa5260cbae9c072c87aecfdcc40896ce">llvm::ARM::FPUName::NeonSupport</a> and <a href="/web-llvm/docs/api/structs/llvm/arm/fpuname/#a725739d3acc705903464c90d0fb7772c">llvm::ARM::FPUName::Restriction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a77eb768ac8911a56c80449a4e98d3467">llvm::ARM::appendArchExtFeatures</a>.</p>

</div>
</div>

### getHWDivSynonym() {#a51c5b47f454cbf71aed5ac9dbc0f566b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getHWDivSynonym (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> HWDiv)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp">ARMTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a> and <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a125c0a3b51a3940108feac9b56d6bb4c">llvm::ARM::parseHWDiv</a>.</p>

</div>
</div>

### getProfileKind() {#acc63544c9d29e08202e6e196a2dfcafc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARM::ProfileKind getProfileKind (<a href="/web-llvm/docs/api/namespaces/llvm/arm/#a251fc5156cdf171e44a7a4463609fe8a">ARM::ArchKind</a> AK)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp">ARMTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ac2456158e5acb44477d8ecfa2d04dbdea7fc56270e7a70fa81a5935b72eacbe29">llvm::ARM::A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ac2456158e5acb44477d8ecfa2d04dbdeaccc0377a8afbf50e7094f5c23a8af223">llvm::ARM::INVALID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ac2456158e5acb44477d8ecfa2d04dbdea69691c7bdcc3ce6d5d8a1361f22d04ac">llvm::ARM::M</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ac2456158e5acb44477d8ecfa2d04dbdeae1e1d3d40573127e9ee0480caf1283d6">llvm::ARM::R</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a5490279984e698a5d0800901a9cb9ad5">llvm::ARM::convertV9toV8</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a96deed10d8fd592dce3db1b8d8df6011">llvm::ARM::parseArchProfile</a>.</p>

</div>
</div>

### stripNegationPrefix() {#aa4e31382e5e1a22b808da4b02b67a7d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool stripNegationPrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name)</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp">ARMTargetParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a77eb768ac8911a56c80449a4e98d3467">llvm::ARM::appendArchExtFeatures</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a929050d440af74e38393ad3a800ffff9">llvm::ARM::getArchExtFeature</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ARM\_CPU\_NAME {#aabe89a04d653c539596c27503e9f25e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ARM_CPU_NAME(NAME, ID, DEFAULT_FPU, IS_DEFAULT, DEFAULT_EXT)&nbsp;&nbsp;&nbsp;  .Case(NAME, DEFAULT_FPU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp">ARMTargetParser.cpp</a>.</p>

</div>
</div>

### ARM\_CPU\_NAME {#ad1f9e19ecc658ace8903ded36a6c4077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ARM_CPU_NAME(NAME, ID, DEFAULT_FPU, IS_DEFAULT, DEFAULT_EXT)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  .Case(NAME,                                                                  \
        ARMArchNames[static_cast&lt;unsigned&gt;(ArchKind::ID)].ArchBaseExtensions | \
            DEFAULT_EXT)
</div>
</dd>
</dl>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp">ARMTargetParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
