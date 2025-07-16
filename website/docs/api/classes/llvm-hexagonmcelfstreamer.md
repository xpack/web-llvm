---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/hexagonmcelfstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HexagonMCELFStreamer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::HexagonMCELFStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-h">Target/Hexagon/MCTargetDesc/HexagonMCELFStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer">MCELFStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9436bfa1d0740af8c93bcb8bda0d1d44">HexagonMCELFStreamer</a> (MCContext &amp;Context, std::unique_ptr&lt; MCAsmBackend &gt; TAB, std::unique_ptr&lt; MCObjectWriter &gt; OW, std::unique_ptr&lt; MCCodeEmitter &gt; Emitter)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf4c03302466c28c8a1cdd267060cad5">HexagonMCELFStreamer</a> (MCContext &amp;Context, std::unique_ptr&lt; MCAsmBackend &gt; TAB, std::unique_ptr&lt; MCObjectWriter &gt; OW, std::unique_ptr&lt; MCCodeEmitter &gt; Emitter, MCAssembler *Assembler)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706aa084f85cdf448e79ad2d8be30bff">emitInstruction</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></span> into the current section. <a href="#a706aa084f85cdf448e79ad2d8be30bff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c8aaade94f26b9991cee49ae53bdadb">EmitSymbol</a> (const MCInst &amp;Inst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51052f1e0d005332637e592f961d951b">HexagonMCEmitLocalCommonSymbol</a> (MCSymbol *Symbol, uint64_t Size, Align ByteAlignment, unsigned AccessSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f1accd42a5eb6c0d80c800e63123b9">HexagonMCEmitCommonSymbol</a> (MCSymbol *Symbol, uint64_t Size, Align ByteAlignment, unsigned AccessSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a110d98c1e2e4e1f3d24e48db4329d211">MCII</a></td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-h">HexagonMCELFStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonMCELFStreamer() {#a9436bfa1d0740af8c93bcb8bda0d1d44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonMCELFStreamer::HexagonMCELFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; TAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; Emitter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-h">HexagonMCELFStreamer.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-cpp">HexagonMCELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa982b3d4867712314f94ac9d9006ee03">llvm::createHexagonMCInstrInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#aec09c5b9322b90f034d51bd3c0903563">llvm::MCELFStreamer::MCELFStreamer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### HexagonMCELFStreamer() {#abf4c03302466c28c8a1cdd267060cad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonMCELFStreamer::HexagonMCELFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; TAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; Emitter, <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> * Assembler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-h">HexagonMCELFStreamer.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-cpp">HexagonMCELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa982b3d4867712314f94ac9d9006ee03">llvm::createHexagonMCInstrInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#aec09c5b9322b90f034d51bd3c0903563">llvm::MCELFStreamer::MCELFStreamer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitInstruction() {#a706aa084f85cdf448e79ad2d8be30bff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCELFStreamer::emitInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Emit the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></span> into the current section.</p>

<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-h">HexagonMCELFStreamer.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-cpp">HexagonMCELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a607343a05725b53e0d5bd85a4a44586e">llvm::HexagonMCInstrInfo::bundleInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a246da06f2e49f678663ae6e21bedffb3">llvm::HexagonMCInstrInfo::bundleSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a92d2d1c2ac97f1151ed8f38d854e8b34">llvm::MCObjectStreamer::emitInstruction</a>, <a href="#a8c8aaade94f26b9991cee49ae53bdadb">EmitSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a8f76c0f5e34856920717e06ebc5f4dc3">HEXAGON_PACKET_SIZE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### EmitSymbol() {#a8c8aaade94f26b9991cee49ae53bdadb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCELFStreamer::EmitSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-h">HexagonMCELFStreamer.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-cpp">HexagonMCELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>


<p>Referenced by <a href="#a706aa084f85cdf448e79ad2d8be30bff">emitInstruction</a>.</p>

</div>
</div>

### HexagonMCEmitCommonSymbol() {#a64f1accd42a5eb6c0d80c800e63123b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCELFStreamer::HexagonMCEmitCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment, unsigned AccessSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-h">HexagonMCELFStreamer.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-cpp">HexagonMCELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a37c1fdede126353d80c3753dfe06f3c7">llvm::bit_width</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#ac725449b95138e5297b8af02df828882">llvm::MCELFStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a1df557a00a6e2c67a971eccd3a06ece4">llvm::MCELFStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae77a5b8d3af591a461aeac723de33240">llvm::MCStreamer::emitZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a0675ed1bdbf987d94ef2360cb18c6eae">llvm::MCAssembler::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ad946e0775ff08232ff6dc1bd9a8ed9bb">llvm::MCStreamer::getCurrentSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a3fddc32fd70ea36b8482c9055eb68c40">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-cpp/#a1760f12f0488d054479e8793e260de94">GPSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f42ed6fd2569fa43f03814a17f9d94a">llvm::Log2_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a366e4bc69bde6c253d7fc89d02ac9464a9a9b2bfc7328ff060a9114f9d6eac3e9">llvm::ELF::SHN_HEXAGON_SCOMMON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a3056225276d5d76c1b142d3505704851">llvm::ELF::STB_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a9803bad2cfdce7601000ee3f6b979d9b">llvm::ELF::STT_OBJECT</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetelfstreamer/#a096c69148815a0db0e2bc9ec21d5a52b">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetELFStreamer::emitCommonSymbolSorted</a> and <a href="#a51052f1e0d005332637e592f961d951b">HexagonMCEmitLocalCommonSymbol</a>.</p>

</div>
</div>

### HexagonMCEmitLocalCommonSymbol() {#a51052f1e0d005332637e592f961d951b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonMCELFStreamer::HexagonMCEmitLocalCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment, unsigned AccessSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-h">HexagonMCELFStreamer.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-cpp">HexagonMCELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="#a64f1accd42a5eb6c0d80c800e63123b9">HexagonMCEmitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetelfstreamer/#a9b32dd33300c8425b92566c6ac4d9c86">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetELFStreamer::emitLocalCommonSymbolSorted</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MCII {#a110d98c1e2e4e1f3d24e48db4329d211}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCInstrInfo&gt; llvm::HexagonMCELFStreamer::MCII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-h">HexagonMCELFStreamer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-cpp">HexagonMCELFStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcelfstreamer-h">HexagonMCELFStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
