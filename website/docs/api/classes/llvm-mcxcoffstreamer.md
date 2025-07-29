---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcxcoffstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCXCOFFStreamer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCXCOFFStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">llvm/MC/MCXCOFFStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Streaming object file generation interface. <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppcxcoffstreamer">PPCXCOFFStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b7d35e652afcfe9d01785d07682c93b">MCXCOFFStreamer</a> (MCContext &amp;Context, std::unique_ptr&lt; MCAsmBackend &gt; MAB, std::unique_ptr&lt; MCObjectWriter &gt; OW, std::unique_ptr&lt; MCCodeEmitter &gt; Emitter)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xcoffobjectwriter">XCOFFObjectWriter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a414bcbdab3e76ffd4609ebf292f71bbc">getWriter</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc1c68d65e64e951a0f7d2a67dc80719">emitSymbolAttribute</a> (MCSymbol *Symbol, MCSymbolAttr Attribute) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></span> to <span class="doxyComputerOutput">Symbol</span>. <a href="#afc1c68d65e64e951a0f7d2a67dc80719">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aac14b3e4ad12e94a2d1a3ec2263b93">emitCommonSymbol</a> (MCSymbol *Symbol, uint64_t Size, Align ByteAlignment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a common symbol. <a href="#a3aac14b3e4ad12e94a2d1a3ec2263b93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4b7ae739c86b3799bba662ca1f3314">emitZerofill</a> (MCSection *Section, MCSymbol *Symbol=nullptr, uint64_t Size=0, Align ByteAlignment=Align(1), SMLoc Loc=SMLoc()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the zerofill section and an optional symbol. <a href="#a4c4b7ae739c86b3799bba662ca1f3314">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dc19532d6ff14ce17e330c87e60411d">emitInstToData</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44931c282d0b62ee7de97bfb46eaf847">emitXCOFFLocalCommonSymbol</a> (MCSymbol *LabelSym, uint64_t Size, MCSymbol *CsectSym, Align Alignment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits an lcomm directive with <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> csect information. <a href="#a44931c282d0b62ee7de97bfb46eaf847">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af980fe7c2238f4ce0ac3b6a5df32bea4">emitXCOFFSymbolLinkageWithVisibility</a> (MCSymbol *Symbol, MCSymbolAttr Linkage, MCSymbolAttr Visibility) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a symbol's linkage and visibility with a linkage directive for <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a>. <a href="#af980fe7c2238f4ce0ac3b6a5df32bea4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f3eb9157be6847f5bf0f9cd228ad01">emitXCOFFRefDirective</a> (const MCSymbol *Symbol) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> .ref directive which creates R_REF type entry in the relocation table for one or more symbols. <a href="#a74f3eb9157be6847f5bf0f9cd228ad01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf384fd884f5ad2bec1307548dddb21f">emitXCOFFRenameDirective</a> (const MCSymbol *Name, StringRef Rename) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> .rename directive which creates a synonym for an illegal or undesirable name. <a href="#acf384fd884f5ad2bec1307548dddb21f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91f7f40ccdbea928f3aee0fdf1ba8b56">emitXCOFFExceptDirective</a> (const MCSymbol *Symbol, const MCSymbol *Trap, unsigned Lang, unsigned Reason, unsigned FunctionSize, bool hasDebug) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> .except directive which adds information about a trap instruction to the object file exception section. <a href="#a91f7f40ccdbea928f3aee0fdf1ba8b56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46be67680c12c7fbf655011203ddcce">emitXCOFFCInfoSym</a> (StringRef Name, StringRef Metadata) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a C_INFO symbol with <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> embedded metadata to the .info section. <a href="#af46be67680c12c7fbf655011203ddcce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCXCOFFStreamer() {#a7b7d35e652afcfe9d01785d07682c93b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCXCOFFStreamer::MCXCOFFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; MAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; Emitter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ad1da683a018add519fd96cd22cc785">llvm::MCObjectStreamer::MCObjectStreamer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcxcoffstreamer/#a6327661699bd482538dcf1a0ffd6af0f">llvm::PPCXCOFFStreamer::PPCXCOFFStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitCommonSymbol() {#a3aac14b3e4ad12e94a2d1a3ec2263b93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCXCOFFStreamer::emitCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment)</td>
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

