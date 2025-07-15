---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/x86-64elftargetobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86_64ELFTargetObjectFile` Class Reference

<p>This implementation is used for X86_64 <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets, and defers to <a href="/web-llvm/docs/api/classes/llvm/x86elftargetobjectfile">X86ELFTargetObjectFile</a> for commonalities with 32-bit targets. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::X86_64ELFTargetObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetobjectfile-h">Target/X86/X86TargetObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/x86elftargetobjectfile">X86ELFTargetObjectFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This implementation is used for <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets that don't have a further specialization (and as a base class for X86_64, which does). <a href="/web-llvm/docs/api/classes/llvm/x86elftargetobjectfile/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e8f95e4147907fdfff44e082a5f5248">X86_64ELFTargetObjectFile</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fade16e9dc1ebc9b6974b12857f5abe">getIndirectSymViaGOTPCRel</a> (const GlobalValue *GV, const MCSymbol *Sym, const MCValue &amp;MV, int64_t Offset, MachineModuleInfo *MMI, MCStreamer &amp;Streamer) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the target specific PC relative GOT entry relocation. <a href="#a7fade16e9dc1ebc9b6974b12857f5abe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This implementation is used for X86_64 <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets, and defers to <a href="/web-llvm/docs/api/classes/llvm/x86elftargetobjectfile">X86ELFTargetObjectFile</a> for commonalities with 32-bit targets.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetobjectfile-h">X86TargetObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86\_64ELFTargetObjectFile() {#a5e8f95e4147907fdfff44e082a5f5248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::X86_64ELFTargetObjectFile::X86_64ELFTargetObjectFile ()</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetobjectfile-h">X86TargetObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2591aeb850ebb8374e27efd823bda866">llvm::TargetLoweringObjectFile::SupportIndirectSymViaGOTPCRel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getIndirectSymViaGOTPCRel() {#a7fade16e9dc1ebc9b6974b12857f5abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * X86_64ELFTargetObjectFile::getIndirectSymViaGOTPCRel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; MV, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> * MMI, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetobjectfile-h">X86TargetObjectFile.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetobjectfile-cpp">X86TargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2a25c9a7112bb84b5d93e6ab5d0d8185">llvm::MCSymbolRefExpr::VK_GOTPCREL</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetobjectfile-cpp">X86TargetObjectFile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetobjectfile-h">X86TargetObjectFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
