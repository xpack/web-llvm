---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgputargetstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AMDGPUTargetStreamer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUTargetStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">Target/AMDGPU/MCTargetDesc/AMDGPUTargetStreamer.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer">AMDGPUTargetAsmStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer">AMDGPUTargetELFStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f62f1873ee379d1c619db1b42780234">AMDGPUTargetStreamer</a> (MCStreamer &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata">AMDGPUPALMetadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05e9d5521cbfc7418446c9319b4f38fe">getPALMetadata</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c5158f5734778cd2e73a84e4247621">EmitDirectiveAMDGCNTarget</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a102af1039d79e782f502c0c6914003bf">EmitDirectiveAMDHSACodeObjectVersion</a> (unsigned COV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa10d793bd306b8c45b5bfdf25736369e">EmitAMDKernelCodeT</a> (AMDGPU::AMDGPUMCKernelCodeT &amp;Header)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b4e8dcaaac6b2ff79d9c215e7d3aa68">EmitAMDGPUSymbolType</a> (StringRef SymbolName, unsigned Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28297b84b1c5b8ec01f34e92b7b76cc8">emitAMDGPULDS</a> (MCSymbol *Symbol, unsigned Size, Align Alignment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fb33b8bdd4c6620889cd0dc597654ad">EmitMCResourceInfo</a> (const MCSymbol *NumVGPR, const MCSymbol *NumAGPR, const MCSymbol *NumExplicitSGPR, const MCSymbol *PrivateSegmentSize, const MCSymbol *UsesVCC, const MCSymbol *UsesFlatScratch, const MCSymbol *HasDynamicallySizedStack, const MCSymbol *HasRecursion, const MCSymbol *HasIndirectCall)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61bacd2e028be93fc6fd8840eebca2cc">EmitMCResourceMaximums</a> (const MCSymbol *MaxVGPR, const MCSymbol *MaxAGPR, const MCSymbol *MaxSGPR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2362fc24f5878125ad9638cab00e5039">EmitISAVersion</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3206989ed2eb7d82c26434da35b469e8">EmitHSAMetadataV3</a> (StringRef HSAMetadataString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02fc438fa1d605d806b8bef3c1d6e9a1">EmitHSAMetadata</a> (msgpack::Document &amp;HSAMetadata, bool Strict)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit HSA <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>. <a href="#a02fc438fa1d605d806b8bef3c1d6e9a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa63037c9fb835c3b838174971cc4bbd1">EmitHSAMetadata</a> (const AMDGPU::HSAMD::Metadata &amp;HSAMetadata)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50a56f4af48b0ae7261e165e68bd3af3">EmitCodeEnd</a> (const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0270cd600c77886c61577fbeb2c37ab9">EmitAmdhsaKernelDescriptor</a> (const MCSubtargetInfo &amp;STI, StringRef KernelName, const AMDGPU::MCKernelDescriptor &amp;KernelDescriptor, const MCExpr *NextVGPR, const MCExpr *NextSGPR, const MCExpr *ReserveVCC, const MCExpr *ReserveFlatScr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid">AMDGPU::IsaInfo::AMDGPUTargetID</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc72867c22a31b29cea037ca2de5b024">getTargetID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid">AMDGPU::IsaInfo::AMDGPUTargetID</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a444e1ab5b6c9bed83963335b1b8d30f2">getTargetID</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a256a30b3dc1c110426c6b0000a547761">initializeTargetID</a> (const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a713f9a6b7ea055e52006afe0128eca27">initializeTargetID</a> (const MCSubtargetInfo &amp;STI, StringRef FeatureString)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41c2681decc5965bf6fc06b6adf5665">getContext</a> () const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid">AMDGPU::IsaInfo::AMDGPUTargetID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2692b44ca7e3780b5f59c1be122f21a">TargetID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81298cdd7d265274f8df7fc6f8e6f26">CodeObjectVersion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata">AMDGPUPALMetadata</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf2da0c0af9dce0e249d31f7b18495fd">PALMetadata</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb66305b78f9b3644622b3b6d5985bd3">getArchNameFromElfMach</a> (unsigned ElfMach)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52327bdee992d6b713c1fe69c1f77902">getElfMach</a> (StringRef GPU)</td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUTargetStreamer() {#a0f62f1873ee379d1c619db1b42780234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPUTargetStreamer::AMDGPUTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>References <a href="#ad81298cdd7d265274f8df7fc6f8e6f26">CodeObjectVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#acfff4f9a518231ee043200a694fcbafa">llvm::MCTargetStreamer::MCTargetStreamer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#a3cf2229c2822291643ee59b19d376378">llvm::AMDGPUTargetAsmStreamer::AMDGPUTargetAsmStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a8083cb06953f12061040ab24764e6fe4">llvm::AMDGPUTargetELFStreamer::AMDGPUTargetELFStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitAMDGPULDS() {#a28297b84b1c5b8ec01f34e92b7b76cc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AMDGPUTargetStreamer::emitAMDGPULDS (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, unsigned Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### EmitAMDGPUSymbolType() {#a5b4e8dcaaac6b2ff79d9c215e7d3aa68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AMDGPUTargetStreamer::EmitAMDGPUSymbolType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymbolName, unsigned Type)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a14f377c5693a34d02d4554382492ee1b">llvm::AMDGPUAsmPrinter::emitFunctionEntryLabel</a>.</p>

</div>
</div>

### EmitAmdhsaKernelDescriptor() {#a0270cd600c77886c61577fbeb2c37ab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AMDGPUTargetStreamer::EmitAmdhsaKernelDescriptor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> KernelName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor">AMDGPU::MCKernelDescriptor</a> &amp; KernelDescriptor, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * NextVGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * NextSGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * ReserveVCC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * ReserveFlatScr)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa07427c984394cc2c4b4cf8b7158def4">llvm::AMDGPUAsmPrinter::emitFunctionBodyEnd</a>.</p>

</div>
</div>

### EmitAMDKernelCodeT() {#aa10d793bd306b8c45b5bfdf25736369e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AMDGPUTargetStreamer::EmitAMDKernelCodeT (<a href="/web-llvm/docs/api/structs/llvm/amdgpu/amdgpumckernelcodet">AMDGPU::AMDGPUMCKernelCodeT</a> &amp; Header)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#ae3bd05a52450589489fbb3602ad95530">llvm::AMDGPUAsmPrinter::emitFunctionBodyStart</a>.</p>

</div>
</div>

### EmitCodeEnd() {#a50a56f4af48b0ae7261e165e68bd3af3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AMDGPUTargetStreamer::EmitCodeEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on success, false on failure.</p></dd>
</dl>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa4e7f162a6130db44eb584e71f19ae67">llvm::AMDGPUAsmPrinter::doFinalization</a>.</p>

</div>
</div>

### EmitDirectiveAMDGCNTarget() {#a84c5158f5734778cd2e73a84e4247621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AMDGPUTargetStreamer::EmitDirectiveAMDGCNTarget ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a01d6b546873c9427d25bf80c857cb2c4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::onBeginOfFile</a>.</p>

</div>
</div>

### EmitDirectiveAMDHSACodeObjectVersion() {#a102af1039d79e782f502c0c6914003bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AMDGPUTargetStreamer::EmitDirectiveAMDHSACodeObjectVersion (unsigned COV)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Reference <a href="#ad81298cdd7d265274f8df7fc6f8e6f26">CodeObjectVersion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#a598d21c442d2b39e891a4e912e2e788c">llvm::AMDGPUTargetAsmStreamer::EmitDirectiveAMDHSACodeObjectVersion</a>.</p>

</div>
</div>

### EmitHSAMetadata() {#a02fc438fa1d605d806b8bef3c1d6e9a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AMDGPUTargetStreamer::EmitHSAMetadata (<a href="/web-llvm/docs/api/classes/llvm/msgpack/document">msgpack::Document</a> &amp; HSAMetadata, bool Strict)</td>
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

<p>Emit HSA <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>.</p>


<p>When <span class="doxyComputerOutput">Strict</span> is true, known metadata elements must already be well-typed. When <span class="doxyComputerOutput">Strict</span> is false, known types are inferred and the <span class="doxyComputerOutput">HSAMetadata</span> structure is updated with the correct types.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on success, false on failure.</p></dd>
</dl>


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Referenced by <a href="#a3206989ed2eb7d82c26434da35b469e8">EmitHSAMetadataV3</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a60682ebeccc6d8a4c4fb8458c6ed186e">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitTo</a>.</p>

</div>
</div>

### EmitHSAMetadata() {#aa63037c9fb835c3b838174971cc4bbd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AMDGPUTargetStreamer::EmitHSAMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hsamd/metadata">AMDGPU::HSAMD::Metadata</a> &amp; HSAMetadata)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on success, false on failure.</p></dd>
</dl>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>

</div>
</div>

### EmitHSAMetadataV3() {#a3206989ed2eb7d82c26434da35b469e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUTargetStreamer::EmitHSAMetadataV3 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> HSAMetadataString)</td>
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


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="#a02fc438fa1d605d806b8bef3c1d6e9a1">EmitHSAMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#abec5174f9edec79de20397f6b8e0ccdf">llvm::msgpack::Document::fromYAML</a>.</p>

</div>
</div>

### EmitISAVersion() {#a2362fc24f5878125ad9638cab00e5039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AMDGPUTargetStreamer::EmitISAVersion ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on success, false on failure.</p></dd>
</dl>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa733268904945dbb99aeebbf625e5050">llvm::AMDGPUAsmPrinter::emitEndOfAsmFile</a>.</p>

</div>
</div>

### EmitMCResourceInfo() {#a0fb33b8bdd4c6620889cd0dc597654ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AMDGPUTargetStreamer::EmitMCResourceInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * NumVGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * NumAGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * NumExplicitSGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * PrivateSegmentSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * UsesVCC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * UsesFlatScratch, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * HasDynamicallySizedStack, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * HasRecursion, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * HasIndirectCall)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### EmitMCResourceMaximums() {#a61bacd2e028be93fc6fd8840eebca2cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AMDGPUTargetStreamer::EmitMCResourceMaximums (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * MaxVGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * MaxAGPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * MaxSGPR)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa4e7f162a6130db44eb584e71f19ae67">llvm::AMDGPUAsmPrinter::doFinalization</a>.</p>

</div>
</div>

### getPALMetadata() {#a05e9d5521cbfc7418446c9319b4f38fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUPALMetadata * llvm::AMDGPUTargetStreamer::getPALMetadata ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#acb6335c5fc14b12bc6987411a8e2b03c">llvm::AMDGPUTargetAsmStreamer::finish</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a595765b8c36eef76cb8f2a6dfd10c277">llvm::AMDGPUTargetELFStreamer::finish</a>.</p>

</div>
</div>

### getTargetID() {#abc72867c22a31b29cea037ca2de5b024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt; AMDGPU::IsaInfo::AMDGPUTargetID &gt; &amp; llvm::AMDGPUTargetStreamer::getTargetID ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Reference <a href="#ad2692b44ca7e3780b5f59c1be122f21a">TargetID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#abf468fdf1fecb6e06d29a8cbfaa808bb">llvm::AMDGPUTargetAsmStreamer::EmitAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#a76473f6421e409f2c8a009157b998356">llvm::AMDGPUTargetAsmStreamer::EmitDirectiveAMDGCNTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#a596cb0f59e053d10323a6c06bb98d013">llvm::AMDGPUTargetAsmStreamer::EmitISAVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#afb080cf7b9699890fae560c167c09291">llvm::AMDGPUTargetELFStreamer::EmitISAVersion</a> and <a href="#a713f9a6b7ea055e52006afe0128eca27">initializeTargetID</a>.</p>

</div>
</div>

### getTargetID() {#a444e1ab5b6c9bed83963335b1b8d30f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; AMDGPU::IsaInfo::AMDGPUTargetID &gt; &amp; llvm::AMDGPUTargetStreamer::getTargetID ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Reference <a href="#ad2692b44ca7e3780b5f59c1be122f21a">TargetID</a>.</p>

</div>
</div>

### initializeTargetID() {#a256a30b3dc1c110426c6b0000a547761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPUTargetStreamer::initializeTargetID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad2692b44ca7e3780b5f59c1be122f21a">TargetID</a>.</p>


<p>Referenced by <a href="#a713f9a6b7ea055e52006afe0128eca27">initializeTargetID</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a01d6b546873c9427d25bf80c857cb2c4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::onBeginOfFile</a>.</p>

</div>
</div>

### initializeTargetID() {#a713f9a6b7ea055e52006afe0128eca27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPUTargetStreamer::initializeTargetID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FeatureString)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abc72867c22a31b29cea037ca2de5b024">getTargetID</a> and <a href="#a256a30b3dc1c110426c6b0000a547761">initializeTargetID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getContext() {#ab41c2681decc5965bf6fc06b6adf5665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext &amp; llvm::AMDGPUTargetStreamer::getContext ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac5c639960b526c507f505f9e3ebb915d">llvm::MCTargetStreamer::Streamer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a99ca9bd4a32a51a2f03d00ad2f09b572">llvm::AMDGPUTargetELFStreamer::emitAMDGPULDS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#ac96454d753afccfed1b283ddf7b3474c">llvm::AMDGPUTargetELFStreamer::EmitAMDGPUSymbolType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#abf468fdf1fecb6e06d29a8cbfaa808bb">llvm::AMDGPUTargetAsmStreamer::EmitAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#aba45e45780737e70f7cf05b6e853b802">llvm::AMDGPUTargetAsmStreamer::EmitAMDKernelCodeT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a52a02f271d804bdc34f866c95a09e252">llvm::AMDGPUTargetELFStreamer::EmitAMDKernelCodeT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a5f962a3da2e5e21ea73c8a2ba3d60cf1">llvm::AMDGPUTargetELFStreamer::EmitHSAMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#afb080cf7b9699890fae560c167c09291">llvm::AMDGPUTargetELFStreamer::EmitISAVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a595765b8c36eef76cb8f2a6dfd10c277">llvm::AMDGPUTargetELFStreamer::finish</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CodeObjectVersion {#ad81298cdd7d265274f8df7fc6f8e6f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPUTargetStreamer::CodeObjectVersion</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Referenced by <a href="#a0f62f1873ee379d1c619db1b42780234">AMDGPUTargetStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#abf468fdf1fecb6e06d29a8cbfaa808bb">llvm::AMDGPUTargetAsmStreamer::EmitAmdhsaKernelDescriptor</a>, <a href="#a102af1039d79e782f502c0c6914003bf">EmitDirectiveAMDHSACodeObjectVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a595765b8c36eef76cb8f2a6dfd10c277">llvm::AMDGPUTargetELFStreamer::finish</a>.</p>

</div>
</div>

### TargetID {#ad2692b44ca7e3780b5f59c1be122f21a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;AMDGPU::IsaInfo::AMDGPUTargetID&gt; llvm::AMDGPUTargetStreamer::TargetID</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>


<p>Referenced by <a href="#a444e1ab5b6c9bed83963335b1b8d30f2">getTargetID</a>, <a href="#abc72867c22a31b29cea037ca2de5b024">getTargetID</a> and <a href="#a256a30b3dc1c110426c6b0000a547761">initializeTargetID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### PALMetadata {#aaf2da0c0af9dce0e249d31f7b18495fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUPALMetadata llvm::AMDGPUTargetStreamer::PALMetadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getArchNameFromElfMach() {#abb66305b78f9b3644622b3b6d5985bd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AMDGPUTargetStreamer::getArchNameFromElfMach (unsigned ElfMach)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8939190065fef27d40d514c822e806d4">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1010</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba378f145e63f544d0f028a9c1d9e9ce49">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1011</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8f8ca3628b71dd6cd9958cb2d01efe27">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1012</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbac357c2e4c3daf961e40ea89d95b41a63">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1013</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba983909dd5c00c9e32a1ef0ea6d9cb177">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1030</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba09a10cfadee02b8256325cbf8c8adff6">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1031</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba394ae0b3f8e54bd06af34be7045521a9">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1032</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8405a5ebed0cb66488d990cced689bc6">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1033</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbac31e0be9f56749b03723afb630c51d23">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1034</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba0725cc100cd231026539bb9aee48c540">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1035</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba2d4523e6b2f789cd705f8ff215574f00">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1036</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbacc5cb861ec1d6ba3902ac27fa31a63ec">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX10_1_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8c15e85cb021f03d3b0126b8e362e860">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX10_3_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba800606a80ae0ffe46db37106778d0f50">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1100</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba7b266d1ea7bf1458a61bc729c644e17c">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1101</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba30b0d644d2b7088c6c88fb2a2086dab2">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1102</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaba55f2d49a12bc5657a4f7680767eb43">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1103</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaded9fbf05fa918f82db81c628c9b015b">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1150</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8ff21af07970e30e9cba8f7780ae626b">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1151</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba5dcdf4d876db73d990d30ff295e01725">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1152</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba883f214ed4de6b9742a0ace9bfe169c0">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1153</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaa3df1e7d03df1697788ae8ca820e8b35">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX11_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba9c18428c4bcdb91c75b7e4a402b84848">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1200</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbad6c304f2895248e92d929a087c80b10b">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1201</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbac7bd92b3ca47a19e2b0ec92a7fbd5981">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX12_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba6d534b0c04f070288e37dd4260136a92">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba4e031a829a14e1dd8371f010c9bbc02c">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX601</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba79806781fd9d750214dccd1bb426e046">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX602</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba9db5fa7862e0cea201ff6834df1622af">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX700</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8b478724bb106904518f046cc5660dde">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX701</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbafa47984a6bc2d5a8659947d459af81af">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX702</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba05272f2990a003556967cd38c0d1599b">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX703</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba1dad68a37493250b1e5a45c800a41891">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX704</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba86a9b8008ad010728bc2422d85c3ab6e">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX705</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba86248f92c3ea10bec8db252c9913d94c">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX801</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaa67de827236385c4e6ec5d40784ef3d7">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX802</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaa3e054b4593652b9e1f9490795d58f30">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX803</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbad4f160e9c91249bfd6f1b8e6bba49387">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX805</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba23ade1c248c8641198c2bcf6e9c90f1c">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX810</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaab4055da0d953daf9f1aea8f801e3ae9">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX900</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba232603e5f1f34e2d7f321e1f1a0e6572">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX902</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbad099f3e0015db08dbbc7d2b9afa27c2c">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX904</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbab398f033b98ca17b6bef71270185d474">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX906</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba37600535a7c3981c2bfdb48f5942a654">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX908</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaabc97091e867105a7290fdfb8c40bf43">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX909</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbac27d47e1d03aac7703c9a5983efecce4">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX90A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaa76f55818d9feac9507993574027e377">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX90C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba3c89aef2d992e790e224edb1288ff8cc">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX940</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba3e11d0dc905f4faa60683def18059502">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX941</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba552917fc0e6030c1b0bfb04754cdd642">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX942</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba24059924aaaa16f74b14cb1d4cd983b5">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX950</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba86d082ef753c857ab9eb77a655170ecb">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX9_4_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbab75ba053a828999b7254e1889888d679">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX9_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbab3c8acc2122cdf39b9de093fe6a1face">llvm::ELF::EF_AMDGPU_MACH_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbae464444fb9c52dc2b47a37bf9b6226e6">llvm::ELF::EF_AMDGPU_MACH_R600_BARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbac08afc94b012698b789d25d449ce82dc">llvm::ELF::EF_AMDGPU_MACH_R600_CAICOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba153406f50e93d1909f0ba38d972aaef0">llvm::ELF::EF_AMDGPU_MACH_R600_CAYMAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba9a3b6b2394acfd5b71c9c41599f07ea3">llvm::ELF::EF_AMDGPU_MACH_R600_CEDAR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba37a21ec7937143996846f81cf27b16be">llvm::ELF::EF_AMDGPU_MACH_R600_CYPRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba3f3e7b0149e4a24fc8727aa5c89a885e">llvm::ELF::EF_AMDGPU_MACH_R600_JUNIPER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba3c69e5e794dfd4018253e3a77c5b0905">llvm::ELF::EF_AMDGPU_MACH_R600_R600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba61be028a4665d0c8dc433c399251752c">llvm::ELF::EF_AMDGPU_MACH_R600_R630</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba64e95301926b0b92f71be9efe27cd7bc">llvm::ELF::EF_AMDGPU_MACH_R600_REDWOOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbad32ddedcc97154af0fc8318b740e0c5d">llvm::ELF::EF_AMDGPU_MACH_R600_RS880</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8a2a3ce63891ae14a16debe367919a99">llvm::ELF::EF_AMDGPU_MACH_R600_RV670</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba371d0a6914b5fb640564a0c2c0c0d98a">llvm::ELF::EF_AMDGPU_MACH_R600_RV710</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba3402160b02fa25b2e13f4d479503df2e">llvm::ELF::EF_AMDGPU_MACH_R600_RV730</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba69ade1ba141f2cb2a5bdf819ee35ed4c">llvm::ELF::EF_AMDGPU_MACH_R600_RV770</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbae3d73ccc36fcd75fc628184398dec1e6">llvm::ELF::EF_AMDGPU_MACH_R600_SUMO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba3e2f582bde213edd6a19d27d4b66f450">llvm::ELF::EF_AMDGPU_MACH_R600_TURKS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abdda436b916531b2103dbcc64325c1b9">llvm::AMDGPU::getArchNameAMDGCN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a00f426afe94474a8c7933eaa97f1db71">llvm::AMDGPU::getArchNameR600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aab0292e2fa154684869a644bb029a265">llvm::AMDGPU::GK_BARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0abbfa45b8bf51aae60c6a9a62de87aaf5">llvm::AMDGPU::GK_CAICOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a8409d9e45598a8706ccf50f8389f8462">llvm::AMDGPU::GK_CAYMAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aadb09c6abe6758256dff6c90ea1a76b6">llvm::AMDGPU::GK_CEDAR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a9264803dfb45730fda3f25282b543975">llvm::AMDGPU::GK_CYPRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad91847f0315557cbaa80e134f41b126b">llvm::AMDGPU::GK_GFX1010</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0af52d637bc791e67bcad28549446ef2f5">llvm::AMDGPU::GK_GFX1011</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0abcd4e53544524c77b26e75b3324e6e2d">llvm::AMDGPU::GK_GFX1012</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a1666585da5fa94f8ffc4ef239e35d402">llvm::AMDGPU::GK_GFX1013</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a0af7c4fa5f04c90c04af24b475146443">llvm::AMDGPU::GK_GFX1030</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a4890850c6802640e28da0127a4028628">llvm::AMDGPU::GK_GFX1031</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0af839fd11ff6ef14278ce5ab2909ecacc">llvm::AMDGPU::GK_GFX1032</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a1cf86d1b367f32d4dcce6b1263851727">llvm::AMDGPU::GK_GFX1033</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad86d9c309318d0e898c11b962f2689ae">llvm::AMDGPU::GK_GFX1034</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a72c46554b31a1af487670cb1b482e071">llvm::AMDGPU::GK_GFX1035</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ae40a66d6dde5d1afbf7c88bea752f8d2">llvm::AMDGPU::GK_GFX1036</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa99086974c656449b0a768a397077871">llvm::AMDGPU::GK_GFX10_1_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a34226d524b27afc332b8d49a773e6386">llvm::AMDGPU::GK_GFX10_3_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a95657bf48aa53bd9069caf9a4cf4a85b">llvm::AMDGPU::GK_GFX1100</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a69eee5a82feaeecf8a11c1537d0be7f9">llvm::AMDGPU::GK_GFX1101</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a56bc624c035fcd4f0cb0dcc8fa69ac44">llvm::AMDGPU::GK_GFX1102</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0adb1513c858da01a82dd680c31847fdf8">llvm::AMDGPU::GK_GFX1103</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a8e887e52f2ac42f801debc4beeb39088">llvm::AMDGPU::GK_GFX1150</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa70ba858a11343b6a2f2a07a570f071f">llvm::AMDGPU::GK_GFX1151</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad484cc41ee4e53f7ff2a31d82fb7fd05">llvm::AMDGPU::GK_GFX1152</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ab050d267cac9447dce920a24d0868330">llvm::AMDGPU::GK_GFX1153</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aea7938fa858839b99bc77596636e6a33">llvm::AMDGPU::GK_GFX11_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a85bdff80fea1923cfef4be6d72a0deb9">llvm::AMDGPU::GK_GFX1200</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad97e690142b36bc08a093a9ec302cc51">llvm::AMDGPU::GK_GFX1201</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a7d26ffeeb2d981fbfc571f04e6a0b591">llvm::AMDGPU::GK_GFX12_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a0326fd0efbae2a2a8b510e1371b52af8">llvm::AMDGPU::GK_GFX600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0abf6e028309fda1638f2c6f58e40e1950">llvm::AMDGPU::GK_GFX601</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ab2f45e0a75827ba73a20d2f7c02fbfb3">llvm::AMDGPU::GK_GFX602</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0acae31aa0eeca479d9d8a15a3cea6e270">llvm::AMDGPU::GK_GFX700</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a064008edef22d98be2b2f99d1ef3f45e">llvm::AMDGPU::GK_GFX701</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a79927d05a746db7daea104ef8f82b9d2">llvm::AMDGPU::GK_GFX702</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a79cfee1ec116388104a8efe34a3fa0cf">llvm::AMDGPU::GK_GFX703</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a0ced4577490d2121701962e4eeb42a4c">llvm::AMDGPU::GK_GFX704</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa0cd4acb4a85e3f0001e238005050e39">llvm::AMDGPU::GK_GFX705</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aadad48ed787fee4a2f6c35b0d9f89b98">llvm::AMDGPU::GK_GFX801</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a52cffa5e9d2c393f73ef1a9fda9a66ef">llvm::AMDGPU::GK_GFX802</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a74066492470f26fc14c8f12619616961">llvm::AMDGPU::GK_GFX803</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa98a5a3e7196936c66079e915056a349">llvm::AMDGPU::GK_GFX805</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa4e784933a9c8cdaf518011c016dd68c">llvm::AMDGPU::GK_GFX810</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0af70db43aa73cadb189ef73754d3fa0d3">llvm::AMDGPU::GK_GFX900</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a9cd8e5be875175b2d9624bd8c01e75a4">llvm::AMDGPU::GK_GFX902</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a5a6d7b2ad4d8aedc73ce73e4a9010227">llvm::AMDGPU::GK_GFX904</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad5ec30fbe83c5e6ed4986249a1263af3">llvm::AMDGPU::GK_GFX906</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a216bf2708fee238d859ce9deb0e9bd00">llvm::AMDGPU::GK_GFX908</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a4aa806154467822b5f68095ba367eff6">llvm::AMDGPU::GK_GFX909</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a7b1ba323a145bec14fd8b653f61028fb">llvm::AMDGPU::GK_GFX90A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad2c6cee4e82fc18ecd7ab30b6a3144ee">llvm::AMDGPU::GK_GFX90C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a921f003176303086f1dca128129e4542">llvm::AMDGPU::GK_GFX940</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a30f3a46329bf8f34f48dc3c58295017c">llvm::AMDGPU::GK_GFX941</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a507ea323fefcf8ff05975c408fcf0f4e">llvm::AMDGPU::GK_GFX942</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a98396db85f1b1cfac33200f7c05badab">llvm::AMDGPU::GK_GFX950</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa6d66771c27b3311eaf5ac122b74226d">llvm::AMDGPU::GK_GFX9_4_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a0c97ffa2d725e9b1278edfc8a32b034d">llvm::AMDGPU::GK_GFX9_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a1b5ba5a6942e8ed8f23932f685d000fc">llvm::AMDGPU::GK_JUNIPER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a7fbe7042d90fd9a4269037cc21b063d8">llvm::AMDGPU::GK_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0afe4344b2b814933ed3bf72f82df1a072">llvm::AMDGPU::GK_R600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a19f3381b6c1b6fe785105d9886351697">llvm::AMDGPU::GK_R630</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a8e5926d8ea19757038c4155912b395f1">llvm::AMDGPU::GK_REDWOOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ac8c3f112117bae6376650f69cdfbe927">llvm::AMDGPU::GK_RS880</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a2ef3bc48291b8bd816d12e4c2a6e631e">llvm::AMDGPU::GK_RV670</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a3197738d328a2ec9bbb5de425007050e">llvm::AMDGPU::GK_RV710</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a1df854d45a3d4a6a1865dc00e750c1dd">llvm::AMDGPU::GK_RV730</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0af053ef33f07262cc463fa6a5d787aeb2">llvm::AMDGPU::GK_RV770</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a051b61b70b71eb4eeccc86b84058c812">llvm::AMDGPU::GK_SUMO</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a6b170bcb32c4c5dbe468f7358abaab82">llvm::AMDGPU::GK_TURKS</a>.</p>

</div>
</div>

### getElfMach() {#a52327bdee992d6b713c1fe69c1f77902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUTargetStreamer::getElfMach (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GPU)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-h">AMDGPUTargetStreamer.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgputargetstreamer-cpp">AMDGPUTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8939190065fef27d40d514c822e806d4">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1010</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba378f145e63f544d0f028a9c1d9e9ce49">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1011</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8f8ca3628b71dd6cd9958cb2d01efe27">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1012</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbac357c2e4c3daf961e40ea89d95b41a63">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1013</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba983909dd5c00c9e32a1ef0ea6d9cb177">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1030</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba09a10cfadee02b8256325cbf8c8adff6">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1031</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba394ae0b3f8e54bd06af34be7045521a9">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1032</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8405a5ebed0cb66488d990cced689bc6">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1033</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbac31e0be9f56749b03723afb630c51d23">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1034</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba0725cc100cd231026539bb9aee48c540">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1035</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba2d4523e6b2f789cd705f8ff215574f00">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1036</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbacc5cb861ec1d6ba3902ac27fa31a63ec">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX10_1_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8c15e85cb021f03d3b0126b8e362e860">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX10_3_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba800606a80ae0ffe46db37106778d0f50">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1100</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba7b266d1ea7bf1458a61bc729c644e17c">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1101</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba30b0d644d2b7088c6c88fb2a2086dab2">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1102</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaba55f2d49a12bc5657a4f7680767eb43">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1103</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaded9fbf05fa918f82db81c628c9b015b">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1150</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8ff21af07970e30e9cba8f7780ae626b">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1151</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba5dcdf4d876db73d990d30ff295e01725">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1152</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba883f214ed4de6b9742a0ace9bfe169c0">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1153</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaa3df1e7d03df1697788ae8ca820e8b35">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX11_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba9c18428c4bcdb91c75b7e4a402b84848">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1200</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbad6c304f2895248e92d929a087c80b10b">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX1201</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbac7bd92b3ca47a19e2b0ec92a7fbd5981">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX12_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba6d534b0c04f070288e37dd4260136a92">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba4e031a829a14e1dd8371f010c9bbc02c">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX601</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba79806781fd9d750214dccd1bb426e046">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX602</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba9db5fa7862e0cea201ff6834df1622af">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX700</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8b478724bb106904518f046cc5660dde">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX701</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbafa47984a6bc2d5a8659947d459af81af">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX702</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba05272f2990a003556967cd38c0d1599b">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX703</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba1dad68a37493250b1e5a45c800a41891">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX704</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba86a9b8008ad010728bc2422d85c3ab6e">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX705</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba86248f92c3ea10bec8db252c9913d94c">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX801</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaa67de827236385c4e6ec5d40784ef3d7">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX802</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaa3e054b4593652b9e1f9490795d58f30">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX803</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbad4f160e9c91249bfd6f1b8e6bba49387">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX805</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba23ade1c248c8641198c2bcf6e9c90f1c">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX810</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaab4055da0d953daf9f1aea8f801e3ae9">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX900</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba232603e5f1f34e2d7f321e1f1a0e6572">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX902</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbad099f3e0015db08dbbc7d2b9afa27c2c">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX904</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbab398f033b98ca17b6bef71270185d474">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX906</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba37600535a7c3981c2bfdb48f5942a654">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX908</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaabc97091e867105a7290fdfb8c40bf43">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX909</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbac27d47e1d03aac7703c9a5983efecce4">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX90A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaa76f55818d9feac9507993574027e377">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX90C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba3c89aef2d992e790e224edb1288ff8cc">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX940</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba3e11d0dc905f4faa60683def18059502">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX941</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba552917fc0e6030c1b0bfb04754cdd642">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX942</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba24059924aaaa16f74b14cb1d4cd983b5">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX950</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba86d082ef753c857ab9eb77a655170ecb">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX9_4_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbab75ba053a828999b7254e1889888d679">llvm::ELF::EF_AMDGPU_MACH_AMDGCN_GFX9_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbab3c8acc2122cdf39b9de093fe6a1face">llvm::ELF::EF_AMDGPU_MACH_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbae464444fb9c52dc2b47a37bf9b6226e6">llvm::ELF::EF_AMDGPU_MACH_R600_BARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbac08afc94b012698b789d25d449ce82dc">llvm::ELF::EF_AMDGPU_MACH_R600_CAICOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba153406f50e93d1909f0ba38d972aaef0">llvm::ELF::EF_AMDGPU_MACH_R600_CAYMAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba9a3b6b2394acfd5b71c9c41599f07ea3">llvm::ELF::EF_AMDGPU_MACH_R600_CEDAR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba37a21ec7937143996846f81cf27b16be">llvm::ELF::EF_AMDGPU_MACH_R600_CYPRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba3f3e7b0149e4a24fc8727aa5c89a885e">llvm::ELF::EF_AMDGPU_MACH_R600_JUNIPER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba3c69e5e794dfd4018253e3a77c5b0905">llvm::ELF::EF_AMDGPU_MACH_R600_R600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba61be028a4665d0c8dc433c399251752c">llvm::ELF::EF_AMDGPU_MACH_R600_R630</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba64e95301926b0b92f71be9efe27cd7bc">llvm::ELF::EF_AMDGPU_MACH_R600_REDWOOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbad32ddedcc97154af0fc8318b740e0c5d">llvm::ELF::EF_AMDGPU_MACH_R600_RS880</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba8a2a3ce63891ae14a16debe367919a99">llvm::ELF::EF_AMDGPU_MACH_R600_RV670</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba371d0a6914b5fb640564a0c2c0c0d98a">llvm::ELF::EF_AMDGPU_MACH_R600_RV710</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba3402160b02fa25b2e13f4d479503df2e">llvm::ELF::EF_AMDGPU_MACH_R600_RV730</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba69ade1ba141f2cb2a5bdf819ee35ed4c">llvm::ELF::EF_AMDGPU_MACH_R600_RV770</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbae3d73ccc36fcd75fc628184398dec1e6">llvm::ELF::EF_AMDGPU_MACH_R600_SUMO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba3e2f582bde213edd6a19d27d4b66f450">llvm::ELF::EF_AMDGPU_MACH_R600_TURKS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aab0292e2fa154684869a644bb029a265">llvm::AMDGPU::GK_BARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0abbfa45b8bf51aae60c6a9a62de87aaf5">llvm::AMDGPU::GK_CAICOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a8409d9e45598a8706ccf50f8389f8462">llvm::AMDGPU::GK_CAYMAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aadb09c6abe6758256dff6c90ea1a76b6">llvm::AMDGPU::GK_CEDAR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a9264803dfb45730fda3f25282b543975">llvm::AMDGPU::GK_CYPRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad91847f0315557cbaa80e134f41b126b">llvm::AMDGPU::GK_GFX1010</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0af52d637bc791e67bcad28549446ef2f5">llvm::AMDGPU::GK_GFX1011</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0abcd4e53544524c77b26e75b3324e6e2d">llvm::AMDGPU::GK_GFX1012</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a1666585da5fa94f8ffc4ef239e35d402">llvm::AMDGPU::GK_GFX1013</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a0af7c4fa5f04c90c04af24b475146443">llvm::AMDGPU::GK_GFX1030</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a4890850c6802640e28da0127a4028628">llvm::AMDGPU::GK_GFX1031</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0af839fd11ff6ef14278ce5ab2909ecacc">llvm::AMDGPU::GK_GFX1032</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a1cf86d1b367f32d4dcce6b1263851727">llvm::AMDGPU::GK_GFX1033</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad86d9c309318d0e898c11b962f2689ae">llvm::AMDGPU::GK_GFX1034</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a72c46554b31a1af487670cb1b482e071">llvm::AMDGPU::GK_GFX1035</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ae40a66d6dde5d1afbf7c88bea752f8d2">llvm::AMDGPU::GK_GFX1036</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa99086974c656449b0a768a397077871">llvm::AMDGPU::GK_GFX10_1_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a34226d524b27afc332b8d49a773e6386">llvm::AMDGPU::GK_GFX10_3_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a95657bf48aa53bd9069caf9a4cf4a85b">llvm::AMDGPU::GK_GFX1100</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a69eee5a82feaeecf8a11c1537d0be7f9">llvm::AMDGPU::GK_GFX1101</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a56bc624c035fcd4f0cb0dcc8fa69ac44">llvm::AMDGPU::GK_GFX1102</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0adb1513c858da01a82dd680c31847fdf8">llvm::AMDGPU::GK_GFX1103</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a8e887e52f2ac42f801debc4beeb39088">llvm::AMDGPU::GK_GFX1150</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa70ba858a11343b6a2f2a07a570f071f">llvm::AMDGPU::GK_GFX1151</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad484cc41ee4e53f7ff2a31d82fb7fd05">llvm::AMDGPU::GK_GFX1152</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ab050d267cac9447dce920a24d0868330">llvm::AMDGPU::GK_GFX1153</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aea7938fa858839b99bc77596636e6a33">llvm::AMDGPU::GK_GFX11_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a85bdff80fea1923cfef4be6d72a0deb9">llvm::AMDGPU::GK_GFX1200</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad97e690142b36bc08a093a9ec302cc51">llvm::AMDGPU::GK_GFX1201</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a7d26ffeeb2d981fbfc571f04e6a0b591">llvm::AMDGPU::GK_GFX12_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a0326fd0efbae2a2a8b510e1371b52af8">llvm::AMDGPU::GK_GFX600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0abf6e028309fda1638f2c6f58e40e1950">llvm::AMDGPU::GK_GFX601</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ab2f45e0a75827ba73a20d2f7c02fbfb3">llvm::AMDGPU::GK_GFX602</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0acae31aa0eeca479d9d8a15a3cea6e270">llvm::AMDGPU::GK_GFX700</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a064008edef22d98be2b2f99d1ef3f45e">llvm::AMDGPU::GK_GFX701</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a79927d05a746db7daea104ef8f82b9d2">llvm::AMDGPU::GK_GFX702</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a79cfee1ec116388104a8efe34a3fa0cf">llvm::AMDGPU::GK_GFX703</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a0ced4577490d2121701962e4eeb42a4c">llvm::AMDGPU::GK_GFX704</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa0cd4acb4a85e3f0001e238005050e39">llvm::AMDGPU::GK_GFX705</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aadad48ed787fee4a2f6c35b0d9f89b98">llvm::AMDGPU::GK_GFX801</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a52cffa5e9d2c393f73ef1a9fda9a66ef">llvm::AMDGPU::GK_GFX802</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a74066492470f26fc14c8f12619616961">llvm::AMDGPU::GK_GFX803</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa98a5a3e7196936c66079e915056a349">llvm::AMDGPU::GK_GFX805</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa4e784933a9c8cdaf518011c016dd68c">llvm::AMDGPU::GK_GFX810</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0af70db43aa73cadb189ef73754d3fa0d3">llvm::AMDGPU::GK_GFX900</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a9cd8e5be875175b2d9624bd8c01e75a4">llvm::AMDGPU::GK_GFX902</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a5a6d7b2ad4d8aedc73ce73e4a9010227">llvm::AMDGPU::GK_GFX904</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad5ec30fbe83c5e6ed4986249a1263af3">llvm::AMDGPU::GK_GFX906</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a216bf2708fee238d859ce9deb0e9bd00">llvm::AMDGPU::GK_GFX908</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a4aa806154467822b5f68095ba367eff6">llvm::AMDGPU::GK_GFX909</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a7b1ba323a145bec14fd8b653f61028fb">llvm::AMDGPU::GK_GFX90A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad2c6cee4e82fc18ecd7ab30b6a3144ee">llvm::AMDGPU::GK_GFX90C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a921f003176303086f1dca128129e4542">llvm::AMDGPU::GK_GFX940</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a30f3a46329bf8f34f48dc3c58295017c">llvm::AMDGPU::GK_GFX941</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a507ea323fefcf8ff05975c408fcf0f4e">llvm::AMDGPU::GK_GFX942</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a98396db85f1b1cfac33200f7c05badab">llvm::AMDGPU::GK_GFX950</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa6d66771c27b3311eaf5ac122b74226d">llvm::AMDGPU::GK_GFX9_4_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a0c97ffa2d725e9b1278edfc8a32b034d">llvm::AMDGPU::GK_GFX9_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a1b5ba5a6942e8ed8f23932f685d000fc">llvm::AMDGPU::GK_JUNIPER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a7fbe7042d90fd9a4269037cc21b063d8">llvm::AMDGPU::GK_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0afe4344b2b814933ed3bf72f82df1a072">llvm::AMDGPU::GK_R600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a19f3381b6c1b6fe785105d9886351697">llvm::AMDGPU::GK_R630</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a8e5926d8ea19757038c4155912b395f1">llvm::AMDGPU::GK_REDWOOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ac8c3f112117bae6376650f69cdfbe927">llvm::AMDGPU::GK_RS880</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a2ef3bc48291b8bd816d12e4c2a6e631e">llvm::AMDGPU::GK_RV670</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a3197738d328a2ec9bbb5de425007050e">llvm::AMDGPU::GK_RV710</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a1df854d45a3d4a6a1865dc00e750c1dd">llvm::AMDGPU::GK_RV730</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0af053ef33f07262cc463fa6a5d787aeb2">llvm::AMDGPU::GK_RV770</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a051b61b70b71eb4eeccc86b84058c812">llvm::AMDGPU::GK_SUMO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a6b170bcb32c4c5dbe468f7358abaab82">llvm::AMDGPU::GK_TURKS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a98ac623b540c21285a2307f08fe7d237">llvm::AMDGPU::parseArchAMDGCN</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af396b64f51fe3f71f771dcf36a46dfbc">llvm::AMDGPU::parseArchR600</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
