---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ppctargetstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCTargetStreamer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::PPCTargetStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetstreamer-h">Target/PowerPC/PPCTargetStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific streamer interface. <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetasmstreamer">PPCTargetAsmStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetelfstreamer">PPCTargetELFStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetmachostreamer">PPCTargetMachOStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetxcoffstreamer">PPCTargetXCOFFStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06730371ef24cd3a2d6c188a77752185">PPCTargetStreamer</a> (MCStreamer &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0666216611ffe7d9aedf9d77bfa154e1">~PPCTargetStreamer</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a946f30e129dd31ad2843da751b7606ef">emitTCEntry</a> (const MCSymbol &amp;S, MCSymbolRefExpr::VariantKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae380aaa91f14f59c81afc2bdf5cc52">emitMachine</a> (StringRef CPU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b7016c299f7de1c5969cb7db2892d2f">emitAbiVersion</a> (int AbiVersion)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a17fcc857e0a6ffca2cb0b635394beb">emitLocalEntry</a> (MCSymbolELF *S, const MCExpr *LocalOffset)</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetstreamer-h">PPCTargetStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCTargetStreamer() {#a06730371ef24cd3a2d6c188a77752185}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCTargetStreamer::PPCTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetstreamer-h">PPCTargetStreamer.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp">PPCMCTargetDesc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#acfff4f9a518231ee043200a694fcbafa">llvm::MCTargetStreamer::MCTargetStreamer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetasmstreamer/#a643749c1f3d23fd8f0622aef89f131e0">anonymous{PPCMCTargetDesc.cpp}::PPCTargetAsmStreamer::PPCTargetAsmStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetelfstreamer/#adfae32c00ec138a29337ef73efaaa2fb">anonymous{PPCMCTargetDesc.cpp}::PPCTargetELFStreamer::PPCTargetELFStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetmachostreamer/#a87475101fb2b8fb9903595ae1e41d46c">anonymous{PPCMCTargetDesc.cpp}::PPCTargetMachOStreamer::PPCTargetMachOStreamer</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcmctargetdesc-cpp-/ppctargetxcoffstreamer/#aa7be5852a81a15c32ef5a039fa0038e8">anonymous{PPCMCTargetDesc.cpp}::PPCTargetXCOFFStreamer::PPCTargetXCOFFStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PPCTargetStreamer() {#a0666216611ffe7d9aedf9d77bfa154e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCTargetStreamer::~PPCTargetStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetstreamer-h">PPCTargetStreamer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitAbiVersion() {#a1b7016c299f7de1c5969cb7db2892d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::PPCTargetStreamer::emitAbiVersion (int AbiVersion)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetstreamer-h">PPCTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#ac7b652d5871240542b523c9d9fd950b5">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### emitLocalEntry() {#a9a17fcc857e0a6ffca2cb0b635394beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::PPCTargetStreamer::emitLocalEntry (<a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LocalOffset)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetstreamer-h">PPCTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a0e3f4587b93083fdc01e3ec8f66b3701">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitFunctionBodyStart</a>.</p>

</div>
</div>

### emitMachine() {#afae380aaa91f14f59c81afc2bdf5cc52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::PPCTargetStreamer::emitMachine (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetstreamer-h">PPCTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a>.</p>

</div>
</div>

### emitTCEntry() {#a946f30e129dd31ad2843da751b7606ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::PPCTargetStreamer::emitTCEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985">MCSymbolRefExpr::VariantKind</a> Kind)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetstreamer-h">PPCTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#aa667597fe6ef3ceceb450890b00fefad">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitEndOfAsmFile</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#ac8c4251bf69ea6c9c941658a83bc9ec4">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitEndOfAsmFile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp">PPCMCTargetDesc.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetstreamer-h">PPCTargetStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
