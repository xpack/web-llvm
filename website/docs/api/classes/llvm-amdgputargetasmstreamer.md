---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgputargetasmstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUTargetAsmStreamer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUTargetAsmStreamer { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf2229c2822291643ee59b19d376378">AMDGPUTargetAsmStreamer</a> (MCStreamer &amp;S, formatted_raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6335c5fc14b12bc6987411a8e2b03c">finish</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76473f6421e409f2c8a009157b998356">EmitDirectiveAMDGCNTarget</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a598d21c442d2b39e891a4e912e2e788c">EmitDirectiveAMDHSACodeObjectVersion</a> (unsigned COV) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba45e45780737e70f7cf05b6e853b802">EmitAMDKernelCodeT</a> (AMDGPU::AMDGPUMCKernelCodeT &amp;Header) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fab6ddb07cae40213e25673fdf33656">EmitAMDGPUSymbolType</a> (StringRef SymbolName, unsigned Type) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcc6f7320bff272e150ff3e6c2d34a68">emitAMDGPULDS</a> (MCSymbol *Sym, unsigned Size, Align Alignment) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d07229c023f96191e3124c856e44370">EmitMCResourceInfo</a> (const MCSymbol *NumVGPR, const MCSymbol *NumAGPR, const MCSymbol *NumExplicitSGPR, const MCSymbol *PrivateSegmentSize, const MCSymbol *UsesVCC, const MCSymbol *UsesFlatScratch, const MCSymbol *HasDynamicallySizedStack, const MCSymbol *HasRecursion, const MCSymbol *HasIndirectCall) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a467a389919bfa1e97f91d87afaa79b9f">EmitMCResourceMaximums</a> (const MCSymbol *MaxVGPR, const MCSymbol *MaxAGPR, const MCSymbol *MaxSGPR) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596cb0f59e053d10323a6c06bb98d013">EmitISAVersion</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ea71f46259463a2379530358a02d372">EmitHSAMetadata</a> (msgpack::Document &amp;HSAMetadata, bool Strict) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bc92696c48ae0ad81766fc7da03bc6">EmitCodeEnd</a> (const MCSubtargetInfo &amp;STI) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf468fdf1fecb6e06d29a8cbfaa808bb">EmitAmdhsaKernelDescriptor</a> (const MCSubtargetInfo &amp;STI, StringRef KernelName, const AMDGPU::MCKernelDescriptor &amp;KernelDescriptor, const MCExpr *NextVGPR, const MCExpr *NextSGPR, const MCExpr *ReserveVCC, const MCExpr *ReserveFlatScr) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac17941c9a37c36e3cfbff63cf0e9cdfa">OS</a></td>
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


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUTargetAsmStreamer() {#a3cf2229c2822291643ee59b19d376378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUTargetAsmStreamer::AMDGPUTargetAsmStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#a0f62f1873ee379d1c619db1b42780234">llvm::AMDGPUTargetStreamer::AMDGPUTargetStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitAMDGPULDS() {#afcc6f7320bff272e150ff3e6c2d34a68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetAsmStreamer::emitAMDGPULDS (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, unsigned Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### EmitAMDGPUSymbolType() {#a3fab6ddb07cae40213e25673fdf33656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetAsmStreamer::EmitAMDGPUSymbolType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymbolName, unsigned Type)</td>
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



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a78554ab6218f194944dae873f7bb1563">llvm::ELF::STT_AMDGPU_HSA_KERNEL</a>.</p>

</div>
</div>

### EmitAmdhsaKernelDescriptor() {#abf468fdf1fecb6e06d29a8cbfaa808bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetAsmStreamer::EmitAmdhsaKernelDescriptor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> KernelName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor">AMDGPU::MCKernelDescriptor</a> &amp; KernelDescriptor, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * NextVGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * NextSGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * ReserveVCC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * ReserveFlatScr)</td>
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



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a30475b065bebd7bc81d1112d9067d772a3cc9c6ed140931f8f27254a01f1c9863">llvm::AMDGPU::AMDHSA_COV4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a30475b065bebd7bc81d1112d9067d772abd2438b14a6a1a27fae653284aaa3cb4">llvm::AMDGPU::AMDHSA_COV5</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a74dc10b4ec4a74b8a4379ea8f6edb221">llvm::AMDGPU::MCKernelDescriptor::bits_get</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#ad81298cdd7d265274f8df7fc6f8e6f26">llvm::AMDGPUTargetStreamer::CodeObjectVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a9e09a6c60a55c8337112ecf8ad9887d1">llvm::AMDGPU::MCKernelDescriptor::compute_pgm_rsrc1</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a039cf91571ec7505f5959ab246acf402">llvm::AMDGPU::MCKernelDescriptor::compute_pgm_rsrc2</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a439263c0c004e30c236fe4d3e7115fe0">llvm::AMDGPU::MCKernelDescriptor::compute_pgm_rsrc3</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a994d277dcd8d2765f20ddb1e81a1187e">llvm::MCBinaryExpr::createMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aafd3b7d8deff060578db9e6e6529ef0a">llvm::AMDGPU::foldAMDGPUMCExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#ab41c2681decc5965bf6fc06b6adf5665">llvm::AMDGPUTargetStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#abc72867c22a31b29cea037ca2de5b024">llvm::AMDGPUTargetStreamer::getTargetID</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#aa66ead6996ffdddf6d2ce285fd6594fd">llvm::AMDGPU::MCKernelDescriptor::group_segment_fixed_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa22d12557395f76722ef205293aa4a3c">llvm::AMDGPU::hasArchitectedFlatScratch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#adbe8b2394969d3cf98b70d46ce725354">llvm::AMDGPU::hasKernargPreload</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6927ea03a5a90995645230645e0fbd89">llvm::AMDGPU::isGFX90A</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a2774f0df9dcc67631d99e0f7547dbe34">llvm::AMDGPU::MCKernelDescriptor::kernarg_preload</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a04b2d9a2534e0d845405eec075c6a367">llvm::AMDGPU::MCKernelDescriptor::kernarg_size</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#ae4e949a5ed9ab404afdb5f36f30a24e5">llvm::AMDGPU::MCKernelDescriptor::kernel_code_properties</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/isaversion/#aef8b56009a9935038a8cd0c4e0495554">llvm::AMDGPU::IsaVersion::Major</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2d69f7dd3e8c055a8aa9f8a6c401dc51">llvm::AMDGPU::printAMDGPUMCExpr</a> and <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a453769e82f1d12738583bfe1582ca3bd">llvm::AMDGPU::MCKernelDescriptor::private_segment_fixed_size</a>.</p>

</div>
</div>

### EmitAMDKernelCodeT() {#aba45e45780737e70f7cf05b6e853b802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetAsmStreamer::EmitAMDKernelCodeT (<a href="/web-llvm/docs/api/structs/llvm/amdgpu/amdgpumckernelcodet">AMDGPU::AMDGPUMCKernelCodeT</a> &amp; Header)</td>
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



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aafd3b7d8deff060578db9e6e6529ef0a">llvm::AMDGPU::foldAMDGPUMCExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#ab41c2681decc5965bf6fc06b6adf5665">llvm::AMDGPUTargetStreamer::getContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2d69f7dd3e8c055a8aa9f8a6c401dc51">llvm::AMDGPU::printAMDGPUMCExpr</a>.</p>

</div>
</div>

### EmitCodeEnd() {#ae8bc92696c48ae0ad81766fc7da03bc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUTargetAsmStreamer::EmitCodeEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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


<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp/#af6ab0b42b53810d4456cb51537349222">CacheLineSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">llvm::AMDGPU::isGFX11Plus</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6927ea03a5a90995645230645e0fbd89">llvm::AMDGPU::isGFX90A</a>.</p>

</div>
</div>

### EmitDirectiveAMDGCNTarget() {#a76473f6421e409f2c8a009157b998356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetAsmStreamer::EmitDirectiveAMDGCNTarget ()</td>
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



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#abc72867c22a31b29cea037ca2de5b024">llvm::AMDGPUTargetStreamer::getTargetID</a>.</p>

</div>
</div>

### EmitDirectiveAMDHSACodeObjectVersion() {#a598d21c442d2b39e891a4e912e2e788c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetAsmStreamer::EmitDirectiveAMDHSACodeObjectVersion (unsigned COV)</td>
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



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#a102af1039d79e782f502c0c6914003bf">llvm::AMDGPUTargetStreamer::EmitDirectiveAMDHSACodeObjectVersion</a>.</p>

</div>
</div>

### EmitHSAMetadata() {#a3ea71f46259463a2379530358a02d372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUTargetAsmStreamer::EmitHSAMetadata (<a href="/web-llvm/docs/api/classes/llvm/msgpack/document">msgpack::Document</a> &amp; HSAMetadata, bool Strict)</td>
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


<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/v3/#a461f2193b620e67d5ef8800016925ca9">llvm::AMDGPU::HSAMD::V3::AssemblerDirectiveBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/v3/#ac74834b1f2978d4d945be02d47571fd2">llvm::AMDGPU::HSAMD::V3::AssemblerDirectiveEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a5deadb4fe33da953cf16a27551f02c3c">llvm::msgpack::Document::getRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a82205f2c71cb88331e554cb4fc8b8822">llvm::msgpack::Document::toYAML</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae91b89e3dbb8e36d143a6efcc4d5d85a">Verifier</a>.</p>

</div>
</div>

### EmitISAVersion() {#a596cb0f59e053d10323a6c06bb98d013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUTargetAsmStreamer::EmitISAVersion ()</td>
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


<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#abc72867c22a31b29cea037ca2de5b024">llvm::AMDGPUTargetStreamer::getTargetID</a>.</p>

</div>
</div>

### EmitMCResourceInfo() {#a2d07229c023f96191e3124c856e44370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetAsmStreamer::EmitMCResourceInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * NumVGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * NumAGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * NumExplicitSGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * PrivateSegmentSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * UsesVCC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * UsesFlatScratch, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * HasDynamicallySizedStack, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * HasRecursion, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * HasIndirectCall)</td>
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



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp/#a332f58169ae0ab282d2d7bb75781493a">PRINT_RES_INFO</a>.</p>

</div>
</div>

### EmitMCResourceMaximums() {#a467a389919bfa1e97f91d87afaa79b9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetAsmStreamer::EmitMCResourceMaximums (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * MaxVGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * MaxAGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * MaxSGPR)</td>
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



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp/#a332f58169ae0ab282d2d7bb75781493a">PRINT_RES_INFO</a>.</p>

</div>
</div>

### finish() {#acb6335c5fc14b12bc6987411a8e2b03c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUTargetAsmStreamer::finish ()</td>
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



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#a05e9d5521cbfc7418446c9319b4f38fe">llvm::AMDGPUTargetStreamer::getPALMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#af3cc411bac033c6b3b5a4e7d6764cb94">llvm::AMDGPUPALMetadata::reset</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#af405cf94e28aca3f12c108ff0b858aee">llvm::AMDGPUPALMetadata::toString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OS {#ac17941c9a37c36e3cfbff63cf0e9cdfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">formatted_raw_ostream&amp; llvm::AMDGPUTargetAsmStreamer::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
