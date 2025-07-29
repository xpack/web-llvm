---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aarch64-elftargetobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64_ELFTargetObjectFile` Class

<p>This implementation is used for <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets (Linux in particular). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AArch64_ELFTargetObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">Target/AArch64/AArch64TargetObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf">TargetLoweringObjectFileELF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1ed0ce5f0b61ff1d2cc70df8846add3">AArch64_ELFTargetObjectFile</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab479db6c0dce9d07c70ea70016ed99ff">getIndirectSymViaGOTPCRel</a> (const GlobalValue *GV, const MCSymbol *Sym, const MCValue &amp;MV, int64_t Offset, MachineModuleInfo *MMI, MCStreamer &amp;Streamer) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the target specific PC relative GOT entry relocation. <a href="#ab479db6c0dce9d07c70ea70016ed99ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa8c25d9479e583055f8cd02df823840">getAuthPtrSlotSymbol</a> (const TargetMachine &amp;TM, MachineModuleInfo *MMI, const MCSymbol *RawSym, AArch64PACKey::ID Key, uint16_t Discriminator) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50239bad1326b962fc58f1b311e7e255">emitPersonalityValueImpl</a> (MCStreamer &amp;Streamer, const DataLayout &amp;DL, const MCSymbol *Sym, const MachineModuleInfo *MMI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36edb1ffdc54ce6fc923afdf35abd063">Initialize</a> (MCContext &amp;Ctx, const TargetMachine &amp;TM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method must be called before any actual lowering is done. <a href="#a36edb1ffdc54ce6fc923afdf35abd063">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This implementation is used for <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets (Linux in particular).</p>

<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64\_ELFTargetObjectFile() {#ac1ed0ce5f0b61ff1d2cc70df8846add3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AArch64_ELFTargetObjectFile::AArch64_ELFTargetObjectFile ()</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#aeb52d995234fdf6809487cc889727516">llvm::TargetLoweringObjectFileELF::PLTRelativeVariantKind</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2591aeb850ebb8374e27efd823bda866">llvm::TargetLoweringObjectFile::SupportIndirectSymViaGOTPCRel</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">llvm::MCSymbolRefExpr::VK_PLT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitPersonalityValueImpl() {#a50239bad1326b962fc58f1b311e7e255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64_ELFTargetObjectFile::emitPersonalityValueImpl (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> * MMI)</td>
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



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp">AArch64TargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#acf36aff5a25265c3165e94a9ba5ab078">llvm::TargetLoweringObjectFileELF::emitPersonalityValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#a92d88d2c22a932066d294be13e2baf55">llvm::MachineModuleInfo::getObjFileInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a901607e60c20148ae701b6e8f43b4647">llvm::MCStreamer::getTargetStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoelf/#a8ed90bfbfc1ad64f7fce9458287b79cc">llvm::MachineModuleInfoELF::hasSignedPersonality</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46aaf2ff1a10f3f3b211d7781a33e4c1e05">llvm::AArch64PACKey::IA</a>.</p>

</div>
</div>

### getAuthPtrSlotSymbol() {#afa8c25d9479e583055f8cd02df823840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * AArch64_ELFTargetObjectFile::getAuthPtrSlotSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> * MMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * RawSym, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46">AArch64PACKey::ID</a> Key, uint16_t Discriminator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp">AArch64TargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp/#a0e2890f613a1a43228dec112d337340d">getAuthPtrSlotSymbolHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#a92d88d2c22a932066d294be13e2baf55">llvm::MachineModuleInfo::getObjFileInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>.</p>

</div>
</div>

### getIndirectSymViaGOTPCRel() {#ab479db6c0dce9d07c70ea70016ed99ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * AArch64_ELFTargetObjectFile::getIndirectSymViaGOTPCRel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; MV, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> * MMI, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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

<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp">AArch64TargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2a25c9a7112bb84b5d93e6ab5d0d8185">llvm::MCSymbolRefExpr::VK_GOTPCREL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### Initialize() {#a36edb1ffdc54ce6fc923afdf35abd063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64_ELFTargetObjectFile::Initialize (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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

<p>This method must be called before any actual lowering is done.</p>


<p>Initialize - this method must be called before any actual lowering is done.</p>


<p>This specifies the current context for codegen, and gives the lowering implementations a chance to set up their default sections.</p>


<p>Declaration at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp">AArch64TargetObjectFile.cpp</a>.</p>

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
