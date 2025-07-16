---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgputargetelfstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUTargetELFStreamer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUTargetELFStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">Target/AMDGPU/MCTargetDesc/AMDGPUTargetStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer">AMDGPUTargetStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8083cb06953f12061040ab24764e6fe4">AMDGPUTargetELFStreamer</a> (MCStreamer &amp;S, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer">MCELFStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae9693ccfa69d763d761028455f14e2a">getStreamer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a595765b8c36eef76cb8f2a6dfd10c277">finish</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021032465d3f9c2fb884f49b354946cb">EmitDirectiveAMDGCNTarget</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52a02f271d804bdc34f866c95a09e252">EmitAMDKernelCodeT</a> (AMDGPU::AMDGPUMCKernelCodeT &amp;Header) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac96454d753afccfed1b283ddf7b3474c">EmitAMDGPUSymbolType</a> (StringRef SymbolName, unsigned Type) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ca9bd4a32a51a2f03d00ad2f09b572">emitAMDGPULDS</a> (MCSymbol *Sym, unsigned Size, Align Alignment) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb080cf7b9699890fae560c167c09291">EmitISAVersion</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f962a3da2e5e21ea73c8a2ba3d60cf1">EmitHSAMetadata</a> (msgpack::Document &amp;HSAMetadata, bool Strict) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d5bfc5811bed855825f405f757caf44">EmitCodeEnd</a> (const MCSubtargetInfo &amp;STI) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac2390b5c807bff61a3eaa2ce2430543">EmitAmdhsaKernelDescriptor</a> (const MCSubtargetInfo &amp;STI, StringRef KernelName, const AMDGPU::MCKernelDescriptor &amp;KernelDescriptor, const MCExpr *NextVGPR, const MCExpr *NextSGPR, const MCExpr *ReserveVCC, const MCExpr *ReserveFlatScr) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4ca5b36a652a896afb575124d187ab8">EmitNote</a> (StringRef Name, const MCExpr *DescSize, unsigned NoteType, function_ref&lt; void(MCELFStreamer &amp;)&gt; EmitDesc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb5942237c47737305836ca137aff3e">getEFlags</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02f34e1d45e9c6cdf2f6c334ed546374">getEFlagsR600</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bec075c0bb7c7dd4126a7a4361ffb83">getEFlagsAMDGCN</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67fe6c1451f8e5c9c603957cc1c5db7b">getEFlagsUnknownOS</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a617f6f0f025551c5ff0a5c5f29956d89">getEFlagsAMDHSA</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c372cee09987ed8a5b32361e1791e3">getEFlagsAMDPAL</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1da31f2a95e912539171dbb35648baf">getEFlagsMesa3D</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa92d28d04e7f5c314e3ce4b0144caf22">getEFlagsV3</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4c1919c9a851bac30c513f35a6b5b17">getEFlagsV4</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa982b3c7b40f92e2d8b356086476d09e">getEFlagsV6</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafba3f277032f2075dfe43878cc1bbfe">STI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9f3cc5d615b4e21d6d7bf0b5b0478b">Streamer</a></td>
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


