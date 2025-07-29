---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ppcelfstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCELFStreamer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::PPCELFStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-h">Target/PowerPC/MCTargetDesc/PPCELFStreamer.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac558199bf4ba000421543f08b7adf8f0">PPCELFStreamer</a> (MCContext &amp;Context, std::unique_ptr&lt; MCAsmBackend &gt; MAB, std::unique_ptr&lt; MCObjectWriter &gt; OW, std::unique_ptr&lt; MCCodeEmitter &gt; Emitter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd418120b6155f0727d4bbf2dfeafe97">emitInstruction</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></span> into the current section. <a href="#abd418120b6155f0727d4bbf2dfeafe97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad765ad35ceb5fb06da044f0f4d365a3b">emitLabel</a> (MCSymbol *Symbol, SMLoc Loc=SMLoc()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a label for <span class="doxyComputerOutput">Symbol</span> into the current section. <a href="#ad765ad35ceb5fb06da044f0f4d365a3b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc351030dd55aee2dbd9df17077a1c3f">emitPrefixedInstruction</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3112b2ade131a3d623e09b723b35032">emitGOTToPCRelReloc</a> (const MCInst &amp;Inst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad17d5781b6f55ab3a989d240b4e7e712">emitGOTToPCRelLabel</a> (const MCInst &amp;Inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4fc12bbc6a819a2d0bc64e03970c0b6">LastLabel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fcfc251bd967a82b18a7d0b9217f1f8">LastLabelLoc</a></td>
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


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-h">PPCELFStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCELFStreamer() {#ac558199bf4ba000421543f08b7adf8f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCELFStreamer::PPCELFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; MAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; Emitter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-h">PPCELFStreamer.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-cpp">PPCELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#aec09c5b9322b90f034d51bd3c0903563">llvm::MCELFStreamer::MCELFStreamer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitInstruction() {#abd418120b6155f0727d4bbf2dfeafe97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCELFStreamer::emitInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-h">PPCELFStreamer.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-cpp">PPCELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a92d2d1c2ac97f1151ed8f38d854e8b34">llvm::MCObjectStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a751b495bbd855f8fa28e98a3619c898a">llvm::MCAssembler::getEmitterPtr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc6a276f0a40e983e11fe851e818ad01">llvm::isPartOfGOTToPCRelPair</a>.</p>

</div>
</div>

### emitLabel() {#ad765ad35ceb5fb06da044f0f4d365a3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCELFStreamer::emitLabel (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Emit a label for <span class="doxyComputerOutput">Symbol</span> into the current section.</p>


<p>This corresponds to an assembler statement such as: foo:</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol to emit. A given symbol should only be emitted as a label once, and symbols emitted as a label should never be used in an assignment.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-h">PPCELFStreamer.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-cpp">PPCELFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#ac725449b95138e5297b8af02df828882">llvm::MCELFStreamer::emitLabel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitGOTToPCRelLabel() {#ad17d5781b6f55ab3a989d240b4e7e712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCELFStreamer::emitGOTToPCRelLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-h">PPCELFStreamer.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-cpp">PPCELFStreamer.cpp</a>.</p>

</div>
</div>

### emitGOTToPCRelReloc() {#ab3112b2ade131a3d623e09b723b35032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCELFStreamer::emitGOTToPCRelReloc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-h">PPCELFStreamer.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-cpp">PPCELFStreamer.cpp</a>.</p>

</div>
</div>

### emitPrefixedInstruction() {#acc351030dd55aee2dbd9df17077a1c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCELFStreamer::emitPrefixedInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-h">PPCELFStreamer.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-cpp">PPCELFStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LastLabel {#af4fc12bbc6a819a2d0bc64e03970c0b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::PPCELFStreamer::LastLabel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-h">PPCELFStreamer.h</a>.</p>

</div>
</div>

### LastLabelLoc {#a6fcfc251bd967a82b18a7d0b9217f1f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::PPCELFStreamer::LastLabelLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-h">PPCELFStreamer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-cpp">PPCELFStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfstreamer-h">PPCELFStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
