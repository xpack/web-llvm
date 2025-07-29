---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/adjust
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `adjust` Namespace



## Definition

<div class="doxyDefinition">
namespace adjust { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/adjust/ldi">ldi</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fixups relating to the LDI instruction. <a href="/web-llvm/docs/api/namespaces/adjust/ldi/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a2da2b39e1834223e10c3d33ade866">unsigned_width</a> (unsigned Width, uint64_t Value, std::string Description, const MCFixup &amp;Fixup, MCContext *Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a180e97360df3a3083f13bde03d4ffe46">adjustBranch</a> (unsigned Size, const MCFixup &amp;Fixup, uint64_t &amp;Value, MCContext *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adjusts the value of a branch target before fixup application. <a href="#a180e97360df3a3083f13bde03d4ffe46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6888126cb2adb886258b17447e5a205">adjustRelativeBranch</a> (unsigned Size, const MCFixup &amp;Fixup, uint64_t &amp;Value, const MCSubtargetInfo *STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adjusts the value of a relative branch target before fixup application. <a href="#ad6888126cb2adb886258b17447e5a205">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f440bc48fa8490137415c9d2f80492">fixup_call</a> (unsigned Size, const MCFixup &amp;Fixup, uint64_t &amp;Value, MCContext *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>22-bit absolute fixup. <a href="#a94f440bc48fa8490137415c9d2f80492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7daa33e05e9d8389d7e8e518eb5c9391">fixup_7_pcrel</a> (unsigned Size, const MCFixup &amp;Fixup, uint64_t &amp;Value, MCContext *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>7-bit PC-relative fixup. <a href="#a7daa33e05e9d8389d7e8e518eb5c9391">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e640b2e159d95523eb58b80cb80f064">fixup_13_pcrel</a> (unsigned Size, const MCFixup &amp;Fixup, uint64_t &amp;Value, MCContext *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>12-bit PC-relative fixup. <a href="#a7e640b2e159d95523eb58b80cb80f064">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54054e19c3f70129290ae0799251c33f">fixup_6</a> (const MCFixup &amp;Fixup, uint64_t &amp;Value, MCContext *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>6-bit fixup for the immediate operand of the STD/LDD family of instructions. <a href="#a54054e19c3f70129290ae0799251c33f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5791905065ceec04294a3f165a266ed4">fixup_6_adiw</a> (const MCFixup &amp;Fixup, uint64_t &amp;Value, MCContext *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>6-bit fixup for the immediate operand of the ADIW family of instructions. <a href="#a5791905065ceec04294a3f165a266ed4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b2dfc5fe543286d452c7411d6048ce">fixup_port5</a> (const MCFixup &amp;Fixup, uint64_t &amp;Value, MCContext *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>5-bit port number fixup on the SBIC family of instructions. <a href="#a76b2dfc5fe543286d452c7411d6048ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77526d3cac35e63f1f829d28b14fd108">fixup_port6</a> (const MCFixup &amp;Fixup, uint64_t &amp;Value, MCContext *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>6-bit port number fixup on the IN family of instructions. <a href="#a77526d3cac35e63f1f829d28b14fd108">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50754b5bcafbd04e7ff2e61265d6134b">fixup_lds_sts_16</a> (const MCFixup &amp;Fixup, uint64_t &amp;Value, MCContext *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>7-bit data space address fixup for the LDS/STS instructions on AVRTiny. <a href="#a50754b5bcafbd04e7ff2e61265d6134b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf2fb91e86b3f0e4a75c79568f4cad9e">pm</a> (uint64_t &amp;Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adjusts a program memory address. <a href="#abf2fb91e86b3f0e4a75c79568f4cad9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### adjustBranch() {#a180e97360df3a3083f13bde03d4ffe46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjust::adjustBranch (unsigned Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx)</td>
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

<p>Adjusts the value of a branch target before fixup application.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/avr/fixups/#a045e45f75e22c4d3afb2756c80882710">llvm::AVR::fixups::adjustBranchTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a06a2da2b39e1834223e10c3d33ade866">unsigned_width</a>.</p>


<p>Referenced by <a href="#a94f440bc48fa8490137415c9d2f80492">fixup_call</a>.</p>

</div>
</div>

### adjustRelativeBranch() {#ad6888126cb2adb886258b17447e5a205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool adjust::adjustRelativeBranch (unsigned Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t &amp; Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Adjusts the value of a relative branch target before fixup application.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/avr/fixups/#a045e45f75e22c4d3afb2756c80882710">llvm::AVR::fixups::adjustBranchTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad80b46c754cc7216244a866ec9b1cb0">llvm::isIntN</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a7e640b2e159d95523eb58b80cb80f064">fixup_13_pcrel</a>, <a href="#a7daa33e05e9d8389d7e8e518eb5c9391">fixup_7_pcrel</a> and <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#acaeae6c0754ca9264b9ad0bb5c4f5916">llvm::AVRAsmBackend::shouldForceRelocation</a>.</p>

</div>
</div>

### fixup\_13\_pcrel() {#a7e640b2e159d95523eb58b80cb80f064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjust::fixup_13_pcrel (unsigned Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx)</td>
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

<p>12-bit PC-relative fixup.</p>


<p>Yes, the fixup is 12 bits even though the name says otherwise.</p>


<p>Resolves to: 0000 kkkk kkkk kkkk Offset of 0 (so the result isn't left-shifted before application).</p>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="#ad6888126cb2adb886258b17447e5a205">adjustRelativeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a78aafef1cfb9e7f16f7cd87ac1f806bc">llvm::AVRAsmBackend::adjustFixupValue</a>.</p>

</div>
</div>

### fixup\_6() {#a54054e19c3f70129290ae0799251c33f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjust::fixup_6 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx)</td>
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

<p>6-bit fixup for the immediate operand of the STD/LDD family of instructions.</p>


<p>Resolves to: 10q0 qq10 0000 1qqq</p>


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="#a06a2da2b39e1834223e10c3d33ade866">unsigned_width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a78aafef1cfb9e7f16f7cd87ac1f806bc">llvm::AVRAsmBackend::adjustFixupValue</a>.</p>

</div>
</div>

### fixup\_6\_adiw() {#a5791905065ceec04294a3f165a266ed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjust::fixup_6_adiw (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx)</td>
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

<p>6-bit fixup for the immediate operand of the ADIW family of instructions.</p>


<p>Resolves to: 0000 0000 kk00 kkkk</p>


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="#a06a2da2b39e1834223e10c3d33ade866">unsigned_width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a78aafef1cfb9e7f16f7cd87ac1f806bc">llvm::AVRAsmBackend::adjustFixupValue</a>.</p>

</div>
</div>

### fixup\_7\_pcrel() {#a7daa33e05e9d8389d7e8e518eb5c9391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjust::fixup_7_pcrel (unsigned Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx)</td>
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

<p>7-bit PC-relative fixup.</p>


<p>Resolves to: 0000 00kk kkkk k000 Offset of 0 (so the result is left shifted by 3 bits before application).</p>


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="#ad6888126cb2adb886258b17447e5a205">adjustRelativeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a78aafef1cfb9e7f16f7cd87ac1f806bc">llvm::AVRAsmBackend::adjustFixupValue</a>.</p>

</div>
</div>

### fixup\_call() {#a94f440bc48fa8490137415c9d2f80492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjust::fixup_call (unsigned Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx)</td>
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

<p>22-bit absolute fixup.</p>


<p>Resolves to: 1001 kkkk 010k kkkk kkkk kkkk 111k kkkk</p>


<p>Offset of 0 (so the result is left shifted by 3 bits before application).</p>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="#a180e97360df3a3083f13bde03d4ffe46">adjustBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a78aafef1cfb9e7f16f7cd87ac1f806bc">llvm::AVRAsmBackend::adjustFixupValue</a>.</p>

</div>
</div>

### fixup\_lds\_sts\_16() {#a50754b5bcafbd04e7ff2e61265d6134b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjust::fixup_lds_sts_16 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx)</td>
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

<p>7-bit data space address fixup for the LDS/STS instructions on AVRTiny.</p>


<p>Resolves to: 1010 ikkk dddd kkkk</p>


<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="#a06a2da2b39e1834223e10c3d33ade866">unsigned_width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a78aafef1cfb9e7f16f7cd87ac1f806bc">llvm::AVRAsmBackend::adjustFixupValue</a>.</p>

</div>
</div>

### fixup\_port5() {#a76b2dfc5fe543286d452c7411d6048ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjust::fixup_port5 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx)</td>
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

<p>5-bit port number fixup on the SBIC family of instructions.</p>


<p>Resolves to: 0000 0000 AAAA A000</p>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="#a06a2da2b39e1834223e10c3d33ade866">unsigned_width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a78aafef1cfb9e7f16f7cd87ac1f806bc">llvm::AVRAsmBackend::adjustFixupValue</a>.</p>

</div>
</div>

### fixup\_port6() {#a77526d3cac35e63f1f829d28b14fd108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjust::fixup_port6 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx)</td>
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

<p>6-bit port number fixup on the IN family of instructions.</p>


<p>Resolves to: 1011 0AAd dddd AAAA</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="#a06a2da2b39e1834223e10c3d33ade866">unsigned_width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a78aafef1cfb9e7f16f7cd87ac1f806bc">llvm::AVRAsmBackend::adjustFixupValue</a>.</p>

</div>
</div>

### pm() {#abf2fb91e86b3f0e4a75c79568f4cad9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjust::pm (uint64_t &amp; Value)</td>
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

<p>Adjusts a program memory address.</p>


<p>This is a simple right-shift.</p>


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a78aafef1cfb9e7f16f7cd87ac1f806bc">llvm::AVRAsmBackend::adjustFixupValue</a>.</p>

</div>
</div>

### unsigned\_width() {#a06a2da2b39e1834223e10c3d33ade866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjust::unsigned_width (unsigned Width, uint64_t Value, std::string Description, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a995470163b6d76695cba5bc8dfb529">llvm::isUIntN</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af80bd4ec8a9b2f8e7d9d75ab708a55c2">llvm::maxUIntN</a>.</p>


<p>Referenced by <a href="#a180e97360df3a3083f13bde03d4ffe46">adjustBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a78aafef1cfb9e7f16f7cd87ac1f806bc">llvm::AVRAsmBackend::adjustFixupValue</a>, <a href="#a54054e19c3f70129290ae0799251c33f">fixup_6</a>, <a href="#a5791905065ceec04294a3f165a266ed4">fixup_6_adiw</a>, <a href="#a50754b5bcafbd04e7ff2e61265d6134b">fixup_lds_sts_16</a>, <a href="#a76b2dfc5fe543286d452c7411d6048ce">fixup_port5</a> and <a href="#a77526d3cac35e63f1f829d28b14fd108">fixup_port6</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrasmbackend-cpp">AVRAsmBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