<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUTargetELFStreamer() {#a8083cb06953f12061040ab24764e6fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUTargetELFStreamer::AMDGPUTargetELFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#a0f62f1873ee379d1c619db1b42780234">llvm::AMDGPUTargetStreamer::AMDGPUTargetStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitAMDGPULDS() {#a99ca9bd4a32a51a2f03d00ad2f09b572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetELFStreamer::emitAMDGPULDS (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, unsigned Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acd4a05b32a482232267400c369932868">llvm::MCSymbol::declareCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#ab41c2681decc5965bf6fc06b6adf5665">llvm::AMDGPUTargetStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a666e25e11bd035c93786545bec5ce44e">llvm::MCSymbolELF::isBindingSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ac1edee41b5f81ab31451e8bf98a3a3e6">llvm::MCSymbolELF::setBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aa03af2ef8f5bbbd64f174f0a8feb3c32">llvm::MCSymbol::setIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a63edf630bae30668b44c9be9a85cb9a8">llvm::MCSymbolELF::setSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#aed759e9547e045f0bd987987de0f76bc">llvm::MCSymbolELF::setType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ade1e281f7783e3cacd627341a116501ea2b1f8fd9974acef592ec96f7757f1442">llvm::ELF::SHN_AMDGPU_LDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a3056225276d5d76c1b142d3505704851">llvm::ELF::STB_GLOBAL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a9803bad2cfdce7601000ee3f6b979d9b">llvm::ELF::STT_OBJECT</a>.</p>

</div>
</div>

### EmitAMDGPUSymbolType() {#ac96454d753afccfed1b283ddf7b3474c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetELFStreamer::EmitAMDGPUSymbolType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymbolName, unsigned Type)</td>
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



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#ab41c2681decc5965bf6fc06b6adf5665">llvm::AMDGPUTargetStreamer::getContext</a> and <a href="#aae9693ccfa69d763d761028455f14e2a">getStreamer</a>.</p>

</div>
</div>

### EmitAmdhsaKernelDescriptor() {#aac2390b5c807bff61a3eaa2ce2430543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetELFStreamer::EmitAmdhsaKernelDescriptor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> KernelName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor">AMDGPU::MCKernelDescriptor</a> &amp; KernelDescriptor, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * NextVGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * NextSGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * ReserveVCC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * ReserveFlatScr)</td>
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



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 955 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a9e09a6c60a55c8337112ecf8ad9887d1">llvm::AMDGPU::MCKernelDescriptor::compute_pgm_rsrc1</a>, <a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t/#a45ff565a0f5dc2633706650c4e8562bc">llvm::amdhsa::kernel_descriptor_t::compute_pgm_rsrc1</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a039cf91571ec7505f5959ab246acf402">llvm::AMDGPU::MCKernelDescriptor::compute_pgm_rsrc2</a>, <a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t/#aa430b22aeafbae06973a9f97d990d16a">llvm::amdhsa::kernel_descriptor_t::compute_pgm_rsrc2</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a439263c0c004e30c236fe4d3e7115fe0">llvm::AMDGPU::MCKernelDescriptor::compute_pgm_rsrc3</a>, <a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t/#ad767468e753de6709622353722e6fee4">llvm::amdhsa::kernel_descriptor_t::compute_pgm_rsrc3</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ae357568bfa7baaa244f16208924f4637">llvm::MCSymbolELF::getBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a2badd3f8011db90045f7be286331125f">llvm::MCSymbolELF::getOther</a>, <a href="#aae9693ccfa69d763d761028455f14e2a">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#add2f34e14532817ad86d5c8f3b179c2a">llvm::MCSymbolELF::getVisibility</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#aa66ead6996ffdddf6d2ce285fd6594fd">llvm::AMDGPU::MCKernelDescriptor::group_segment_fixed_size</a>, <a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t/#a00c93ea2cbbc98a3b069b286c75ff916">llvm::amdhsa::kernel_descriptor_t::group_segment_fixed_size</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a2774f0df9dcc67631d99e0f7547dbe34">llvm::AMDGPU::MCKernelDescriptor::kernarg_preload</a>, <a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t/#a915bc6b3ff2ba22b1d8e659b1c875385">llvm::amdhsa::kernel_descriptor_t::kernarg_preload</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a04b2d9a2534e0d845405eec075c6a367">llvm::AMDGPU::MCKernelDescriptor::kernarg_size</a>, <a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t/#a8ac8bf05852d06753e544aa552ed3d39">llvm::amdhsa::kernel_descriptor_t::kernarg_size</a>, <a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t/#afed83eb16431ab8f2a72ef6a112807a0">llvm::amdhsa::kernel_descriptor_t::kernel_code_entry_byte_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#ae4e949a5ed9ab404afdb5f36f30a24e5">llvm::AMDGPU::MCKernelDescriptor::kernel_code_properties</a>, <a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t/#aa91c506e6598736498d581465891a9c6">llvm::amdhsa::kernel_descriptor_t::kernel_code_properties</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a453769e82f1d12738583bfe1582ca3bd">llvm::AMDGPU::MCKernelDescriptor::private_segment_fixed_size</a>, <a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t/#a7dbf8460eec03ca1cfd3565ec87a44ba">llvm::amdhsa::kernel_descriptor_t::private_segment_fixed_size</a>, <a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t/#a91d55df721c06d782aa14e691860a67d">llvm::amdhsa::kernel_descriptor_t::reserved0</a>, <a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t/#a3cd7f19bc7b958944b3a7e5250fc4b6b">llvm::amdhsa::kernel_descriptor_t::reserved1</a>, <a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t/#a05c40ee874fad3493080a01a78b5b41a">llvm::amdhsa::kernel_descriptor_t::reserved3</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ac1edee41b5f81ab31451e8bf98a3a3e6">llvm::MCSymbolELF::setBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#aed9abfbf50800b7378713d657bf0cf5a">llvm::MCSymbolELF::setOther</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a63edf630bae30668b44c9be9a85cb9a8">llvm::MCSymbolELF::setSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#aed759e9547e045f0bd987987de0f76bc">llvm::MCSymbolELF::setType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a42d355b38e3f57001fdbce9f13846a04">llvm::MCSymbolELF::setVisibility</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a9803bad2cfdce7601000ee3f6b979d9b">llvm::ELF::STT_OBJECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5af3e7284f94dabe52ad31412ab70c15f4">llvm::ELF::STV_DEFAULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5aec3ecfdbfbbe90889a70c56df29b263a">llvm::ELF::STV_PROTECTED</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa26b41b8badd0d0826298773147fef4c">llvm::MCSymbolRefExpr::VK_AMDGPU_REL64</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>

</div>
</div>

### EmitAMDKernelCodeT() {#a52a02f271d804bdc34f866c95a09e252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetELFStreamer::EmitAMDKernelCodeT (<a href="/web-llvm/docs/api/structs/llvm/amdgpu/amdgpumckernelcodet">AMDGPU::AMDGPUMCKernelCodeT</a> &amp; Header)</td>
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



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#ab41c2681decc5965bf6fc06b6adf5665">llvm::AMDGPUTargetStreamer::getContext</a>, <a href="#aae9693ccfa69d763d761028455f14e2a">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a216005880453270b48e5d5d7daeec6d4">llvm::MCStreamer::popSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ab095568f88bb32f8a744aaeab0d2c4d0">llvm::MCStreamer::pushSection</a>.</p>

</div>
</div>

### EmitCodeEnd() {#a3d5bfc5811bed855825f405f757caf44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUTargetELFStreamer::EmitCodeEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on success, false on failure.</p></dd>
</dl>


<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp/#af6ab0b42b53810d4456cb51537349222">CacheLineSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9488c32df3cb8819f6a07f8c88d72c66">llvm::MCStreamer::emitValueToAlignment</a>, <a href="#aae9693ccfa69d763d761028455f14e2a">getStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">llvm::AMDGPU::isGFX11Plus</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6927ea03a5a90995645230645e0fbd89">llvm::AMDGPU::isGFX90A</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a216005880453270b48e5d5d7daeec6d4">llvm::MCStreamer::popSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ab095568f88bb32f8a744aaeab0d2c4d0">llvm::MCStreamer::pushSection</a>.</p>

</div>
</div>

### EmitDirectiveAMDGCNTarget() {#a021032465d3f9c2fb884f49b354946cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetELFStreamer::EmitDirectiveAMDGCNTarget ()</td>
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



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>

</div>
</div>

### EmitHSAMetadata() {#a5f962a3da2e5e21ea73c8a2ba3d60cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUTargetELFStreamer::EmitHSAMetadata (<a href="/web-llvm/docs/api/classes/llvm/msgpack/document">msgpack::Document</a> &amp; HSAMetadata, bool Strict)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on success, false on failure.</p></dd>
</dl>


<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 902 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a66d51c3585e4733b99bb8d3e3eb2bb81">llvm::MCObjectStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#ac725449b95138e5297b8af02df828882">llvm::MCELFStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#ab41c2681decc5965bf6fc06b6adf5665">llvm::AMDGPUTargetStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a5deadb4fe33da953cf16a27551f02c3c">llvm::msgpack::Document::getRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/elfnote/#aefb41dbb5c30115f2597db8083cfcb0a">llvm::AMDGPU::ElfNote::NoteNameV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ae01999f6bb8613fd9cad067b9e8e83b4acd3865a0ae5a4a85ae17d89a549267d3">llvm::ELF::NT_AMDGPU_METADATA</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae91b89e3dbb8e36d143a6efcc4d5d85a">Verifier</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a8f94c9dc628a8565363014088523a0fa">llvm::msgpack::Document::writeToBlob</a>.</p>

</div>
</div>

### EmitISAVersion() {#afb080cf7b9699890fae560c167c09291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUTargetELFStreamer::EmitISAVersion ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on success, false on failure.</p></dd>
</dl>


<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 883 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a66d51c3585e4733b99bb8d3e3eb2bb81">llvm::MCObjectStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#ac725449b95138e5297b8af02df828882">llvm::MCELFStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#ab41c2681decc5965bf6fc06b6adf5665">llvm::AMDGPUTargetStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#abc72867c22a31b29cea037ca2de5b024">llvm::AMDGPUTargetStreamer::getTargetID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/elfnote/#a9c117e2bdb138b1a81a4d318f0eae388">llvm::AMDGPU::ElfNote::NoteNameV2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5298f27e75d05e13c7a4f2da4b0d9be3a24a15604bd169280ce7ee0821b8647ff">llvm::ELF::NT_AMD_HSA_ISA_NAME</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>

</div>
</div>

### finish() {#a595765b8c36eef76cb8f2a6dfd10c277}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetELFStreamer::finish ()</td>
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



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#ad81298cdd7d265274f8df7fc6f8e6f26">llvm::AMDGPUTargetStreamer::CodeObjectVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a66d51c3585e4733b99bb8d3e3eb2bb81">llvm::MCObjectStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#ab41c2681decc5965bf6fc06b6adf5665">llvm::AMDGPUTargetStreamer::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aefc4a12d8d9d170f14b8586d4a4da549">llvm::AMDGPU::getELFABIVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#a05e9d5521cbfc7418446c9319b4f38fe">llvm::AMDGPUTargetStreamer::getPALMetadata</a>, <a href="#aae9693ccfa69d763d761028455f14e2a">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a803f31e2dc0f9d21ac3d3c19ca8ce927">llvm::AMDGPUPALMetadata::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a194297d42c7fc8aa48a8be43a3ec9fca">llvm::AMDGPUPALMetadata::getVendor</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#af3cc411bac033c6b3b5a4e7d6764cb94">llvm::AMDGPUPALMetadata::reset</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#adfc533e5af74bf82cb31e1f9699e063b">llvm::AMDGPUPALMetadata::toBlob</a>.</p>

</div>
</div>

### getStreamer() {#aae9693ccfa69d763d761028455f14e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCELFStreamer &amp; AMDGPUTargetELFStreamer::getStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="#ac96454d753afccfed1b283ddf7b3474c">EmitAMDGPUSymbolType</a>, <a href="#aac2390b5c807bff61a3eaa2ce2430543">EmitAmdhsaKernelDescriptor</a>, <a href="#a52a02f271d804bdc34f866c95a09e252">EmitAMDKernelCodeT</a>, <a href="#a3d5bfc5811bed855825f405f757caf44">EmitCodeEnd</a> and <a href="#a595765b8c36eef76cb8f2a6dfd10c277">finish</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### EmitNote() {#af4ca5b36a652a896afb575124d187ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetELFStreamer::EmitNote (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * DescSize, unsigned NoteType, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer">MCELFStreamer</a> &amp;)&gt; EmitDesc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>

</div>
</div>

### getEFlags() {#accb5942237c47737305836ca137aff3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUTargetELFStreamer::getEFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>

</div>
</div>

### getEFlagsAMDGCN() {#a7bec075c0bb7c7dd4126a7a4361ffb83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUTargetELFStreamer::getEFlagsAMDGCN ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>

</div>
</div>

### getEFlagsAMDHSA() {#a617f6f0f025551c5ff0a5c5f29956d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUTargetELFStreamer::getEFlagsAMDHSA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>

</div>
</div>

### getEFlagsAMDPAL() {#af1c372cee09987ed8a5b32361e1791e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUTargetELFStreamer::getEFlagsAMDPAL ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 741 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>

</div>
</div>

### getEFlagsMesa3D() {#ac1da31f2a95e912539171dbb35648baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUTargetELFStreamer::getEFlagsMesa3D ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>

</div>
</div>

### getEFlagsR600() {#a02f34e1d45e9c6cdf2f6c334ed546374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUTargetELFStreamer::getEFlagsR600 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>

</div>
</div>

### getEFlagsUnknownOS() {#a67fe6c1451f8e5c9c603957cc1c5db7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUTargetELFStreamer::getEFlagsUnknownOS ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>

</div>
</div>

### getEFlagsV3() {#aa92d28d04e7f5c314e3ce4b0144caf22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUTargetELFStreamer::getEFlagsV3 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>

</div>
</div>

### getEFlagsV4() {#ab4c1919c9a851bac30c513f35a6b5b17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUTargetELFStreamer::getEFlagsV4 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>

</div>
</div>

### getEFlagsV6() {#aa982b3c7b40f92e2d8b356086476d09e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUTargetELFStreamer::getEFlagsV6 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### STI {#aafba3f277032f2075dfe43878cc1bbfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo&amp; llvm::AMDGPUTargetELFStreamer::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>

</div>
</div>

### Streamer {#a4e9f3cc5d615b4e21d6d7bf0b5b0478b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer&amp; llvm::AMDGPUTargetELFStreamer::Streamer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
