---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/avrasmbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AVRAsmBackend` Class

<p>Utilities for manipulating generated <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> machine code. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AVRAsmBackend { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">Target/AVR/MCTargetDesc/AVRAsmBackend.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic interface to target specific assembler backends. <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512987fb8415c6262a53327a35229346">AVRAsmBackend</a> (Triple::OSType OSType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78aafef1cfb9e7f16f7cd87ac1f806bc">adjustFixupValue</a> (const MCFixup &amp;Fixup, const MCValue &amp;Target, uint64_t &amp;Value, MCContext *Ctx=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjecttargetwriter">MCObjectTargetWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d8e808eda7588361d53e7c6b7428836">createObjectTargetWriter</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a863fe7b0cd779f309ac493e93c952d37">applyFixup</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, MutableArrayRef&lt; char &gt; Data, uint64_t Value, bool IsResolved, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate. <a href="#a863fe7b0cd779f309ac493e93c952d37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86ec1c09eab7a6bd76bdbd5cd1fc922d">getFixupKind</a> (StringRef Name) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a relocation name used in .reloc to a fixup kind. <a href="#a86ec1c09eab7a6bd76bdbd5cd1fc922d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo">MCFixupKindInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09b2372b0e54d255c3c5e6433cb74b03">getFixupKindInfo</a> (MCFixupKind Kind) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get information on a fixup kind. <a href="#a09b2372b0e54d255c3c5e6433cb74b03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf4f3626cea56f14014da5ee1463f258">getNumFixupKinds</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of target specific fixup kinds. <a href="#acf4f3626cea56f14014da5ee1463f258">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8adb83bb8a3474a9261a804c2798ee94">writeNopData</a> (raw_ostream &amp;OS, uint64_t Count, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write an (optimal) nop sequence of Count bytes to the given output. <a href="#a8adb83bb8a3474a9261a804c2798ee94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaeae6c0754ca9264b9ad0bb5c4f5916">shouldForceRelocation</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, const uint64_t Value, const MCSubtargetInfo *STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hook to check if a relocation is needed for some target specific reason. <a href="#acaeae6c0754ca9264b9ad0bb5c4f5916">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cd">Triple::OSType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0317d1b0369b10126dd922b6b2bd8800">OSType</a></td>
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

<p>Utilities for manipulating generated <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> machine code.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">AVRAsmBackend.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AVRAsmBackend() {#a512987fb8415c6262a53327a35229346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AVRAsmBackend::AVRAsmBackend (<a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cd">Triple::OSType</a> OSType)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">AVRAsmBackend.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a3dd30d6980185ef34e42333191453867">llvm::MCAsmBackend::MCAsmBackend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### adjustFixupValue() {#a78aafef1cfb9e7f16f7cd87ac1f806bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRAsmBackend::adjustFixupValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, uint64_t &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">AVRAsmBackend.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/adjust/ldi/#aeeddcc1e750e09610ab189e07a2d5bc8">adjust::ldi::fixup</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a7e640b2e159d95523eb58b80cb80f064">adjust::fixup_13_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aef7dfebd31b781d8947b5ee86ea8344b">llvm::AVR::fixup_13_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a1988574074630219dd0822e790327356">llvm::AVR::fixup_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a0a7ad8e9592283440f485e0c10e944f2">llvm::AVR::fixup_16_pm</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a54054e19c3f70129290ae0799251c33f">adjust::fixup_6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1afdbb8a9b4206897c419c5a93db879478">llvm::AVR::fixup_6</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a5791905065ceec04294a3f165a266ed4">adjust::fixup_6_adiw</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a5a35c5fe666b4d94dd0fec1399e3e46f">llvm::AVR::fixup_6_adiw</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a7daa33e05e9d8389d7e8e518eb5c9391">adjust::fixup_7_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a60e6a283e3c8cbea62c15d290b3b7230">llvm::AVR::fixup_7_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a94f440bc48fa8490137415c9d2f80492">adjust::fixup_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a223843ea9d717c21dd80bf8124e9a16e">llvm::AVR::fixup_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a382b86a3e3c868e6ddd9475944d8d1cd">llvm::AVR::fixup_hh8_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a99d632ff5fa83e7b6ad4bf40eb108cbb">llvm::AVR::fixup_hh8_ldi_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a9ee8f8e04076fa4bb138a15c7c28691f">llvm::AVR::fixup_hh8_ldi_pm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1ac8e2243f3ba6ba72cdea9d6e5d86a504">llvm::AVR::fixup_hh8_ldi_pm_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a78ac987d603e1af3517bd49dacc5ee34">llvm::AVR::fixup_hi8_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a1edd771e4ceba008a0aa03ca9aee683f">llvm::AVR::fixup_hi8_ldi_gs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aefc20853a2c98d2ef8a07255a98a6a22">llvm::AVR::fixup_hi8_ldi_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1ab13e48e1103a86880bd207573da528e9">llvm::AVR::fixup_hi8_ldi_pm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a766028df6cd5759254edcfea42e8296d">llvm::AVR::fixup_hi8_ldi_pm_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a6b7175a9e13966bf2bebe7d0f196b462">llvm::AVR::fixup_ldi</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a50754b5bcafbd04e7ff2e61265d6134b">adjust::fixup_lds_sts_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1afffc03deb9be0873e82f17212493795e">llvm::AVR::fixup_lds_sts_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a72001e129a73846ac51da1bc606f8c2d">llvm::AVR::fixup_lo8_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aa925266a218e48fd76747c51bd83615d">llvm::AVR::fixup_lo8_ldi_gs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a58d3467e8ce0a23f1b6085534f4abf28">llvm::AVR::fixup_lo8_ldi_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a86089f48a39009fba6b797d64a5c3e38">llvm::AVR::fixup_lo8_ldi_pm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aa45c22f2c30f421e4b2efbefde64a2b8">llvm::AVR::fixup_lo8_ldi_pm_neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a5a57de6d17ac1d7fe855d0bdf7420b7e">llvm::AVR::fixup_ms8_ldi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a46b76675cc30a160bdc1efdfa54c26f2">llvm::AVR::fixup_ms8_ldi_neg</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a76b2dfc5fe543286d452c7411d6048ce">adjust::fixup_port5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aa417f149a7d5fd39ca8e72197c12b4d8">llvm::AVR::fixup_port5</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a77526d3cac35e63f1f829d28b14fd108">adjust::fixup_port6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a8bfdf34483b345245854a23f35888527">llvm::AVR::fixup_port6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ab39a952893aef8c5d618b3d6f7d6bc84">llvm::FK_GPRel_4</a>, <a href="#a09b2372b0e54d255c3c5e6433cb74b03">getFixupKindInfo</a>, <a href="/web-llvm/docs/api/namespaces/adjust/ldi/#aca951e95d0a0cf12c676f91ef7c31740">adjust::ldi::hh8</a>, <a href="/web-llvm/docs/api/namespaces/adjust/ldi/#a189a46e268c912f577fa2c59e92bb149">adjust::ldi::hi8</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/adjust/ldi/#aaec3d8a144e99bceb790607e542834c0">adjust::ldi::lo8</a>, <a href="/web-llvm/docs/api/namespaces/adjust/ldi/#a0ffd933c06c7daefad330577b403516b">adjust::ldi::ms8</a>, <a href="/web-llvm/docs/api/namespaces/adjust/ldi/#a93bb30deb858c4113baccc93f0c1f001">adjust::ldi::neg</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#abf2fb91e86b3f0e4a75c79568f4cad9e">adjust::pm</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#acfcb94e2996dda3707eaa1eb1cb79f80">llvm::MCFixupKindInfo::TargetSize</a> and <a href="/web-llvm/docs/api/namespaces/adjust/#a06a2da2b39e1834223e10c3d33ade866">adjust::unsigned_width</a>.</p>


<p>Referenced by <a href="#a863fe7b0cd779f309ac493e93c952d37">applyFixup</a>.</p>

</div>
</div>

### applyFixup() {#a863fe7b0cd779f309ac493e93c952d37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRAsmBackend::applyFixup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; char &gt; Data, uint64_t Value, bool IsResolved, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Apply the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate.</p>


<p>Errors (such as an out of range fixup value) should be reported via <span class="doxyComputerOutput">Ctx</span>. The <span class="doxyComputerOutput">STI</span> is present only for fragments of type <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdatafragment">MCDataFragment</a> with hasInstructions() == true.</p>


<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">AVRAsmBackend.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="#a78aafef1cfb9e7f16f7cd87ac1f806bc">adjustFixupValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="#a09b2372b0e54d255c3c5e6433cb74b03">getFixupKindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### createObjectTargetWriter() {#a5d8e808eda7588361d53e7c6b7428836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MCObjectTargetWriter &gt; llvm::AVRAsmBackend::createObjectTargetWriter ()</td>
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



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">AVRAsmBackend.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8a800280ca833e834c367b1b184db4e0">llvm::createAVRELFObjectWriter</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#acb68e5e499fa476923a02f379546d450">llvm::MCELFObjectTargetWriter::getOSABI</a>.</p>

</div>
</div>

### getFixupKind() {#a86ec1c09eab7a6bd76bdbd5cd1fc922d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MCFixupKind &gt; llvm::AVRAsmBackend::getFixupKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Map a relocation name used in .reloc to a fixup kind.</p>

<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">AVRAsmBackend.h</a>, definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>.</p>

</div>
</div>

### getFixupKindInfo() {#a09b2372b0e54d255c3c5e6433cb74b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFixupKindInfo const  &amp; llvm::AVRAsmBackend::getFixupKindInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind)</td>
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

<p>Get information on a fixup kind.</p>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">AVRAsmBackend.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a02772a67f2052ae04bb9ef1ff9dc3cf8">llvm::FirstTargetFixupKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a845a63cbed041d42d8c3452991d629c4">llvm::FK_NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">llvm::MCFixupKindInfo::FKF_IsPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad4777f004ef52f665e6ec6defc1cb32a">llvm::MCAsmBackend::getFixupKindInfo</a>, <a href="#acf4f3626cea56f14014da5ee1463f258">getNumFixupKinds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a6499d178b9964b2fc7b26cd8ebb82d24">llvm::AVR::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#a78aafef1cfb9e7f16f7cd87ac1f806bc">adjustFixupValue</a>, <a href="#a863fe7b0cd779f309ac493e93c952d37">applyFixup</a> and <a href="#acaeae6c0754ca9264b9ad0bb5c4f5916">shouldForceRelocation</a>.</p>

</div>
</div>

### getNumFixupKinds() {#acf4f3626cea56f14014da5ee1463f258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRAsmBackend::getNumFixupKinds ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the number of target specific fixup kinds.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">AVRAsmBackend.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a6499d178b9964b2fc7b26cd8ebb82d24">llvm::AVR::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#a09b2372b0e54d255c3c5e6433cb74b03">getFixupKindInfo</a>.</p>

</div>
</div>

### shouldForceRelocation() {#acaeae6c0754ca9264b9ad0bb5c4f5916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRAsmBackend::shouldForceRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Hook to check if a relocation is needed for some target specific reason.</p>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">AVRAsmBackend.h</a>, definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/adjust/#ad6888126cb2adb886258b17447e5a205">adjust::adjustRelativeBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1aef7dfebd31b781d8947b5ee86ea8344b">llvm::AVR::fixup_13_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a60e6a283e3c8cbea62c15d290b3b7230">llvm::AVR::fixup_7_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1a223843ea9d717c21dd80bf8124e9a16e">llvm::AVR::fixup_call</a>, <a href="#a09b2372b0e54d255c3c5e6433cb74b03">getFixupKindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#acfcb94e2996dda3707eaa1eb1cb79f80">llvm::MCFixupKindInfo::TargetSize</a>.</p>

</div>
</div>

### writeNopData() {#a8adb83bb8a3474a9261a804c2798ee94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRAsmBackend::writeNopData (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Count, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Write an (optimal) nop sequence of Count bytes to the given output.</p>


<p>If the target cannot generate such a sequence, it should return an error.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- True on success.</p></dd>
</dl>


<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">AVRAsmBackend.h</a>, definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a06288f4d38e1d74fc7a1d10056d88373">llvm::raw_ostream::write_zeros</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OSType {#a0317d1b0369b10126dd922b6b2bd8800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::OSType llvm::AVRAsmBackend::OSType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">AVRAsmBackend.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-h">AVRAsmBackend.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
