---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86AsmBackend` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{X86AsmBackend.cpp}::X86AsmBackend { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/darwinx86asmbackend">DarwinX86AsmBackend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/elfx86asmbackend">ELFX86AsmBackend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/windowsx86asmbackend">WindowsX86AsmBackend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51cfff6dff330a39d19c88e0ccd8abf1">X86AsmBackend</a> (const Target &amp;T, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3e9018a72f4ab775773a23480aff17">allowAutoPadding</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this target might automatically pad instructions and thus need to emit padding enable/disable directives around sensative code. <a href="#a8a3e9018a72f4ab775773a23480aff17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491288fbc508a0628c5ac7df28aa818f">allowEnhancedRelaxation</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this target allows an unrelaxable instruction to be emitted into RelaxableFragment and then we can increase its size in a tricky way for optimization. <a href="#a491288fbc508a0628c5ac7df28aa818f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38dcf42330d1efcd03d0686ba7bbaf1d">emitInstructionBegin</a> (MCObjectStreamer &amp;OS, const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert BoundaryAlignFragment before instructions to align branches. <a href="#a38dcf42330d1efcd03d0686ba7bbaf1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c9b4bc17f742123fb67a743e46e11bc">emitInstructionEnd</a> (MCObjectStreamer &amp;OS, const MCInst &amp;Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the last fragment to be aligned for the BoundaryAlignFragment. <a href="#a8c9b4bc17f742123fb67a743e46e11bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1c7028bd6f6b4b2f3ff9a4fc974a7e0">getNumFixupKinds</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of target specific fixup kinds. <a href="#ac1c7028bd6f6b4b2f3ff9a4fc974a7e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628c61cc739e4291331529759a81f2ce">getFixupKind</a> (StringRef Name) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a relocation name used in .reloc to a fixup kind. <a href="#a628c61cc739e4291331529759a81f2ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo">MCFixupKindInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3619a2032935a5fd9864f3e58208b7">getFixupKindInfo</a> (MCFixupKind Kind) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get information on a fixup kind. <a href="#a8d3619a2032935a5fd9864f3e58208b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ab0419e0b93d5d9ae6c68b7857b9b72">shouldForceRelocation</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, const uint64_t Value, const MCSubtargetInfo *STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hook to check if a relocation is needed for some target specific reason. <a href="#a7ab0419e0b93d5d9ae6c68b7857b9b72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4f1ecc11d292a77e74ca1043c72c8d2">applyFixup</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, MutableArrayRef&lt; char &gt; Data, uint64_t Value, bool IsResolved, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the <span class="doxyComputerOutput">Value</span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate. <a href="#ac4f1ecc11d292a77e74ca1043c72c8d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae14243cebfb18dca997cdca22b151245">mayNeedRelaxation</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether the given instruction may need relaxation. <a href="#ae14243cebfb18dca997cdca22b151245">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e29d4c5ce17dd4e45009a0cfb31931f">fixupNeedsRelaxation</a> (const MCFixup &amp;Fixup, uint64_t Value) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple predicate for targets where !Resolved implies requiring relaxation. <a href="#a6e29d4c5ce17dd4e45009a0cfb31931f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85095bdb81f7b2460ce2b158985cdfa9">relaxInstruction</a> (MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Relax the instruction in the given fragment to the next wider instruction. <a href="#a85095bdb81f7b2460ce2b158985cdfa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a112639954fd036a8748791f74d0db6fb">padInstructionViaRelaxation</a> (MCRelaxableFragment &amp;RF, MCCodeEmitter &amp;Emitter, unsigned &amp;RemainingSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec5e1563ca339dbf7905cf069c364e39">padInstructionViaPrefix</a> (MCRelaxableFragment &amp;RF, MCCodeEmitter &amp;Emitter, unsigned &amp;RemainingSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fab033607162e6ab1a1d6fb7ed5e07b">padInstructionEncoding</a> (MCRelaxableFragment &amp;RF, MCCodeEmitter &amp;Emitter, unsigned &amp;RemainingSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b45cdd0366bfaa446ebdb3f00d80496">finishLayout</a> (const MCAssembler &amp;Asm) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Give backend an opportunity to finish layout after relaxation. <a href="#a4b45cdd0366bfaa446ebdb3f00d80496">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4704062228bd37e6102915129ba326b5">getMaximumNopSize</a> (const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum size of a nop in bytes on this target. <a href="#a4704062228bd37e6102915129ba326b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8f8a80943df09baa1ccdb938e453639">writeNopData</a> (raw_ostream &amp;OS, uint64_t Count, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a sequence of optimal nops to the output, covering <span class="doxyComputerOutput">Count</span> bytes. <a href="#ac8f8a80943df09baa1ccdb938e453639">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9424257300fecd5e0b13d90e3532859a">determinePaddingPrefix</a> (const MCInst &amp;Inst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> can reduce the bytes of NOP by padding instructions with prefixes to get a better peformance in some cases. <a href="#a9424257300fecd5e0b13d90e3532859a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd060cf31ba5e5a5532a991aaf93d92">isMacroFused</a> (const MCInst &amp;Cmp, const MCInst &amp;Jcc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the two instructions will be macro-fused on the target cpu. <a href="#a2cd060cf31ba5e5a5532a991aaf93d92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5163f2dbec8129f1ebda594d8d6074bc">needAlign</a> (const MCInst &amp;Inst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the instruction operand needs to be aligned. <a href="#a5163f2dbec8129f1ebda594d8d6074bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c98eb19bd659c5d343384d882315c60">canPadBranches</a> (MCObjectStreamer &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdf1a4f6c701fbc6b903f696792d63b7">canPadInst</a> (const MCInst &amp;Inst, MCObjectStreamer &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can insert NOP or prefixes automatically before the the instruction to be emitted. <a href="#abdf1a4f6c701fbc6b903f696792d63b7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84dce4acf7a4beb42341108363633186">STI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846ef4406f3ecaa75edf87089560396b">MCII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86alignbranchkind">X86AlignBranchKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6797d1aadf1b5f4bc6b67e88e10ad87e">AlignBranchType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d37b4db8d85838aef6d90660e54167e">AlignBoundary</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf628deb6551924471b46d160e41bb1">TargetPrefixMax</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe79f930a87a5333a709f8d17c9442f4">PrevInst</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d5503cd6e1a8a63578aa657f097abf">PrevInstOpcode</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcboundaryalignfragment">MCBoundaryAlignFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13fee0aee2ef97ed348ccd6fc07002fe">PendingBA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> *, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3746012708d70ea6ce763bdc984a01a1">PrevInstPosition</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72630120300a30abb26c2945f612c534">IsRightAfterData</a> = false</td>
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


<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86AsmBackend() {#a51cfff6dff330a39d19c88e0ccd8abf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86AsmBackend.cpp}::X86AsmBackend::X86AsmBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1fe75f600f6eea354189c898829a9465aee32f1149f4d72dc0e46c30ef99b842b">llvm::X86::AlignBranchFused</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1fe75f600f6eea354189c898829a9465a7904634a4e129754fb211d0354b3a6bb">llvm::X86::AlignBranchJcc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1fe75f600f6eea354189c898829a9465a1dc5d1078370bcbec902b4f77717fcbb">llvm::X86::AlignBranchJmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad4b2e7a84faf3d7b6ffb84b541358e00">llvm::assumeAligned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a249ee518076ddd95d8bdae34bd403a39">createMCInstrInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a3dd30d6980185ef34e42333191453867">llvm::MCAsmBackend::MCAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-x86asmbackend-cpp-/#a8f8473d082ffa6af3268b92be91d76c9">anonymous{X86AsmBackend.cpp}::X86AlignBranch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-x86asmbackend-cpp-/#a0acefb208d7fb2bc01efcad87a4d85ee">anonymous{X86AsmBackend.cpp}::X86AlignBranchBoundary</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-x86asmbackend-cpp-/#ab7c0c4e61a820dda83c1d6266d2e5569">anonymous{X86AsmBackend.cpp}::X86AlignBranchKindLoc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-x86asmbackend-cpp-/#a6fd70b871a4433fb39d0af8ef7403e79">anonymous{X86AsmBackend.cpp}::X86AlignBranchWithin32BBoundaries</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-x86asmbackend-cpp-/#afc6b4a4b1b13998c0a99229a9b992dac">anonymous{X86AsmBackend.cpp}::X86PadMaxPrefixSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/darwinx86asmbackend/#a89732d6378fdcd6c7580805844d42f33">anonymous{X86AsmBackend.cpp}::DarwinX86AsmBackend::DarwinX86AsmBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/elfx86asmbackend/#a0cb189d00d8c497e861a7e2eb84eb87a">anonymous{X86AsmBackend.cpp}::ELFX86AsmBackend::ELFX86AsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#ad133d82ed8cf2866b22b7304524935c8">llvm::X86_MC::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/windowsx86asmbackend/#a62674954f25682a018d96d0c7c6b2df2">anonymous{X86AsmBackend.cpp}::WindowsX86AsmBackend::WindowsX86AsmBackend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allowAutoPadding() {#a8a3e9018a72f4ab775773a23480aff17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::allowAutoPadding ()</td>
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

<p>Return true if this target might automatically pad instructions and thus need to emit padding enable/disable directives around sensative code.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1fe75f600f6eea354189c898829a9465ad1140457ba32a450d106fc2010ff66db">llvm::X86::AlignBranchNone</a>.</p>


<p>Referenced by <a href="#a491288fbc508a0628c5ac7df28aa818f">allowEnhancedRelaxation</a>.</p>

</div>
</div>

### allowEnhancedRelaxation() {#a491288fbc508a0628c5ac7df28aa818f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::allowEnhancedRelaxation ()</td>
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

<p>Return true if this target allows an unrelaxable instruction to be emitted into RelaxableFragment and then we can increase its size in a tricky way for optimization.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="#a8a3e9018a72f4ab775773a23480aff17">allowAutoPadding</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-x86asmbackend-cpp-/#a43f30dd8395928416cc42cc0346dffb8">anonymous{X86AsmBackend.cpp}::X86PadForBranchAlign</a>.</p>

</div>
</div>

### applyFixup() {#ac4f1ecc11d292a77e74ca1043c72c8d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmBackend::applyFixup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; char &gt; Data, uint64_t Value, bool IsResolved, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Apply the <span class="doxyComputerOutput">Value</span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate.</p>


<p>Errors (such as an out of range fixup value) should be reported via <span class="doxyComputerOutput">Ctx</span>. The <span class="doxyComputerOutput">STI</span> is present only for fragments of type MCRelaxableFragment and MCDataFragment with hasInstructions() == true.</p>


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">llvm::MCFixupKindInfo::FKF_IsPCRel</a>, <a href="#a8d3619a2032935a5fd9864f3e58208b7">getFixupKindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#ab57022d93dc2497efb738e358dbc1f1b">getFixupKindSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad80b46c754cc7216244a866ec9b1cb0">llvm::isIntN</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitInstructionBegin() {#a38dcf42330d1efcd03d0686ba7bbaf1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmBackend::emitInstructionBegin (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert BoundaryAlignFragment before instructions to align branches.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1fe75f600f6eea354189c898829a9465aee32f1149f4d72dc0e46c30ef99b842b">llvm::X86::AlignBranchFused</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aed79db19d00f742ef88eafad5b074be0">llvm::MCContext::allocFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2f9393965bc0de69da6236c623f79579">llvm::MCStreamer::getCurrentFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a941f547c39a7daf0a48452cc945a835c">llvm::MCObjectStreamer::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#a819849ddb360be005e7c78fad31f754d">isFirstMacroFusibleInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#a3e3ecc5f07c46d1e37b8d7cff83982e6">isRightAfterData</a>.</p>

</div>
</div>

### emitInstructionEnd() {#a8c9b4bc17f742123fb67a743e46e11bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmBackend::emitInstructionEnd (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the last fragment to be aligned for the BoundaryAlignFragment.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aed79db19d00f742ef88eafad5b074be0">llvm::MCContext::allocFragment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a0fa8088b7ca6c8fccd88370bc5be4afa">llvm::MCSection::ensureMinAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2f9393965bc0de69da6236c623f79579">llvm::MCStreamer::getCurrentFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae1b3cf074436ef5b527071540e13bd58">llvm::MCStreamer::getCurrentSectionOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#a3248c8df4d1857db0bf66decdcdcce24">getSizeForInstFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a941f547c39a7daf0a48452cc945a835c">llvm::MCObjectStreamer::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>.</p>

</div>
</div>

### finishLayout() {#a4b45cdd0366bfaa446ebdb3f00d80496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmBackend::finishLayout (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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

<p>Give backend an opportunity to finish layout after relaxation.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a1f3544ccfba8bd153218f9aff934ae23">llvm::MCFragment::FT_Align</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a79f2f5b7f9eccf921287b14be41f29ac">llvm::MCFragment::FT_BoundaryAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a31f0e4803273f2184e596c87e1e05f80">llvm::MCFragment::FT_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68abe5194c45ead6aefe6b0882dcb6f2104">llvm::MCFragment::FT_Relaxable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="#ae14243cebfb18dca997cdca22b151245">mayNeedRelaxation</a>, <a href="#a2fab033607162e6ab1a1d6fb7ed5e07b">padInstructionEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-x86asmbackend-cpp-/#ac5493f0a7c649b6d0ac023f19af7a6c3">anonymous{X86AsmBackend.cpp}::X86PadForAlign</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-x86asmbackend-cpp-/#a43f30dd8395928416cc42cc0346dffb8">anonymous{X86AsmBackend.cpp}::X86PadForBranchAlign</a>.</p>

</div>
</div>

### fixupNeedsRelaxation() {#a6e29d4c5ce17dd4e45009a0cfb31931f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::fixupNeedsRelaxation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t Value)</td>
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

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>.</p>

</div>
</div>

### getFixupKind() {#a628c61cc739e4291331529759a81f2ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MCFixupKind &gt; X86AsmBackend::getFixupKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad60ec34cc0289efdb2530fc622949f83">llvm::MCAsmBackend::getFixupKind</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>

</div>
</div>

### getFixupKindInfo() {#a8d3619a2032935a5fd9864f3e58208b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCFixupKindInfo &amp; X86AsmBackend::getFixupKindInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind)</td>
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

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a02772a67f2052ae04bb9ef1ff9dc3cf8">llvm::FirstTargetFixupKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a845a63cbed041d42d8c3452991d629c4">llvm::FK_NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">llvm::MCFixupKindInfo::FKF_IsPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad4777f004ef52f665e6ec6defc1cb32a">llvm::MCAsmBackend::getFixupKindInfo</a>, <a href="#ac1c7028bd6f6b4b2f3ff9a4fc974a7e0">getNumFixupKinds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca60d9caee92edd1c41f6c7955833953be">llvm::X86::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#ac4f1ecc11d292a77e74ca1043c72c8d2">applyFixup</a>.</p>

</div>
</div>

### getMaximumNopSize() {#a4704062228bd37e6102915129ba326b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86AsmBackend::getMaximumNopSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Returns the maximum size of a nop in bytes on this target.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>Referenced by <a href="#ac8f8a80943df09baa1ccdb938e453639">writeNopData</a>.</p>

</div>
</div>

### getNumFixupKinds() {#ac1c7028bd6f6b4b2f3ff9a4fc974a7e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86AsmBackend.cpp}::X86AsmBackend::getNumFixupKinds ()</td>
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

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca60d9caee92edd1c41f6c7955833953be">llvm::X86::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#a8d3619a2032935a5fd9864f3e58208b7">getFixupKindInfo</a>.</p>

</div>
</div>

### mayNeedRelaxation() {#ae14243cebfb18dca997cdca22b151245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::mayNeedRelaxation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Check whether the given instruction may need relaxation.</p>


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
<td class="doxyParamItemDescription"><p>- The MCSubtargetInfo in effect when the instruction was encoded.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab4ef8f6d88ba8604aa83ce35440fd8fb">llvm::X86::getOpcodeForLongImmediateForm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#acbdae24ff287326bec843d5344366119">isRelaxableBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a4b45cdd0366bfaa446ebdb3f00d80496">finishLayout</a>, <a href="#aec5e1563ca339dbf7905cf069c364e39">padInstructionViaPrefix</a> and <a href="#a112639954fd036a8748791f74d0db6fb">padInstructionViaRelaxation</a>.</p>

</div>
</div>

### padInstructionEncoding() {#a2fab033607162e6ab1a1d6fb7ed5e07b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::padInstructionEncoding (<a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> &amp; RF, <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &amp; Emitter, unsigned &amp; RemainingSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="#aec5e1563ca339dbf7905cf069c364e39">padInstructionViaPrefix</a> and <a href="#a112639954fd036a8748791f74d0db6fb">padInstructionViaRelaxation</a>.</p>


<p>Referenced by <a href="#a4b45cdd0366bfaa446ebdb3f00d80496">finishLayout</a>.</p>

</div>
</div>

### padInstructionViaPrefix() {#aec5e1563ca339dbf7905cf069c364e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::padInstructionViaPrefix (<a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> &amp; RF, <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &amp; Emitter, unsigned &amp; RemainingSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#ac6e1cdbd935a8cc82d9f9f3e1cead86b">llvm::X86_MC::emitPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment/#a6965f7a34449437c164118e26fb9fb64">llvm::MCRelaxableFragment::getAllowAutoPadding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragmentwithfixups/#adeb8e72f8eb5703650627d39457436dd">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getContents</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragmentwithfixups/#a8a0daac469ed602d68174c8efae89b22">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getFixups</a>, <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment/#a970b0dade67a110b2d700dda628054c6">llvm::MCRelaxableFragment::getInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a2c97dba695c5b5fa2bcc39c47c3b0762">llvm::MCEncodedFragment::getSubtargetInfo</a>, <a href="#ae14243cebfb18dca997cdca22b151245">mayNeedRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragmentwithfixups/#a1574158cb7099ca0885c17e2a4c2d210">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::setContents</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a2fab033607162e6ab1a1d6fb7ed5e07b">padInstructionEncoding</a>.</p>

</div>
</div>

### padInstructionViaRelaxation() {#a112639954fd036a8748791f74d0db6fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::padInstructionViaRelaxation (<a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> &amp; RF, <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &amp; Emitter, unsigned &amp; RemainingSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragmentwithfixups/#adeb8e72f8eb5703650627d39457436dd">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getContents</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragmentwithfixups/#a8a0daac469ed602d68174c8efae89b22">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getFixups</a>, <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment/#a970b0dade67a110b2d700dda628054c6">llvm::MCRelaxableFragment::getInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a2c97dba695c5b5fa2bcc39c47c3b0762">llvm::MCEncodedFragment::getSubtargetInfo</a>, <a href="#ae14243cebfb18dca997cdca22b151245">mayNeedRelaxation</a>, <a href="#a85095bdb81f7b2460ce2b158985cdfa9">relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragmentwithfixups/#a1574158cb7099ca0885c17e2a4c2d210">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::setContents</a>, <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment/#ac7e7b8aae133415311dcc543086c9272">llvm::MCRelaxableFragment::setInst</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a2fab033607162e6ab1a1d6fb7ed5e07b">padInstructionEncoding</a>.</p>

</div>
</div>

### relaxInstruction() {#a85095bdb81f7b2460ce2b158985cdfa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmBackend::relaxInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a230d5dad7ea2d94e1671a4aa222a2e15">llvm::MCInst::dump_pretty</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#a9091bc00a994cdb96d1133c21d1f41ec">getRelaxedOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>.</p>


<p>Referenced by <a href="#a112639954fd036a8748791f74d0db6fb">padInstructionViaRelaxation</a>.</p>

</div>
</div>

### shouldForceRelocation() {#a7ab0419e0b93d5d9ae6c68b7857b9b72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::shouldForceRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>.</p>

</div>
</div>

### writeNopData() {#ac8f8a80943df09baa1ccdb938e453639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::writeNopData (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Count, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Write a sequence of optimal nops to the output, covering <span class="doxyComputerOutput">Count</span> bytes.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- true on success, false on failure</p></dd>
</dl>


<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a4704062228bd37e6102915129ba326b5">getMaximumNopSize</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canPadBranches() {#a5c98eb19bd659c5d343384d882315c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::canPadBranches (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### canPadInst() {#abdf1a4f6c701fbc6b903f696792d63b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::canPadInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if we can insert NOP or prefixes automatically before the the instruction to be emitted.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### determinePaddingPrefix() {#a9424257300fecd5e0b13d90e3532859a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t X86AsmBackend::determinePaddingPrefix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> can reduce the bytes of NOP by padding instructions with prefixes to get a better peformance in some cases.</p>


<p>Here, we determine which prefix is the most suitable.</p>


<p>If the instruction has a segment override prefix, use the existing one. If the target is 64-bit, use the CS. If the target is 32-bit,</p>


<ul class="doxyList ">
<li>If the instruction has a ESP/EBP base register, use SS.</li>
<li>Otherwise use DS.</li>
</ul>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### isMacroFused() {#a2cd060cf31ba5e5a5532a991aaf93d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::isMacroFused (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Cmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Jcc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if the two instructions will be macro-fused on the target cpu.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### needAlign() {#a5163f2dbec8129f1ebda594d8d6074bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmBackend::needAlign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if the instruction operand needs to be aligned.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AlignBoundary {#a3d37b4db8d85838aef6d90660e54167e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align anonymous{X86AsmBackend.cpp}::X86AsmBackend::AlignBoundary</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### AlignBranchType {#a6797d1aadf1b5f4bc6b67e88e10ad87e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86AlignBranchKind anonymous{X86AsmBackend.cpp}::X86AsmBackend::AlignBranchType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### IsRightAfterData {#a72630120300a30abb26c2945f612c534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86AsmBackend.cpp}::X86AsmBackend::IsRightAfterData = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### MCII {#a846ef4406f3ecaa75edf87089560396b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MCInstrInfo&gt; anonymous{X86AsmBackend.cpp}::X86AsmBackend::MCII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### PendingBA {#a13fee0aee2ef97ed348ccd6fc07002fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCBoundaryAlignFragment* anonymous{X86AsmBackend.cpp}::X86AsmBackend::PendingBA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### PrevInst {#abe79f930a87a5333a709f8d17c9442f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst anonymous{X86AsmBackend.cpp}::X86AsmBackend::PrevInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### PrevInstOpcode {#ab7d5503cd6e1a8a63578aa657f097abf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86AsmBackend.cpp}::X86AsmBackend::PrevInstOpcode = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### PrevInstPosition {#a3746012708d70ea6ce763bdc984a01a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt;MCFragment *, size_t&gt; anonymous{X86AsmBackend.cpp}::X86AsmBackend::PrevInstPosition</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### STI {#a84dce4acf7a4beb42341108363633186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo&amp; anonymous{X86AsmBackend.cpp}::X86AsmBackend::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

### TargetPrefixMax {#a2bf628deb6551924471b46d160e41bb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86AsmBackend.cpp}::X86AsmBackend::TargetPrefixMax = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
