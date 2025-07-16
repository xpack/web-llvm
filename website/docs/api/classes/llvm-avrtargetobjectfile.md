---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/avrtargetobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AVRTargetObjectFile` Class Reference

<p>Lowering for an <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> ELF32 object file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AVRTargetObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-h">Target/AVR/AVRTargetObjectFile.h</a>"
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf">TargetLoweringObjectFileELF</a> <a href="#a1883e4ae26664e722c99f4c7442ede19">Base</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea43cdda6a483d7a93fc2adbb0d3297c">Initialize</a> (MCContext &amp;ctx, const TargetMachine &amp;TM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method must be called before any actual lowering is done. <a href="#aea43cdda6a483d7a93fc2adbb0d3297c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ac5016664f09fbfd8b97a954fccd664">SelectSectionForGlobal</a> (const GlobalObject *GO, SectionKind Kind, const TargetMachine &amp;TM) const override</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a676cb7001440cba8c150cb2d65ca545a">ProgmemDataSection</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adedecd463e09f96bd58bcfedbbfdbe69">Progmem1DataSection</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa178dfde8ecf8361dd8f7a51dc245e40">Progmem2DataSection</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea735f88099a65ecb20dfa66939930e">Progmem3DataSection</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa76917e151229c8a1e85b8748df15f2e">Progmem4DataSection</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb062b5bad052effd93981519a5bb4d">Progmem5DataSection</a></td>
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

<p>Lowering for an <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> ELF32 object file.</p>

<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-h">AVRTargetObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Base {#a1883e4ae26664e722c99f4c7442ede19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef TargetLoweringObjectFileELF llvm::AVRTargetObjectFile::Base</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-h">AVRTargetObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Initialize() {#aea43cdda6a483d7a93fc2adbb0d3297c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRTargetObjectFile::Initialize (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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


<p>Declaration at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-h">AVRTargetObjectFile.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-cpp">AVRTargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2793bce814c8f8c6fc2f41d4156a4ebb">llvm::TargetLoweringObjectFileELF::Initialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>.</p>

</div>
</div>

### SelectSectionForGlobal() {#a2ac5016664f09fbfd8b97a954fccd664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * llvm::AVRTargetObjectFile::SelectSectionForGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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



<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-h">AVRTargetObjectFile.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-cpp">AVRTargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/avr/#a72f5caee7436dfc130b92f2545cf727b">llvm::AVR::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ade7dc7510e950cd1c1181138b390f965">llvm::GlobalObject::hasSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#aaef9228fcde19f54da2a08e85cbb25af">llvm::AVR::isProgramMemoryAddress</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ab7fa9bb927a227efb1a38db426c5aaf6a467a127a5b333ac481886bc438195f39">llvm::AVR::ProgramMemory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ab7fa9bb927a227efb1a38db426c5aaf6a7f665801fc3404179d216811ff0e078e">llvm::AVR::ProgramMemory1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ab7fa9bb927a227efb1a38db426c5aaf6a50e0252b5e7ef8f8436a17833c68e129">llvm::AVR::ProgramMemory2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ab7fa9bb927a227efb1a38db426c5aaf6afc31612b630161a10ae6136e5269a838">llvm::AVR::ProgramMemory3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ab7fa9bb927a227efb1a38db426c5aaf6a7c223f9bbe2b2c14ae004a7881ce50b0">llvm::AVR::ProgramMemory4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#ab7fa9bb927a227efb1a38db426c5aaf6ab548472c1931ea8aab10863b9976bbec">llvm::AVR::ProgramMemory5</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a7c532f94d6bb9c4aba4190b81a7f8dbf">llvm::TargetLoweringObjectFileELF::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Progmem1DataSection {#adedecd463e09f96bd58bcfedbbfdbe69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::AVRTargetObjectFile::Progmem1DataSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-h">AVRTargetObjectFile.h</a>.</p>

</div>
</div>

### Progmem2DataSection {#aa178dfde8ecf8361dd8f7a51dc245e40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::AVRTargetObjectFile::Progmem2DataSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-h">AVRTargetObjectFile.h</a>.</p>

</div>
</div>

### Progmem3DataSection {#a2ea735f88099a65ecb20dfa66939930e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::AVRTargetObjectFile::Progmem3DataSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-h">AVRTargetObjectFile.h</a>.</p>

</div>
</div>

### Progmem4DataSection {#aa76917e151229c8a1e85b8748df15f2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::AVRTargetObjectFile::Progmem4DataSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-h">AVRTargetObjectFile.h</a>.</p>

</div>
</div>

### Progmem5DataSection {#a8bb062b5bad052effd93981519a5bb4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::AVRTargetObjectFile::Progmem5DataSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-h">AVRTargetObjectFile.h</a>.</p>

</div>
</div>

### ProgmemDataSection {#a676cb7001440cba8c150cb2d65ca545a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::AVRTargetObjectFile::ProgmemDataSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-h">AVRTargetObjectFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-cpp">AVRTargetObjectFile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetobjectfile-h">AVRTargetObjectFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
