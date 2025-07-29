---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCLinuxAsmPrinter` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter">PPCLinuxAsmPrinter</a> - PowerPC assembly printer, customized for Linux. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter">PPCAsmPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c814a47b8f04900dc9efa78d9f76a3b">PPCLinuxAsmPrinter</a> (TargetMachine &amp;TM, std::unique_ptr&lt; MCStreamer &gt; Streamer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec8b6021b3340d7dbee82f8289c2fab">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a1ec8b6021b3340d7dbee82f8289c2fab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af305a78272ba50ce406878a0fc0654ba">emitGNUAttributes</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b652d5871240542b523c9d9fd950b5">emitStartOfAsmFile</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This virtual method can be overridden by targets that want to emit something at the start of their file. <a href="#ac7b652d5871240542b523c9d9fd950b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c4251bf69ea6c9c941658a83bc9ec4">emitEndOfAsmFile</a> (Module &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This virtual method can be overridden by targets that want to emit something at the end of their file. <a href="#ac8c4251bf69ea6c9c941658a83bc9ec4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac456206c08bdce2e1a11cf14b316bc9a">emitFunctionEntryLabel</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitFunctionEntryLabel - Emit the label that is the entrypoint for the function. <a href="#ac456206c08bdce2e1a11cf14b316bc9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3f4587b93083fdc01e3ec8f66b3701">emitFunctionBodyStart</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitFunctionBodyStart - Emit a global entry point prefix for ELFv2. <a href="#a0e3f4587b93083fdc01e3ec8f66b3701">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f7d295492d6b2992bc084b59a00557c">emitFunctionBodyEnd</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitFunctionBodyEnd - Print the traceback table before the .size directive. <a href="#a4f7d295492d6b2992bc084b59a00557c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4123a254ab36bc97c087331e6cb38665">emitInstruction</a> (const MachineInstr *MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitInstruction – Print out a single PowerPC MI in Darwin syntax to the current output stream. <a href="#a4123a254ab36bc97c087331e6cb38665">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter">PPCLinuxAsmPrinter</a> - PowerPC assembly printer, customized for Linux.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCLinuxAsmPrinter() {#a8c814a47b8f04900dc9efa78d9f76a3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::PPCLinuxAsmPrinter (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &gt; Streamer)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a6ff58b45ac27585d64b06c4c511203af">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::PPCAsmPrinter</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a62fefc41d89d22d96ef82c2537da4343">createPPCAsmPrinterPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitEndOfAsmFile() {#ac8c4251bf69ea6c9c941658a83bc9ec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCLinuxAsmPrinter::emitEndOfAsmFile (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>This virtual method can be overridden by targets that want to emit something at the end of their file.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a7c9a3fd165029985d3d43de5226da4e3">llvm::AsmPrinter::emitEndOfAsmFile</a>, <a href="#af305a78272ba50ce406878a0fc0654ba">emitGNUAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetstreamer/#a946f30e129dd31ad2843da751b7606ef">llvm::PPCTargetStreamer::emitTCEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae4a28f2ce2647934f469d4bb2144612a">llvm::AsmPrinter::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aaac6d709ea6a14a69a632a3685936c92">llvm::AsmPrinter::GetExternalSymbolSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a47692fd7344d1adc2916ad4cc31d26c8">llvm::AsmPrinter::MAI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a2a9f5abc8bc96c0f6aad7e8a2ef5e343">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::TOC</a>.</p>

</div>
</div>

### emitFunctionBodyEnd() {#a4f7d295492d6b2992bc084b59a00557c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCLinuxAsmPrinter::emitFunctionBodyEnd ()</td>
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

<p>EmitFunctionBodyEnd - Print the traceback table before the .size directive.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ae2d680022bd0368819b4d6f511765a13">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::Subtarget</a>.</p>

</div>
</div>

### emitFunctionBodyStart() {#a0e3f4587b93083fdc01e3ec8f66b3701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCLinuxAsmPrinter::emitFunctionBodyStart ()</td>
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

<p>EmitFunctionBodyStart - Emit a global entry point prefix for ELFv2.</p>

<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a4f49f04c5de0799837b4c349c1db8ce2">llvm::PPCMCExpr::createHa</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a4cc67dcfb3533e94b42341e10b8ffe76">llvm::PPCMCExpr::createLo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa06f7388d0cc9b44ece08cdf56c0ecf0">llvm::AsmPrinter::CurrentFnSym</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetstreamer/#a9a17fcc857e0a6ffca2cb0b635394beb">llvm::PPCTargetStreamer::emitLocalEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b02eda9bb97934fbcc3d7f29219b931">llvm::AsmPrinter::EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a2455497c6e33bcd6363fbecc2fe00f0a">llvm::PPCFunctionInfo::getGlobalEPSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a265951c79bd6867cd86f173112f3cc55">llvm::PPCFunctionInfo::getLocalEPSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a95a4a415a083d19b0a8f92cabb81c720">llvm::PPCFunctionInfo::getTOCOffsetSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ae2d680022bd0368819b4d6f511765a13">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::Subtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a6017bce5768f09c7cdbe312e90962dda">llvm::PPCFunctionInfo::usesTOCBasePtr</a>.</p>

</div>
</div>

### emitFunctionEntryLabel() {#ac456206c08bdce2e1a11cf14b316bc9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCLinuxAsmPrinter::emitFunctionEntryLabel ()</td>
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

<p>EmitFunctionEntryLabel - Emit the label that is the entrypoint for the function.</p>


<p>This can be overridden by targets as required to do custom stuff.</p>


<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa06f7388d0cc9b44ece08cdf56c0ecf0">llvm::AsmPrinter::CurrentFnSym</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ace3ea8c3465c0162820996b0f009d26a">llvm::AsmPrinter::CurrentFnSymForSize</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae8edc50d690d43b67f033f0acf46cd04">llvm::AsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a2455497c6e33bcd6363fbecc2fe00f0a">llvm::PPCFunctionInfo::getGlobalEPSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a123bd4a5c86831ea657817f781102eaf">llvm::PPCFunctionInfo::getPICOffsetSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a95a4a415a083d19b0a8f92cabb81c720">llvm::PPCFunctionInfo::getTOCOffsetSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ab2fdacf803a7a00c831b1e3c068a5ce8">llvm::AsmPrinter::isPositionIndependent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/piclevel/#a66ddbf1bb21f90ddc44260d1ca677b6ba930654495acf7b77bcf00f2c65c32347">llvm::PICLevel::SmallPIC</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ae2d680022bd0368819b4d6f511765a13">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::Subtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a488e8422444868d47101cb1b7c3fd51d">llvm::PPCFunctionInfo::usesPICBase</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a6cd4a312e47b0e61f2dcabb3889abe66">llvm::MCSymbolRefExpr::VK_PPC_TOCBASE</a>.</p>

</div>
</div>

### emitGNUAttributes() {#af305a78272ba50ce406878a0fc0654ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCLinuxAsmPrinter::emitGNUAttributes (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcasmprinter-cpp-/#a008376669674688e9280675f9552c4afae26c9cbb7403c0692cf9fb7429d4fb57">anonymous{PPCAsmPrinter.cpp}::Tag_GNU_Power_ABI_FP</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcasmprinter-cpp-/#a008376669674688e9280675f9552c4afa3e272a78e7dfb37b37bb7987d1744eec">anonymous{PPCAsmPrinter.cpp}::Val_GNU_Power_ABI_HardFloat_DP</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcasmprinter-cpp-/#a008376669674688e9280675f9552c4afa387167cb78fb06bc9a3821f6bdcb083b">anonymous{PPCAsmPrinter.cpp}::Val_GNU_Power_ABI_LDBL_64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcasmprinter-cpp-/#a008376669674688e9280675f9552c4afaa87cb16bc12bfdd71d36bf41aa5be8f4">anonymous{PPCAsmPrinter.cpp}::Val_GNU_Power_ABI_LDBL_IBM128</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-ppcasmprinter-cpp-/#a008376669674688e9280675f9552c4afa21fad3ed9ecb602ac2deec774c7d21cc">anonymous{PPCAsmPrinter.cpp}::Val_GNU_Power_ABI_LDBL_IEEE128</a>.</p>


<p>Referenced by <a href="#ac8c4251bf69ea6c9c941658a83bc9ec4">emitEndOfAsmFile</a>.</p>

</div>
</div>

### emitInstruction() {#a4123a254ab36bc97c087331e6cb38665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCLinuxAsmPrinter::emitInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>EmitInstruction – Print out a single PowerPC MI in Darwin syntax to the current output stream.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#ad824e6c64e2015a9fbaba9a4c9d0a7b9">llvm::MCInstBuilder::addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#a2b9700052102985a61c9cf62b71d68f0">llvm::MCInstBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b02eda9bb97934fbcc3d7f29219b931">llvm::AsmPrinter::EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac40b688a96b903167e07f7555c2a1e11ac5a963d0fca7d2453c04dda884ebda0f">llvm::AsmPrinter::FUNCTION_ENTER</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac40b688a96b903167e07f7555c2a1e11a9fc24e2ef1ac1d5634e9def062cc94ee">llvm::AsmPrinter::FUNCTION_EXIT</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aebe7e48735a59049062e384e810c108a">llvm::AsmPrinter::getSubtargetInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a975319b2f772b89387ffea1b1ba1f049">llvm::PPC::InvertPredicate</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a261510478c31d3a3f1537bddd746a421">llvm::LowerPPCMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a47692fd7344d1adc2916ad4cc31d26c8">llvm::AsmPrinter::MAI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a7c868807760d76531432d5a31b6938dc">llvm::AsmPrinter::recordSled</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ae2d680022bd0368819b4d6f511765a13">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::Subtarget</a>.</p>

</div>
</div>

### emitStartOfAsmFile() {#ac7b652d5871240542b523c9d9fd950b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCLinuxAsmPrinter::emitStartOfAsmFile (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>This virtual method can be overridden by targets that want to emit something at the start of their file.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetstreamer/#a1b7016c299f7de1c5969cb7db2892d2f">llvm::PPCTargetStreamer::emitAbiVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a61cd2b013b5c017cb253fd02242de1c1">llvm::AsmPrinter::emitStartOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a0580b05cc0794957d4ac1ce2f209ac87">llvm::AsmPrinter::getObjFileLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ab2fdacf803a7a00c831b1e3c068a5ce8">llvm::AsmPrinter::isPositionIndependent</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/piclevel/#a66ddbf1bb21f90ddc44260d1ca677b6ba930654495acf7b77bcf00f2c65c32347">llvm::PICLevel::SmallPIC</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>

</div>
</div>

### getPassName() {#a1ec8b6021b3340d7dbee82f8289c2fab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
