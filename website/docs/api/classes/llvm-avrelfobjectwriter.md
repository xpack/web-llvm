---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/avrelfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AVRELFObjectWriter` Class

<p>Writes <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> machine code into an ELF32 object file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AVRELFObjectWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter">MCELFObjectTargetWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25bc1199b9b97ff8e27b7b793b913f68">AVRELFObjectWriter</a> (uint8_t OSABI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab77bbaa6fcb1680e6880efbafac01bd7">~AVRELFObjectWriter</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d1153ad58a6a11c307ae506cc3439e1">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsPCRel) const override</td>
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

<p>Writes <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> machine code into an ELF32 object file.</p>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrelfobjectwriter-cpp">AVRELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AVRELFObjectWriter() {#a25bc1199b9b97ff8e27b7b793b913f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AVRELFObjectWriter::AVRELFObjectWriter (uint8_t OSABI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrelfobjectwriter-cpp">AVRELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#ae6c6e76c9d8e0c912542fe4f8375e8ce">llvm::MCELFObjectTargetWriter::MCELFObjectTargetWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AVRELFObjectWriter() {#ab77bbaa6fcb1680e6880efbafac01bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::AVRELFObjectWriter::~AVRELFObjectWriter ()</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrelfobjectwriter-cpp">AVRELFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRelocType() {#a6d1153ad58a6a11c307ae506cc3439e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRELFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsPCRel)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrelfobjectwriter-cpp">AVRELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aef7dfebd31b781d8947b5ee86ea8344b">llvm::AVR::fixup_13_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a1988574074630219dd0822e790327356">llvm::AVR::fixup_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a0a7ad8e9592283440f485e0c10e944f2">llvm::AVR::fixup_16_pm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a500fa30f51cc74e5a90492f6b302334a">llvm::AVR::fixup_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1afdbb8a9b4206897c419c5a93db879478">llvm::AVR::fixup_6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a5a35c5fe666b4d94dd0fec1399e3e46f">llvm::AVR::fixup_6_adiw</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a60e6a283e3c8cbea62c15d290b3b7230">llvm::AVR::fixup_7_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1acdd0f7dd8821f18836309748e0502b09">llvm::AVR::fixup_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1ac41084f0958f15695b00ec1f6421d5f1">llvm::AVR::fixup_8_hi8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a5c874e004c307eb67afd5ea9a301f9c3">llvm::AVR::fixup_8_hlo8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aa2d2fe99786c5857ad6ea10e4d3cd980">llvm::AVR::fixup_8_lo8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a223843ea9d717c21dd80bf8124e9a16e">llvm::AVR::fixup_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a085e8b08c76da2d683bd83bd15f6f6be">llvm::AVR::fixup_diff16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aebac1fc0b48d2ccc07a425d70025d74f">llvm::AVR::fixup_diff32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a5a2eeb2fb2811f245cbf30d2c48abc1c">llvm::AVR::fixup_diff8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a382b86a3e3c868e6ddd9475944d8d1cd">llvm::AVR::fixup_hh8_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a99d632ff5fa83e7b6ad4bf40eb108cbb">llvm::AVR::fixup_hh8_ldi_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a9ee8f8e04076fa4bb138a15c7c28691f">llvm::AVR::fixup_hh8_ldi_pm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1ac8e2243f3ba6ba72cdea9d6e5d86a504">llvm::AVR::fixup_hh8_ldi_pm_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a78ac987d603e1af3517bd49dacc5ee34">llvm::AVR::fixup_hi8_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a1edd771e4ceba008a0aa03ca9aee683f">llvm::AVR::fixup_hi8_ldi_gs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aefc20853a2c98d2ef8a07255a98a6a22">llvm::AVR::fixup_hi8_ldi_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1ab13e48e1103a86880bd207573da528e9">llvm::AVR::fixup_hi8_ldi_pm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a766028df6cd5759254edcfea42e8296d">llvm::AVR::fixup_hi8_ldi_pm_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a6b7175a9e13966bf2bebe7d0f196b462">llvm::AVR::fixup_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1afffc03deb9be0873e82f17212493795e">llvm::AVR::fixup_lds_sts_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a72001e129a73846ac51da1bc606f8c2d">llvm::AVR::fixup_lo8_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aa925266a218e48fd76747c51bd83615d">llvm::AVR::fixup_lo8_ldi_gs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a58d3467e8ce0a23f1b6085534f4abf28">llvm::AVR::fixup_lo8_ldi_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a86089f48a39009fba6b797d64a5c3e38">llvm::AVR::fixup_lo8_ldi_pm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aa45c22f2c30f421e4b2efbefde64a2b8">llvm::AVR::fixup_lo8_ldi_pm_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a5a57de6d17ac1d7fe855d0bdf7420b7e">llvm::AVR::fixup_ms8_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a46b76675cc30a160bdc1efdfa54c26f2">llvm::AVR::fixup_ms8_ldi_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aa417f149a7d5fd39ca8e72197c12b4d8">llvm::AVR::fixup_port5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a8bfdf34483b345245854a23f35888527">llvm::AVR::fixup_port6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a23ddbd81fa939ae7beb63b41adf49840">llvm::MCSymbolRefExpr::VK_AVR_DIFF16</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a7d4ea2582d7854b749f600956cab2270">llvm::MCSymbolRefExpr::VK_AVR_DIFF32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a23b7b8655bd878090bcde3981874b67b">llvm::MCSymbolRefExpr::VK_AVR_DIFF8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985af05034277372574cb19c4b1a4cd9512e">llvm::MCSymbolRefExpr::VK_AVR_HI8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ae94f4874e083b555503261633fddf252">llvm::MCSymbolRefExpr::VK_AVR_HLO8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a397380ba86f34c5d45316aedb17717be">llvm::MCSymbolRefExpr::VK_AVR_LO8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a20fbdefa51326892a391cc8b92cfeed3">llvm::MCSymbolRefExpr::VK_AVR_NONE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985af427aa83e01ff2afe3a8640aaa86c0a9">llvm::MCSymbolRefExpr::VK_AVR_PM</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrelfobjectwriter-cpp">AVRELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
