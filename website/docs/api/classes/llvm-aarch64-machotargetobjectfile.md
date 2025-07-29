---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aarch64-machotargetobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64_MachoTargetObjectFile` Class

<p><a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile">AArch64_MachoTargetObjectFile</a> - This TLOF implementation is used for Darwin. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AArch64_MachoTargetObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">Target/AArch64/AArch64TargetObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho">TargetLoweringObjectFileMachO</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a821a2de5466baeb8f887dd7c41b1b575">AArch64_MachoTargetObjectFile</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abda04e72e43a3aaef8a55e4ecf91d127">getTTypeGlobalReference</a> (const GlobalValue *GV, unsigned Encoding, const TargetMachine &amp;TM, MachineModuleInfo *MMI, MCStreamer &amp;Streamer) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> to use for a reference to the specified global variable from exception handling information. <a href="#abda04e72e43a3aaef8a55e4ecf91d127">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7b86bc2bb8a965529cb9c4ace6d7e56">getCFIPersonalitySymbol</a> (const GlobalValue *GV, const TargetMachine &amp;TM, MachineModuleInfo *MMI) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab2cc2813c5a774bb4f83b6f9ae5a98b">getIndirectSymViaGOTPCRel</a> (const GlobalValue *GV, const MCSymbol *Sym, const MCValue &amp;MV, int64_t Offset, MachineModuleInfo *MMI, MCStreamer &amp;Streamer) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the target specific PC relative GOT entry relocation. <a href="#aab2cc2813c5a774bb4f83b6f9ae5a98b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab74a50e826e0105a5a0f724700c5d5c2">getNameWithPrefix</a> (SmallVectorImpl&lt; char &gt; &amp;OutName, const GlobalValue *GV, const TargetMachine &amp;TM) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74cb396080d0202745507029ad8d65c5">getAuthPtrSlotSymbol</a> (const TargetMachine &amp;TM, MachineModuleInfo *MMI, const MCSymbol *RawSym, AArch64PACKey::ID Key, uint16_t Discriminator) const</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile">AArch64_MachoTargetObjectFile</a> - This TLOF implementation is used for Darwin.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64\_MachoTargetObjectFile() {#a821a2de5466baeb8f887dd7c41b1b575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64_MachoTargetObjectFile::AArch64_MachoTargetObjectFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp">AArch64TargetObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a1db84bd65461646cde0085f4b02d5fa3">llvm::TargetLoweringObjectFile::SupportGOTPCRelWithOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAuthPtrSlotSymbol() {#a74cb396080d0202745507029ad8d65c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * AArch64_MachoTargetObjectFile::getAuthPtrSlotSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> * MMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * RawSym, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46">AArch64PACKey::ID</a> Key, uint16_t Discriminator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp">AArch64TargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp/#a0e2890f613a1a43228dec112d337340d">getAuthPtrSlotSymbolHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#a92d88d2c22a932066d294be13e2baf55">llvm::MachineModuleInfo::getObjFileInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>.</p>

</div>
</div>

### getCFIPersonalitySymbol() {#ab7b86bc2bb8a965529cb9c4ace6d7e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * AArch64_MachoTargetObjectFile::getCFIPersonalitySymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> * MMI)</td>
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



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp">AArch64TargetObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>.</p>

</div>
</div>

### getIndirectSymViaGOTPCRel() {#aab2cc2813c5a774bb4f83b6f9ae5a98b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * AArch64_MachoTargetObjectFile::getIndirectSymViaGOTPCRel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; MV, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> * MMI, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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

<p>Get the target specific PC relative GOT entry relocation.</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp">AArch64TargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a>.</p>

</div>
</div>

### getNameWithPrefix() {#ab74a50e826e0105a5a0f724700c5d5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64_MachoTargetObjectFile::getNameWithPrefix (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; OutName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp">AArch64TargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2156a9e22505242a9118da71e8054269">llvm::TargetLoweringObjectFile::getMangler</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>.</p>

</div>
</div>

### getTTypeGlobalReference() {#abda04e72e43a3aaef8a55e4ecf91d127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * AArch64_MachoTargetObjectFile::getTTypeGlobalReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, unsigned Encoding, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> * MMI, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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

<p>Return an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> to use for a reference to the specified global variable from exception handling information.</p>


<p>getTTypeGlobalReference - Return an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> to use for a reference to the specified global variable from exception handling information.</p>


<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp">AArch64TargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ac859bd9ec26a2398dd13f4f9262f0595">llvm::dwarf::DW_EH_PE_indirect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a18cb02c6dc96569494f65b82ab70487b">llvm::dwarf::DW_EH_PE_pcrel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#ae41814965809c6fb6403ca6338710a25">llvm::TargetLoweringObjectFileMachO::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp">AArch64TargetObjectFile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
