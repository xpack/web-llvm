---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64elfstreamer-cpp-/aarch64elfstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AArch64ELFStreamer` Class Reference

<p>Extend the generic ELFStreamer class so that it can emit mapping symbols at the appropriate points in the object files. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer { ... }
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ElfMappingSymbol { <a href="#a4744fdc1b9d18487659e12956b6bfc02">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3c1d7ab672f0bd15bc00752eb7f8c4d">AArch64ELFStreamer</a> (MCContext &amp;Context, std::unique_ptr&lt; MCAsmBackend &gt; TAB, std::unique_ptr&lt; MCObjectWriter &gt; OW, std::unique_ptr&lt; MCCodeEmitter &gt; Emitter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9a2a9dc08d70f6677c97d0738a021e2">changeSection</a> (MCSection *Section, uint32_t Subsection=0) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is called by popSection and switchSection, if the current section changes. <a href="#ac9a2a9dc08d70f6677c97d0738a021e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd3096b3198e0f0c671429afe7ceacc6">reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State management. <a href="#afd3096b3198e0f0c671429afe7ceacc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48e5ddc867eaadad1d3c120a9f7225cc">emitInstruction</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is the one used to emit instruction data into the <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> streamer. <a href="#a48e5ddc867eaadad1d3c120a9f7225cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9228d21f3dcd46a1ad064ab8092afe36">emitInst</a> (uint32_t Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a 32-bit value as an instruction. <a href="#a9228d21f3dcd46a1ad064ab8092afe36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34bf3d5a69371e950e45bc7f8e7b753c">emitBytes</a> (StringRef Data) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is one of the functions used to emit data into an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> section, so the <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> streamer overrides it to add the appropriate mapping symbol ($d) if necessary. <a href="#a34bf3d5a69371e950e45bc7f8e7b753c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a109c07630047a793087d9a7cfd4c2505">emitValueImpl</a> (const MCExpr *Value, unsigned Size, SMLoc Loc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is one of the functions used to emit data into an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> section, so the <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> streamer overrides it to add the appropriate mapping symbol ($d) if necessary. <a href="#a109c07630047a793087d9a7cfd4c2505">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78113bbde2824d812568689d2a10899a">emitFill</a> (const MCExpr &amp;NumBytes, uint64_t FillValue, SMLoc Loc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit <span class="doxyComputerOutput">Size</span> bytes worth of the value specified by <span class="doxyComputerOutput">FillValue</span>. <a href="#a78113bbde2824d812568689d2a10899a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec538ee6f0ce032787a81cd91bfdb19">emitDataMappingSymbol</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37d764e907711158219755ca657fe7ed">emitA64MappingSymbol</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a842528ff6b06d6dec9f191ccc12ee280">emitMappingSymbol</a> (StringRef Name)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a940f5562335a3f5dd2536fe9fa54d891">AArch64TargetELFStreamer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *, ElfMappingSymbol &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cd87f052684a3414b8ccf07023b8536">LastMappingSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ElfMappingSymbol</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2ad1e0c71f2b4ca9a95d9e960b4ee73">LastEMS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf4eb39a33a82a9edabf62d4498e61a">ImplicitMapSyms</a></td>
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

<p>Extend the generic ELFStreamer class so that it can emit mapping symbols at the appropriate points in the object files.</p>


<p>These symbols are defined in the <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> ABI: infocenter.arm.com/help/topic/com.arm.doc.ihi0056a/IHI0056A_aaelf64.pdf</p>


<p>In brief: $x or $d should be emitted at the start of each contiguous region of A64 code or data in a section. In practice, this emission does not rely on explicit assembler directives but on inherent properties of the directives doing the emission (e.g. ".byte" is data, "add x0, x0, x0" an instruction).</p>


<p>As a result this system is orthogonal to the DataRegion infrastructure used by <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a>. Beware!</p>


<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ElfMappingSymbol {#a4744fdc1b9d18487659e12956b6bfc02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::ElfMappingSymbol </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EMS_None<a id="a4744fdc1b9d18487659e12956b6bfc02a68244682db3e4a2153ca4410816098a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EMS_A64<a id="a4744fdc1b9d18487659e12956b6bfc02a946c5837c6a4a911ee7cb4f8fbf508dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EMS_Data<a id="a4744fdc1b9d18487659e12956b6bfc02a733183ed1214bfcbb2969b292fe9af60"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AArch64ELFStreamer() {#ab3c1d7ab672f0bd15bc00752eb7f8c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::AArch64ELFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; TAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; Emitter)</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ad270e6f1bba829cef8708bba5faeeb8a">llvm::MCContext::getTargetOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a00e9b008c809aa499263cff181c10248">llvm::MCTargetOptions::ImplicitMapSyms</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#aec09c5b9322b90f034d51bd3c0903563">llvm::MCELFStreamer::MCELFStreamer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### changeSection() {#ac9a2a9dc08d70f6677c97d0738a021e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::changeSection (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, uint32_t)</td>
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

<p>This is called by popSection and switchSection, if the current section changes.</p>

<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a1f4f0489eaa2133da3944177f6646130">llvm::MCELFStreamer::changeSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ad946e0775ff08232ff6dc1bd9a8ed9bb">llvm::MCStreamer::getCurrentSection</a>.</p>

</div>
</div>

### emitBytes() {#a34bf3d5a69371e950e45bc7f8e7b753c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::emitBytes (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data)</td>
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

<p>This is one of the functions used to emit data into an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> section, so the <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> streamer overrides it to add the appropriate mapping symbol ($d) if necessary.</p>

<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a66d51c3585e4733b99bb8d3e3eb2bb81">llvm::MCObjectStreamer::emitBytes</a>.</p>

</div>
</div>

### emitFill() {#a78113bbde2824d812568689d2a10899a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::emitFill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> &amp; NumBytes, uint64_t FillValue, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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

<p>Emit <span class="doxyComputerOutput">Size</span> bytes worth of the value specified by <span class="doxyComputerOutput">FillValue</span>.</p>


<p>This is used to implement assembler directives such as .space or .skip.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumBytes</td>
<td class="doxyParamItemDescription"><p>- The number of bytes to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FillValue</td>
<td class="doxyParamItemDescription"><p>- The value to use when filling bytes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Loc</td>
<td class="doxyParamItemDescription"><p>- The location of the expression for error reporting.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a0fe2220852635deb479d9b7274750f5f">llvm::MCObjectStreamer::emitFill</a>.</p>

</div>
</div>

### emitInst() {#a9228d21f3dcd46a1ad064ab8092afe36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::emitInst (uint32_t Inst)</td>
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

<p>Emit a 32-bit value as an instruction.</p>


<p>This is only used for the .inst directive, EmitInstruction should be used in other cases.</p>


<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a66d51c3585e4733b99bb8d3e3eb2bb81">llvm::MCObjectStreamer::emitBytes</a>.</p>

</div>
</div>

### emitInstruction() {#a48e5ddc867eaadad1d3c120a9f7225cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::emitInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>This function is the one used to emit instruction data into the <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> streamer.</p>


<p>We override it to add the appropriate mapping symbol if necessary.</p>


<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a92d2d1c2ac97f1151ed8f38d854e8b34">llvm::MCObjectStreamer::emitInstruction</a>.</p>

</div>
</div>

### emitValueImpl() {#a109c07630047a793087d9a7cfd4c2505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::emitValueImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value, unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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

<p>This is one of the functions used to emit data into an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> section, so the <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> streamer overrides it to add the appropriate mapping symbol ($d) if necessary.</p>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a473f720043ce71ecfaf3154314bed97c">llvm::MCELFStreamer::emitValueImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### reset() {#afd3096b3198e0f0c671429afe7ceacc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::reset ()</td>
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

<p>State management.</p>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#abb624b05bcfdc4558508e1e4ae6de32b">llvm::MCELFStreamer::reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitA64MappingSymbol() {#a37d764e907711158219755ca657fe7ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::emitA64MappingSymbol ()</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>

</div>
</div>

### emitDataMappingSymbol() {#a1ec538ee6f0ce032787a81cd91bfdb19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::emitDataMappingSymbol ()</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>

</div>
</div>

### emitMappingSymbol() {#a842528ff6b06d6dec9f191ccc12ee280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::emitMappingSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AArch64TargetELFStreamer {#a940f5562335a3f5dd2536fe9fa54d891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::AArch64TargetELFStreamer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ImplicitMapSyms {#a3cf4eb39a33a82a9edabf62d4498e61a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::ImplicitMapSyms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>

</div>
</div>

### LastEMS {#ae2ad1e0c71f2b4ca9a95d9e960b4ee73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElfMappingSymbol anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::LastEMS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>

</div>
</div>

### LastMappingSymbols {#a7cd87f052684a3414b8ccf07023b8536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MCSection *, ElfMappingSymbol&gt; anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::LastMappingSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfstreamer-cpp">AArch64ELFStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
