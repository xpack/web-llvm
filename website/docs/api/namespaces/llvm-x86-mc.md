---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/x86-mc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `X86_MC` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::X86_MC { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis">X86MCInstrAnalysis</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; std::pair&lt; uint64_t, uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa32860b6f507582db22346076bf5caa0">findX86PltEntries</a> (uint64_t PltSectionVA, ArrayRef&lt; uint8_t &gt; PltContents)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; std::pair&lt; uint64_t, uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dc8dda7e6f1c6adc7eaaf755f6c27a5">findX86_64PltEntries</a> (uint64_t PltSectionVA, ArrayRef&lt; uint8_t &gt; PltContents)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac799d914344a144a68709ea5dc541439">ParseX86Triple</a> (const Triple &amp;TT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af79bf5c9f731c8f0d5f1995637adba47">getDwarfRegFlavour</a> (const Triple &amp;TT, bool isEH)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85bf92f849a9d2d11f112747b93cb2ae">initLLVMToSEHAndCVRegMapping</a> (MCRegisterInfo *MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c25db35754b1e2c9df08e429b0b9a7d">hasLockPrefix</a> (const MCInst &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction has a LOCK prefix. <a href="#a5c25db35754b1e2c9df08e429b0b9a7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4cc9236e2a4f99e7e616a7f6740f16">is16BitMemOperand</a> (const MCInst &amp;MI, unsigned Op, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a4743c3cd4e0961c692360c298d97f5">is32BitMemOperand</a> (const MCInst &amp;MI, unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0debe625b7e83a944ae3614d7d51cae">is64BitMemOperand</a> (const MCInst &amp;MI, unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70e27203f31ce8fcdd19e77996a12f8">needsAddressSizeOverride</a> (const MCInst &amp;MI, const MCSubtargetInfo &amp;STI, int MemoryOperand, uint64_t TSFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction needs an Address-Size override prefix. <a href="#aa70e27203f31ce8fcdd19e77996a12f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5725b4767b5ffa093fcf5c21fc2bb27">createX86MCSubtargetInfo</a> (const Triple &amp;TT, StringRef CPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> instance. <a href="#ae5725b4767b5ffa093fcf5c21fc2bb27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad133d82ed8cf2866b22b7304524935c8">emitInstruction</a> (MCObjectStreamer &amp;, const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6e1cdbd935a8cc82d9f9f3e1cead86b">emitPrefix</a> (MCCodeEmitter &amp;MCE, const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, const MCSubtargetInfo &amp;STI)</td>
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


<div class="doxySectionDef">

## Functions

### createX86MCSubtargetInfo() {#ae5725b4767b5ffa093fcf5c21fc2bb27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSubtargetInfo * llvm::X86_MC::createX86MCSubtargetInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> instance.</p>


<p>This is exposed so Asm parser, etc. do not need to go through <a href="/web-llvm/docs/api/structs/llvm/targetregistry">TargetRegistry</a>.</p>


<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp">X86MCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a> and <a href="#ac799d914344a144a68709ea5dc541439">ParseX86Triple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a>.</p>

</div>
</div>

### emitInstruction() {#ad133d82ed8cf2866b22b7304524935c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86_MC::emitInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a>, definition at line 1553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a51cfff6dff330a39d19c88e0ccd8abf1">anonymous{X86AsmBackend.cpp}::X86AsmBackend::X86AsmBackend</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86elfstreamer/#aa54643a174b5b98ed33486797ca585fe">anonymous{X86AsmBackend.cpp}::X86ELFStreamer::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86wincoffstreamer-cpp-/x86wincoffstreamer/#a4ba48a1965d81afbc5b476fcb257206d">anonymous{X86WinCOFFStreamer.cpp}::X86WinCOFFStreamer::emitInstruction</a>.</p>

</div>
</div>

### emitPrefix() {#ac6e1cdbd935a8cc82d9f9f3e1cead86b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86_MC::emitPrefix (<a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &amp; MCE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a>, definition at line 1546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter/#a380773ba72f8745ffdea347917d48a95">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::emitPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter/#a66a91a4b7ba7dadf46425e8bbb463e5f">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::X86MCCodeEmitter</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#aec5e1563ca339dbf7905cf069c364e39">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaPrefix</a>.</p>

</div>
</div>

### findX86\_64PltEntries() {#a9dc8dda7e6f1c6adc7eaaf755f6c27a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::pair&lt; uint64_t, uint64_t &gt; &gt; llvm::X86_MC::findX86_64PltEntries (uint64_t PltSectionVA, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; PltContents)</td>
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



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp">X86MCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#ae48345ba0c30a521aab65eeb28949d8f">llvm::X86_MC::X86MCInstrAnalysis::findPltEntries</a>.</p>

</div>
</div>

### findX86PltEntries() {#aa32860b6f507582db22346076bf5caa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::pair&lt; uint64_t, uint64_t &gt; &gt; llvm::X86_MC::findX86PltEntries (uint64_t PltSectionVA, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; PltContents)</td>
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



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp">X86MCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#ae48345ba0c30a521aab65eeb28949d8f">llvm::X86_MC::X86MCInstrAnalysis::findPltEntries</a>.</p>

</div>
</div>

### getDwarfRegFlavour() {#af79bf5c9f731c8f0d5f1995637adba47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86_MC::getDwarfRegFlavour (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, bool isEH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp">X86MCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarfflavour/#a5da6b6259f229bb911bc528f48959fe3a529ca38d33e9ba250143e21df7effe94">llvm::DWARFFlavour::X86_32_DarwinEH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfflavour/#a5da6b6259f229bb911bc528f48959fe3a62d2f8cbc59370b03dc64f223493d3f3">llvm::DWARFFlavour::X86_32_Generic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfflavour/#a5da6b6259f229bb911bc528f48959fe3a47a98b5535026debf4229e5cdbfbaaf1">llvm::DWARFFlavour::X86_64</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#a4ca5ad26bd6f05539ea46021582c30ba">createX86MCRegisterInfo</a>.</p>

</div>
</div>

### hasLockPrefix() {#a5c25db35754b1e2c9df08e429b0b9a7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86_MC::hasLockPrefix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this instruction has a LOCK prefix.</p>

<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp">X86MCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a21f6d8d4fc6a58587a2b022eb048a3bc">llvm::X86::IP_HAS_LOCK</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### initLLVMToSEHAndCVRegMapping() {#a85bf92f849a9d2d11f112747b93cb2ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86_MC::initLLVMToSEHAndCVRegMapping (<a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> * MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp">X86MCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#a4ca5ad26bd6f05539ea46021582c30ba">createX86MCRegisterInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#aac7b6f011839cfcf4d25443e735b57a5">llvm::X86RegisterInfo::X86RegisterInfo</a>.</p>

</div>
</div>

### is16BitMemOperand() {#a4c4cc9236e2a4f99e7e616a7f6740f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86_MC::is16BitMemOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6"&gt;Op&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>operand # of the memory operand.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the specified instruction has a 16-bit memory operand.</p></dd>
</dl>


<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp">X86MCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84a319f0e99a1ac9396659683d2638d4f45">llvm::X86::AddrBaseReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84aba7ebe0e28a2c1c4c14343f549c01462">llvm::X86::AddrIndexReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#afef1d5400d8233fa3d9ee7d4b2b5c971">isMemOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aa70e27203f31ce8fcdd19e77996a12f8">needsAddressSizeOverride</a>.</p>

</div>
</div>

### is32BitMemOperand() {#a3a4743c3cd4e0961c692360c298d97f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86_MC::is32BitMemOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6"&gt;Op&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>operand # of the memory operand.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the specified instruction has a 32-bit memory operand.</p></dd>
</dl>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp">X86MCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84a319f0e99a1ac9396659683d2638d4f45">llvm::X86::AddrBaseReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84aba7ebe0e28a2c1c4c14343f549c01462">llvm::X86::AddrIndexReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#afef1d5400d8233fa3d9ee7d4b2b5c971">isMemOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aa70e27203f31ce8fcdd19e77996a12f8">needsAddressSizeOverride</a>.</p>

</div>
</div>

### is64BitMemOperand() {#af0debe625b7e83a944ae3614d7d51cae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86_MC::is64BitMemOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6"&gt;Op&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>operand # of the memory operand.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the specified instruction has a 64-bit memory operand.</p></dd>
</dl>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp">X86MCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#afef1d5400d8233fa3d9ee7d4b2b5c971">isMemOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aa70e27203f31ce8fcdd19e77996a12f8">needsAddressSizeOverride</a>.</p>

</div>
</div>

### needsAddressSizeOverride() {#aa70e27203f31ce8fcdd19e77996a12f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86_MC::needsAddressSizeOverride (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, int MemoryOperand, uint64_t TSFlags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this instruction needs an Address-Size override prefix.</p>

<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp">X86MCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eab2eec66c1c52ab7579af0cb9130b8ab5">llvm::X86II::AdSize16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eae324586afb9a70d93aa2aba95abcd2d0">llvm::X86II::AdSize32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea50c2f31aba037c4ec3acceb23258ef8f">llvm::X86II::AdSizeMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea3ae6529df02b311ddca2a678a0bfaf64">llvm::X86II::FormMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="#a4c4cc9236e2a4f99e7e616a7f6740f16">is16BitMemOperand</a>, <a href="#a3a4743c3cd4e0961c692360c298d97f5">is32BitMemOperand</a>, <a href="#af0debe625b7e83a944ae3614d7d51cae">is64BitMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea336cd3807e9712aee813c92ab1cbd3c7">llvm::X86II::RawFrmDst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea0ebbf8b9bdbf40355e1786a06fe3ebdb">llvm::X86II::RawFrmDstSrc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eab93edaca89956bd35deb0830c0a83c32">llvm::X86II::RawFrmSrc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a9e01cbc62f1eb3379712051ded643013">llvm::X86InstPrinterCommon::printInstFlags</a>.</p>

</div>
</div>

### ParseX86Triple() {#ac799d914344a144a68709ea5dc541439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::X86_MC::ParseX86Triple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp">X86MCTargetDesc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ace5d58a24effb264483f4af8b79b97b2">llvm::Triple::CODE16</a>.</p>


<p>Referenced by <a href="#ae5725b4767b5ffa093fcf5c21fc2bb27">createX86MCSubtargetInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp">X86MCTargetDesc.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">X86MCTargetDesc.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
