---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/systemzelftargetobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SystemZELFTargetObjectFile` Class Reference

<p>This implementation is used for <a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a> <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SystemZELFTargetObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetobjectfile-h">Target/SystemZ/SystemZTargetObjectFile.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad01acc6ff03acab3d587f760feca2c09">SystemZELFTargetObjectFile</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aa41b5373e9b1834047d254cf00e9f0">getDebugThreadLocalSymbol</a> (const MCSymbol *Sym) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Describe a TLS variable address within debug info. <a href="#a7aa41b5373e9b1834047d254cf00e9f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This implementation is used for <a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a> <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets.</p>

<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetobjectfile-h">SystemZTargetObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SystemZELFTargetObjectFile() {#ad01acc6ff03acab3d587f760feca2c09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SystemZELFTargetObjectFile::SystemZELFTargetObjectFile ()</td>
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



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetobjectfile-h">SystemZTargetObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDebugThreadLocalSymbol() {#a7aa41b5373e9b1834047d254cf00e9f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * SystemZELFTargetObjectFile::getDebugThreadLocalSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
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

<p>Describe a TLS variable address within debug info.</p>

<p>Declaration at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetobjectfile-h">SystemZTargetObjectFile.h</a>, definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetobjectfile-cpp">SystemZTargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a005feb527dcbfd0ff9cb36d5926259b5">llvm::MCSymbolRefExpr::VK_DTPOFF</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetobjectfile-cpp">SystemZTargetObjectFile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetobjectfile-h">SystemZTargetObjectFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