<p>Emit a common symbol.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The common symbol to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the common symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteAlignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70aeffba1492a002e3d506d9eca64672a24">llvm::XCOFF::C_HIDEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a21d70037ecf679b5f8d13af07f8f136a">llvm::MCObjectStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae77a5b8d3af591a461aeac723de33240">llvm::MCStreamer::emitZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a44931c282d0b62ee7de97bfb46eaf847">emitXCOFFLocalCommonSymbol</a>.</p>

</div>
</div>

### emitInstToData() {#a4dc19532d6ff14ce17e330c87e60411d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCXCOFFStreamer::emitInstToData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3558114ca72d34962abb28004d864b19">llvm::MCObjectStreamer::getOrCreateDataFragment</a>.</p>

</div>
</div>

### emitSymbolAttribute() {#afc1c68d65e64e951a0f7d2a67dc80719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCXCOFFStreamer::emitSymbolAttribute (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Attribute)</td>
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

<p>Add the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></span> to <span class="doxyComputerOutput">Symbol</span>.</p>

<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a19f57c169e86a4332accccf291954261">llvm::XCOFF::C_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70aeffba1492a002e3d506d9eca64672a24">llvm::XCOFF::C_HIDEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a8f5d26c17483f47bf923e263a4de4c2e">llvm::XCOFF::C_WEAKEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ab79bc663bb12acbf83bd10cdcfdd037e">llvm::MCSA_Cold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a345961d937ffac378faab680906913d6">llvm::MCSA_Exported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ab11aa8a54bc3faf1ef7db38e4bf4fb60">llvm::MCSA_Extern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243aa1e94c23156e37812e4d6e078af1d728">llvm::MCSA_Global</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ae472359b991bb5235c8f6714f4cacb6a">llvm::MCSA_Hidden</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ae5c5c7dd59c0c23f91be2b9c8f2594c9">llvm::MCSA_LGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a1f47433b83f2818076a3cf55b500233a">llvm::MCSA_Protected</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a83df6138e7dba38c0c80380486544ea0">llvm::MCSA_Weak</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a8a4cb520e5c6a7e39926cfe8dae0b73ea6077f0f2b971e50bbacbc960260a8008">llvm::XCOFF::SYM_V_EXPORTED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a8a4cb520e5c6a7e39926cfe8dae0b73ea5f87b6d679c546ae79ee03411c54a15f">llvm::XCOFF::SYM_V_HIDDEN</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a8a4cb520e5c6a7e39926cfe8dae0b73ea0eee4603371bd48180d987e3600ce5b6">llvm::XCOFF::SYM_V_PROTECTED</a>.</p>


<p>Referenced by <a href="#af980fe7c2238f4ce0ac3b6a5df32bea4">emitXCOFFSymbolLinkageWithVisibility</a>.</p>

</div>
</div>

### emitXCOFFCInfoSym() {#af46be67680c12c7fbf655011203ddcce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCXCOFFStreamer::emitXCOFFCInfoSym (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Metadata)</td>
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

<p>Emit a C_INFO symbol with <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> embedded metadata to the .info section.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>- The embedded metadata name</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/metadata"&gt;Metadata&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The embedded metadata</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/xcoffobjectwriter/#abffa5af353a498e8248e27a7fdcdbbab">llvm::XCOFFObjectWriter::addCInfoSymEntry</a> and <a href="#a414bcbdab3e76ffd4609ebf292f71bbc">getWriter</a>.</p>

</div>
</div>

### emitXCOFFExceptDirective() {#a91f7f40ccdbea928f3aee0fdf1ba8b56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCXCOFFStreamer::emitXCOFFExceptDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Trap, unsigned Lang, unsigned Reason, unsigned FunctionSize, bool hasDebug)</td>
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

