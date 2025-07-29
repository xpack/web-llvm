---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armasmbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARMAsmBackend` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ARMAsmBackend { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">Target/ARM/MCTargetDesc/ARMAsmBackend.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic interface to target specific assembler backends. <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armasmbackenddarwin">ARMAsmBackendDarwin</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armasmbackendelf">ARMAsmBackendELF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armasmbackendwincoff">ARMAsmBackendWinCOFF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60d4755db8b2fc2adc714cbab2f5cece">ARMAsmBackend</a> (const Target &amp;T, bool isThumb, llvm::endianness Endian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72d8166dc6c279c7007f5812e2c3f836">getNumFixupKinds</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of target specific fixup kinds. <a href="#a72d8166dc6c279c7007f5812e2c3f836">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa989296bab9644b587d977a65b455d91">hasNOP</a> (const MCSubtargetInfo *STI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1812ca217d69c0224dfc3f6eebac120">getFixupKind</a> (StringRef Name) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a relocation name used in .reloc to a fixup kind. <a href="#ad1812ca217d69c0224dfc3f6eebac120">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo">MCFixupKindInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60294eddf1ce864e51e4f520d53b019b">getFixupKindInfo</a> (MCFixupKind Kind) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get information on a fixup kind. <a href="#a60294eddf1ce864e51e4f520d53b019b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d646b59f77217c6a669115f4a30283">shouldForceRelocation</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, const uint64_t Value, const MCSubtargetInfo *STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hook to check if a relocation is needed for some target specific reason. <a href="#a69d646b59f77217c6a669115f4a30283">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd2d48bd67d42ac499c2b0acdef4c2c3">adjustFixupValue</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, uint64_t Value, bool IsResolved, MCContext &amp;Ctx, const MCSubtargetInfo *STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a454671b28fb42060da505e5692fccc77">applyFixup</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, MutableArrayRef&lt; char &gt; Data, uint64_t Value, bool IsResolved, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate. <a href="#a454671b28fb42060da505e5692fccc77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ee4cfb1ef279fef4911d050f67ec1e">getRelaxedOpcode</a> (unsigned Op, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adea9d854579eb622c1be4e9add02180a">mayNeedRelaxation</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given instruction may need relaxation. <a href="#adea9d854579eb622c1be4e9add02180a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dbae0b9fd70753e65a348ef9eaf1aaf">reasonForFixupRelaxation</a> (const MCFixup &amp;Fixup, uint64_t Value) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc579d4500f6930f47bf75146de3ceb">fixupNeedsRelaxation</a> (const MCFixup &amp;Fixup, uint64_t Value) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple predicate for targets where !Resolved implies requiring relaxation. <a href="#a2cc579d4500f6930f47bf75146de3ceb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad50e8c99a8ff188846367ea1a9ae2143">relaxInstruction</a> (MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Relax the instruction in the given fragment to the next wider instruction. <a href="#ad50e8c99a8ff188846367ea1a9ae2143">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfcc9bf39d2207d4e4e96c88903728fc">writeNopData</a> (raw_ostream &amp;OS, uint64_t Count, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write an (optimal) nop sequence of Count bytes to the given output. <a href="#acfcc9bf39d2207d4e4e96c88903728fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0ba8dbc1bf75aafecea98035f72fe63">handleAssemblerFlag</a> (MCAssemblerFlag Flag) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle any target-specific assembler flags. By default, do nothing. <a href="#af0ba8dbc1bf75aafecea98035f72fe63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b5435bd7904778ea7d27dbc8c04894">getPointerSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a273ed0afd8646fd6073bfa147eb1dea1">isThumb</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c65a6990b01a135ed0e99b523d17f86">setIsThumb</a> (bool it)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaed3aeee67e5b6c8ce3bfc3cc63d5682">isThumbMode</a></td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMAsmBackend() {#a60d4755db8b2fc2adc714cbab2f5cece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARMAsmBackend::ARMAsmBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, bool isThumb, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endian)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a071344506034666f000a89f98ec79768">llvm::MCAsmBackend::Endian</a>, <a href="#a273ed0afd8646fd6073bfa147eb1dea1">isThumb</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a3dd30d6980185ef34e42333191453867">llvm::MCAsmBackend::MCAsmBackend</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmbackenddarwin/#a8a9aeec3d6dbf964fefb7758055cf0d6">llvm::ARMAsmBackendDarwin::ARMAsmBackendDarwin</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackendelf/#a3bf079a0c47b26e4157645cf5ce064b7">llvm::ARMAsmBackendELF::ARMAsmBackendELF</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmbackendwincoff/#af6e215912c602c80d9daf179c367d7cb">llvm::ARMAsmBackendWinCOFF::ARMAsmBackendWinCOFF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### adjustFixupValue() {#acd2d48bd67d42ac499c2b0acdef4c2c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMAsmBackend::adjustFixupValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, uint64_t Value, bool IsResolved, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>, definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a071344506034666f000a89f98ec79768">llvm::MCAsmBackend::Endian</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a0d7591bd8aae60a8151c5015a61f000b">llvm::ARM::fixup_arm_adr_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a92999538a175673cea0e806d24285585">llvm::ARM::fixup_arm_blx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0ac101b88c74df376a53087a2a12829576">llvm::ARM::fixup_arm_condbl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0afbaadabc6e1f4ff4ddacc0b8ddf61872">llvm::ARM::fixup_arm_condbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a48f07670606b6468cdcec6b936f0de95">llvm::ARM::fixup_arm_ldst_abs_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0ac8226e9dee163f040579c8cd8e5eb8c5">llvm::ARM::fixup_arm_ldst_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0ad8333a61d51a1a24c7282773e6099667">llvm::ARM::fixup_arm_mod_imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a551a7051fef9738a64327579574a84f1">llvm::ARM::fixup_arm_movt_hi16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a2b8a01780fc474ad24becf86799f112b">llvm::ARM::fixup_arm_movw_lo16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a1eea621a676048b22be7958e8be8a714">llvm::ARM::fixup_arm_pcrel_10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a8c5b03f8ae59e84ef4b8301c9cf246b3">llvm::ARM::fixup_arm_pcrel_10_unscaled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a4e8f8786070cb526f59e12e7141d0b3d">llvm::ARM::fixup_arm_pcrel_9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a9ad27f8b55ac56d16b5e0c378bad0051">llvm::ARM::fixup_arm_thumb_bcc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0adb86ef3fcfce8098efef7cb48f3ae98d">llvm::ARM::fixup_arm_thumb_bl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a78f923cec6a90c05ba09b4cf99112b93">llvm::ARM::fixup_arm_thumb_blx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a02e738702c5e86913f9f7df2f83480b3">llvm::ARM::fixup_arm_thumb_br</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a293bb495311c0764277085879d15c057">llvm::ARM::fixup_arm_thumb_cb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a7b3659cc67fef8cc53f589860b2f1299">llvm::ARM::fixup_arm_thumb_cp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a395a669e3966360328fdb04b8e4d32d5">llvm::ARM::fixup_arm_thumb_lower_0_7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0accb1029955f0d3a550b1b96e1d6b5f78">llvm::ARM::fixup_arm_thumb_lower_8_15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a9ccf8ef9481f1525a17726e9637798a4">llvm::ARM::fixup_arm_thumb_upper_0_7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a0d3f21c752fedc664c8a23df76f9a107">llvm::ARM::fixup_arm_thumb_upper_8_15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a8b3ea0884f12a07077ecb6fd18395467">llvm::ARM::fixup_arm_uncondbl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a1f91bda8769d2b0c0a7e9d6e813334b8">llvm::ARM::fixup_arm_uncondbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a6555681f7809e4db3c0869b70d55995e">llvm::ARM::fixup_bf_branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a07e85c2a333077f3cc595abcb7a27291">llvm::ARM::fixup_bf_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a74594465a337cf8b251cee95aa0f512b">llvm::ARM::fixup_bfc_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0aa605fdc6a8c29df27b40b4d327c98b6f">llvm::ARM::fixup_bfcsel_else_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a813cea44cae2b85cd8224f154ec4ff05">llvm::ARM::fixup_bfl_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a3bf7591ae1a1baca62aa917ffd3f4d16">llvm::ARM::fixup_le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0aac71630154c96f2f6b3e2e324a40037c">llvm::ARM::fixup_t2_adr_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0abd8de06471430072373886fe44229083">llvm::ARM::fixup_t2_condbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a336d5f4419eb0ef8073bbac49a84de19">llvm::ARM::fixup_t2_ldst_pcrel_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a3175e012a680bfa04176f1073d837f78">llvm::ARM::fixup_t2_movt_hi16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0af29359bd1f79d7f6aec8e2c9275f44d1">llvm::ARM::fixup_t2_movw_lo16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a6d87443e7775d51eaf0708da110f352a">llvm::ARM::fixup_t2_pcrel_10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a602810052128acb5e2f15572370533bf">llvm::ARM::fixup_t2_pcrel_9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0aeebc6c5e4e32b0c507045b954dd187b5">llvm::ARM::fixup_t2_so_imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a81dbbcf6c6a3e2c7c87af5dc5b9301d3">llvm::ARM::fixup_t2_uncondbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a09a9168eafc337c15e7de013524a1532">llvm::ARM::fixup_thumb_adr_pcrel_10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0adbee28ccbbf59371a33a9b6741c890a3">llvm::ARM::fixup_wls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a128346d352fde2e704c07867f4d82eef">llvm::FK_SecRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a8b2acba82b6d0830ab47d67eb8f1ccf0">llvm::FK_SecRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a0f3447f06da0010c13eeb865004f71ca">llvm::ARM_AM::getSOImmVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a3d6b5f20dd274d971ef924f3e2a29d1a">llvm::ARM_AM::getT2SOImmVal</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a1ef6ef4ff039e873e9f66e21e3e55e26">llvm::MCSubtargetInfo::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a6300d761fd69580d711fad99b934950a">llvm::Triple::isOSBinFormatCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#aea6d215256ae43bc9149bf41f2cc7694">llvm::Triple::isOSBinFormatELF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp/#a9dc7acf8b3c43429ae38afb5d9d562ae">joinHalfWords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08b6d5c69d7933ac65aae84e1b50fa62">llvm::maxIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9a9168454d9535e1d4ef88fb4a3592d">llvm::minIntN</a>, <a href="#a2dbae0b9fd70753e65a348ef9eaf1aaf">reasonForFixupRelaxation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp/#a20dcf78408d6fb68621f440f31c5ccf2">swapHalfWords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a066e2a31a13d6520e52ae1944f194662">llvm::Value</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a03bfc9e15ea1f28db8231b2259bac14d">llvm::MCSymbolRefExpr::VK_TLSCALL</a>.</p>


<p>Referenced by <a href="#a454671b28fb42060da505e5692fccc77">applyFixup</a>.</p>

</div>
</div>

### applyFixup() {#a454671b28fb42060da505e5692fccc77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMAsmBackend::applyFixup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; char &gt; Data, uint64_t Value, bool IsResolved, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Apply the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate.</p>


<p>Errors (such as an out of range fixup value) should be reported via <span class="doxyComputerOutput">Ctx</span>. The <span class="doxyComputerOutput">STI</span> is present only for fragments of type <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdatafragment">MCDataFragment</a> with hasInstructions() == true.</p>


<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>, definition at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="#acd2d48bd67d42ac499c2b0acdef4c2c3">adjustFixupValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a071344506034666f000a89f98ec79768">llvm::MCAsmBackend::Endian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp/#a679283d1a6dfa1b34e7ae84492d9daa0">getFixupKindContainerSizeBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp/#ac372fb24df18ed69d99fb8658ec0e7a7">getFixupKindNumBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### fixupNeedsRelaxation() {#a2cc579d4500f6930f47bf75146de3ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMAsmBackend::fixupNeedsRelaxation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t Value)</td>
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

<p>Simple predicate for targets where !Resolved implies requiring relaxation.</p>

<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>, definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="#a2dbae0b9fd70753e65a348ef9eaf1aaf">reasonForFixupRelaxation</a>.</p>

</div>
</div>

### getFixupKind() {#ad1812ca217d69c0224dfc3f6eebac120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MCFixupKind &gt; ARMAsmBackend::getFixupKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Map a relocation name used in .reloc to a fixup kind.</p>

<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>

</div>
</div>

### getFixupKindInfo() {#a60294eddf1ce864e51e4f520d53b019b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCFixupKindInfo &amp; ARMAsmBackend::getFixupKindInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind)</td>
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

<p>Get information on a fixup kind.</p>

<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a071344506034666f000a89f98ec79768">llvm::MCAsmBackend::Endian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a02772a67f2052ae04bb9ef1ff9dc3cf8">llvm::FirstTargetFixupKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a845a63cbed041d42d8c3452991d629c4">llvm::FK_NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da4736f387c937299570b8ac87f9d9dd08">llvm::MCFixupKindInfo::FKF_IsAlignedDownTo32Bits</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">llvm::MCFixupKindInfo::FKF_IsPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad4777f004ef52f665e6ec6defc1cb32a">llvm::MCAsmBackend::getFixupKindInfo</a>, <a href="#a72d8166dc6c279c7007f5812e2c3f836">getNumFixupKinds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a83aa9d86657b1bae143f5512d9a1b131">llvm::ARM::NumTargetFixupKinds</a>.</p>

</div>
</div>

### getNumFixupKinds() {#a72d8166dc6c279c7007f5812e2c3f836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMAsmBackend::getNumFixupKinds ()</td>
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

<p>Get the number of target specific fixup kinds.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a83aa9d86657b1bae143f5512d9a1b131">llvm::ARM::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#a60294eddf1ce864e51e4f520d53b019b">getFixupKindInfo</a>.</p>

</div>
</div>

### getPointerSize() {#a37b5435bd7904778ea7d27dbc8c04894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMAsmBackend::getPointerSize ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>.</p>

</div>
</div>

### getRelaxedOpcode() {#ab9ee4cfb1ef279fef4911d050f67ec1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMAsmBackend::getRelaxedOpcode (unsigned Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>.</p>


<p>Referenced by <a href="#adea9d854579eb622c1be4e9add02180a">mayNeedRelaxation</a> and <a href="#ad50e8c99a8ff188846367ea1a9ae2143">relaxInstruction</a>.</p>

</div>
</div>

### handleAssemblerFlag() {#af0ba8dbc1bf75aafecea98035f72fe63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMAsmBackend::handleAssemblerFlag (<a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1">MCAssemblerFlag</a> Flag)</td>
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

<p>Handle any target-specific assembler flags. By default, do nothing.</p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1a97f114ed47db100e48185ee6d6ad531b">llvm::MCAF_Code16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1ad77d445deab9f2715c6d2b48aee116ea">llvm::MCAF_Code32</a> and <a href="#a8c65a6990b01a135ed0e99b523d17f86">setIsThumb</a>.</p>

</div>
</div>

### hasNOP() {#aa989296bab9644b587d977a65b455d91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMAsmBackend::hasNOP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>.</p>


<p>Referenced by <a href="#acfcc9bf39d2207d4e4e96c88903728fc">writeNopData</a>.</p>

</div>
</div>

### isThumb() {#a273ed0afd8646fd6073bfa147eb1dea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMAsmBackend::isThumb ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>.</p>


<p>Referenced by <a href="#a60d4755db8b2fc2adc714cbab2f5cece">ARMAsmBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackenddarwin/#a8a9aeec3d6dbf964fefb7758055cf0d6">llvm::ARMAsmBackendDarwin::ARMAsmBackendDarwin</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackendelf/#a3bf079a0c47b26e4157645cf5ce064b7">llvm::ARMAsmBackendELF::ARMAsmBackendELF</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackendwincoff/#af6e215912c602c80d9daf179c367d7cb">llvm::ARMAsmBackendWinCOFF::ARMAsmBackendWinCOFF</a> and <a href="#acfcc9bf39d2207d4e4e96c88903728fc">writeNopData</a>.</p>

</div>
</div>

### mayNeedRelaxation() {#adea9d854579eb622c1be4e9add02180a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMAsmBackend::mayNeedRelaxation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given instruction may need relaxation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inst</td>
<td class="doxyParamItemDescription"><p>- The instruction to test.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">STI</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> in effect when the instruction was encoded.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a> and <a href="#ab9ee4cfb1ef279fef4911d050f67ec1e">getRelaxedOpcode</a>.</p>

</div>
</div>

### reasonForFixupRelaxation() {#a2dbae0b9fd70753e65a348ef9eaf1aaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * ARMAsmBackend::reasonForFixupRelaxation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>, definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp/#aab6bca7f04b7048a44ef3e887328df7a">checkPCRelOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a9ad27f8b55ac56d16b5e0c378bad0051">llvm::ARM::fixup_arm_thumb_bcc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a02e738702c5e86913f9f7df2f83480b3">llvm::ARM::fixup_arm_thumb_br</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a293bb495311c0764277085879d15c057">llvm::ARM::fixup_arm_thumb_cb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a7b3659cc67fef8cc53f589860b2f1299">llvm::ARM::fixup_arm_thumb_cp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a6555681f7809e4db3c0869b70d55995e">llvm::ARM::fixup_bf_branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a07e85c2a333077f3cc595abcb7a27291">llvm::ARM::fixup_bf_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a74594465a337cf8b251cee95aa0f512b">llvm::ARM::fixup_bfc_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0aa605fdc6a8c29df27b40b4d327c98b6f">llvm::ARM::fixup_bfcsel_else_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a813cea44cae2b85cd8224f154ec4ff05">llvm::ARM::fixup_bfl_target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a3bf7591ae1a1baca62aa917ffd3f4d16">llvm::ARM::fixup_le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a09a9168eafc337c15e7de013524a1532">llvm::ARM::fixup_thumb_adr_pcrel_10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0adbee28ccbbf59371a33a9b6741c890a3">llvm::ARM::fixup_wls</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#acd2d48bd67d42ac499c2b0acdef4c2c3">adjustFixupValue</a> and <a href="#a2cc579d4500f6930f47bf75146de3ceb">fixupNeedsRelaxation</a>.</p>

</div>
</div>

### relaxInstruction() {#ad50e8c99a8ff188846367ea1a9ae2143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMAsmBackend::relaxInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Relax the instruction in the given fragment to the next wider instruction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] Inst</td>
<td class="doxyParamItemDescription"><p>The instruction to relax, which is also the relaxed instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">STI</td>
<td class="doxyParamItemDescription"><p>the subtarget information for the associated instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a230d5dad7ea2d94e1671a4aa222a2e15">llvm::MCInst::dump_pretty</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="#ab9ee4cfb1ef279fef4911d050f67ec1e">getRelaxedOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>.</p>

</div>
</div>

### setIsThumb() {#a8c65a6990b01a135ed0e99b523d17f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ARMAsmBackend::setIsThumb (bool it)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>.</p>


<p>Referenced by <a href="#af0ba8dbc1bf75aafecea98035f72fe63">handleAssemblerFlag</a>.</p>

</div>
</div>

### shouldForceRelocation() {#a69d646b59f77217c6a669115f4a30283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMAsmBackend::shouldForceRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Hook to check if a relocation is needed for some target specific reason.</p>

<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>, definition at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a92999538a175673cea0e806d24285585">llvm::ARM::fixup_arm_blx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0ac101b88c74df376a53087a2a12829576">llvm::ARM::fixup_arm_condbl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0adb86ef3fcfce8098efef7cb48f3ae98d">llvm::ARM::fixup_arm_thumb_bl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a78f923cec6a90c05ba09b4cf99112b93">llvm::ARM::fixup_arm_thumb_blx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a02e738702c5e86913f9f7df2f83480b3">llvm::ARM::fixup_arm_thumb_br</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a8b3ea0884f12a07077ecb6fd18395467">llvm::ARM::fixup_arm_uncondbl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a1f91bda8769d2b0c0a7e9d6e813334b8">llvm::ARM::fixup_arm_uncondbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0abd8de06471430072373886fe44229083">llvm::ARM::fixup_t2_condbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a81dbbcf6c6a3e2c7c87af5dc5b9301d3">llvm::ARM::fixup_t2_uncondbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3d3a355228d2f64fa312abbd7abfbf">llvm::FixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a32d2549f322ec04f233dc4304b4bbd16">llvm::MCSymbol::isELF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ada159ab0506b0f377aaa17516506f65a">llvm::MCSymbol::isExternal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a28ceebccd9f41f8a7e2359ac45c59f66">llvm::ELF::STT_FUNC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a7269ceaea4bf3dbd15caa427598cbcb9">llvm::ELF::STT_GNU_IFUNC</a>.</p>

</div>
</div>

### writeNopData() {#acfcc9bf39d2207d4e4e96c88903728fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMAsmBackend::writeNopData (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Count, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Write an (optimal) nop sequence of Count bytes to the given output.</p>


<p>If the target cannot generate such a sequence, it should return an error.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- True on success.</p></dd>
</dl>


<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>, definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a071344506034666f000a89f98ec79768">llvm::MCAsmBackend::Endian</a>, <a href="#aa989296bab9644b587d977a65b455d91">hasNOP</a>, <a href="#a273ed0afd8646fd6073bfa147eb1dea1">isThumb</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### isThumbMode {#aaed3aeee67e5b6c8ce3bfc3cc63d5682}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMAsmBackend::isThumbMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-h">ARMAsmBackend.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