<p>Emit an <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> .except directive which adds information about a trap instruction to the object file exception section.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The function containing the trap.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Lang</td>
<td class="doxyParamItemDescription"><p>- The language code for the exception entry.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Reason</td>
<td class="doxyParamItemDescription"><p>- The reason code for the exception entry.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/xcoffobjectwriter/#ab2da6910125f24f04c3fd78fdbd455d8">llvm::XCOFFObjectWriter::addExceptionEntry</a>, <a href="#a414bcbdab3e76ffd4609ebf292f71bbc">getWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba178e499decd0c21272bc34e4b3056eab">Trap</a>.</p>

</div>
</div>

### emitXCOFFLocalCommonSymbol() {#a44931c282d0b62ee7de97bfb46eaf847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCXCOFFStreamer::emitXCOFFLocalCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LabelSym, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * CsectSym, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>Emits an lcomm directive with <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> csect information.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LabelSym</td>
<td class="doxyParamItemDescription"><p>- Label on the block of storage.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the block of storage.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CsectSym</td>
<td class="doxyParamItemDescription"><p>- Csect name for the block of storage.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the symbol in bytes.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a>.</p>


<p>References <a href="#a3aac14b3e4ad12e94a2d1a3ec2263b93">emitCommonSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitXCOFFRefDirective() {#a74f3eb9157be6847f5bf0f9cd228ad01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCXCOFFStreamer::emitXCOFFRefDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> .ref directive which creates R_REF type entry in the relocation table for one or more symbols.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Sym</td>
<td class="doxyParamItemDescription"><p>- The symbol on the .ref directive.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ab01b807c062ac4610366c6772ad5fd16">llvm::MCAssembler::getBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad60ec34cc0289efdb2530fc622949f83">llvm::MCAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3558114ca72d34962abb28004d864b19">llvm::MCObjectStreamer::getOrCreateDataFragment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### emitXCOFFRenameDirective() {#acf384fd884f5ad2bec1307548dddb21f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCXCOFFStreamer::emitXCOFFRenameDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Rename)</td>
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

<p>Emit a <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> .rename directive which creates a synonym for an illegal or undesirable name.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>- The name used internally in the assembly for references to the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Rename</td>
<td class="doxyParamItemDescription"><p>- The value to which the Name parameter is changed at the end of assembly.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### emitXCOFFSymbolLinkageWithVisibility() {#af980fe7c2238f4ce0ac3b6a5df32bea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCXCOFFStreamer::emitXCOFFSymbolLinkageWithVisibility (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Linkage, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Visibility)</td>
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

<p>Emit a symbol's linkage and visibility with a linkage directive for <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Linkage</td>
<td class="doxyParamItemDescription"><p>- The linkage of the symbol to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Visibility</td>
<td class="doxyParamItemDescription"><p>- The visibility of the symbol to emit or MCSA_Invalid if the symbol does not have an explicit visibility.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a>.</p>


<p>References <a href="#afc1c68d65e64e951a0f7d2a67dc80719">emitSymbolAttribute</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243af3367f8319e21bf0779da14146221c55">llvm::MCSA_Invalid</a>.</p>

</div>
</div>

### emitZerofill() {#a4c4b7ae739c86b3799bba662ca1f3314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCXCOFFStreamer::emitZerofill (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol=nullptr, uint64_t Size=0, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1), <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Emit the zerofill section and an optional symbol.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Section</td>
<td class="doxyParamItemDescription"><p>- The zerofill section to create and or to put the symbol</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The zerofill symbol to emit, if non-NULL.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the zerofill symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteAlignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the zerofill symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getWriter() {#a414bcbdab3e76ffd4609ebf292f71bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFFObjectWriter &amp; MCXCOFFStreamer::getWriter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a> and <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a56c45e3acce6f7b060bed7e40398d207">llvm::MCAssembler::getWriter</a>.</p>


<p>Referenced by <a href="#af46be67680c12c7fbf655011203ddcce">emitXCOFFCInfoSym</a> and <a href="#a91f7f40ccdbea928f3aee0fdf1ba8b56">emitXCOFFExceptDirective</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcxcoffstreamer-h">MCXCOFFStreamer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcxcoffstreamer-cpp">MCXCOFFStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
