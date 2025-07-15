---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AArch64AsmPrinter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is intended to be used as a driving class for all asm writers. <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::tuple&lt; unsigned, bool, uint32_t, bool, uint64_t &gt; <a href="#a407c5b30287f1ed88cbfe58fa3243b59">HwasanMemaccessTuple</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e731c6cf972a3720a14d02242ee289a">MInstToMCSymbol</a> = std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6147c1328dbba40094c5b4fa45f8e6d0">AArch64AsmPrinter</a> (TargetMachine &amp;TM, std::unique_ptr&lt; MCStreamer &gt; Streamer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98d2a67d3ff90b12911cb002fc8528ea">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a98d2a67d3ff90b12911cb002fc8528ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81b329962e40cb6da3060ad31f0201b">lowerOperand</a> (const MachineOperand &amp;MO, MCOperand &amp;MCOp) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrapper for MCInstLowering.lowerOperand() for the tblgen'erated pseudo lowering. <a href="#ad81b329962e40cb6da3060ad31f0201b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55d9cc47f7041c1afad87f88ec5c7636">lowerConstantPtrAuth</a> (const ConstantPtrAuth &amp;CPA) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa491a3f3efd1663381a0b3788cbac643">lowerBlockAddressConstant</a> (const BlockAddress &amp;BA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower the specified BlockAddress to an MCExpr. <a href="#aa491a3f3efd1663381a0b3788cbac643">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adae657ab9991540e975726434ee1f053">emitStartOfAsmFile</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This virtual method can be overridden by targets that want to emit something at the start of their file. <a href="#adae657ab9991540e975726434ee1f053">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b744276265a7587d11961d5cbf82dd0">emitJumpTableInfo</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print assembly representations of the jump tables used by the current function to the current output stream. <a href="#a7b744276265a7587d11961d5cbf82dd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, uint64_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a747205569fe3391e3d051822f17c6df3">codeview::JumpTableEntrySize</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea4e708dcae44f8eb91e02c3a3d2e847">getCodeViewJumpTableInfo</a> (int JTI, const MachineInstr *BranchInstr, const MCSymbol *BranchLabel) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets information required to create a CodeView debug symbol for a jump table. <a href="#aea4e708dcae44f8eb91e02c3a3d2e847">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed12387a77f0d475d9cb9b247580257b">emitFunctionEntryLabel</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitFunctionEntryLabel - Emit the label that is the entrypoint for the function. <a href="#aed12387a77f0d475d9cb9b247580257b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1972cf6987294034e568c6423348acd">emitXXStructor</a> (const DataLayout &amp;DL, const Constant *CV) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can override this to change how global constants that are part of a C++ static/global constructor list are emitted. <a href="#ad1972cf6987294034e568c6423348acd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a164e68b3a2bec7c004e7fe6632611400">LowerJumpTableDest</a> (MCStreamer &amp;OutStreamer, const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Small jump tables contain an unsigned byte or half, representing the offset from the lowest-addressed possible destination to the desired basic block. <a href="#a164e68b3a2bec7c004e7fe6632611400">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55c74c151c09190ab2204e33e77b299">LowerHardenedBRJumpTable</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6002788c3c056672d7af9931f11baf3">LowerMOPS</a> (MCStreamer &amp;OutStreamer, const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a727cd7e7e9065ed9ac33e69075c51352">LowerSTACKMAP</a> (MCStreamer &amp;OutStreamer, StackMaps &amp;SM, const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ec8e57004a88ea5cb892311c3c81ff">LowerPATCHPOINT</a> (MCStreamer &amp;OutStreamer, StackMaps &amp;SM, const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a010b554002b5c2fdbc6e2d2b64afedb9">LowerSTATEPOINT</a> (MCStreamer &amp;OutStreamer, StackMaps &amp;SM, const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72864dd5479176074c3bbcc3b0e50c22">LowerFAULTING_OP</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a868e574facfcc4125c0ecac72cfca7">LowerPATCHABLE_FUNCTION_ENTER</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaaf077b7bd69dd161b4fa6257f535e8">LowerPATCHABLE_FUNCTION_EXIT</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9856c715cc73b3fc0e951d4cac490b9">LowerPATCHABLE_TAIL_CALL</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1c4cab46120a38ac573508e15189f9e">LowerPATCHABLE_EVENT_CALL</a> (const MachineInstr &amp;MI, bool Typed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a5214da5fedd168431b377870b2eaea">LowerKCFI_CHECK</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f07768097bdb66d5e2b5bd82e629c3">LowerHWASAN_CHECK_MEMACCESS</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac53de41a4af1d12db6ce7d5a0cf6678">emitHwasanMemaccessSymbols</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae02526f6beecce739c07e81ad631eccc">emitSled</a> (const MachineInstr &amp;MI, SledKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a879a7a14ff0a9e63980908bc502d9">emitPtrauthBranch</a> (const MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2871329035b9e43047202b4ee2198fd">emitPtrauthCheckAuthenticatedValue</a> (Register TestedReg, Register ScratchReg, AArch64PACKey::ID Key, AArch64PAuth::AuthCheckMethod Method, bool ShouldTrap, const MCSymbol *OnFailure)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a code sequence to check an authenticated pointer value. <a href="#ae2871329035b9e43047202b4ee2198fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a143e4c2358a1f5d46268f20f0fc52ba7">emitPtrauthTailCallHardening</a> (const MachineInstr *TC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3227bdb52724365458abe5cb94be8766">emitPtrauthAuthResign</a> (const MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae260c2b32968b1f83af078cb6a1af74d">emitPtrauthDiscriminator</a> (uint16_t Disc, Register AddrDisc, Register ScratchReg, bool MayUseAddrAsScratch=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaf899f496f2ac717a79e58b4e439058">LowerLOADauthptrstatic</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22c90a0d582e484ad655a9f337002b05">LowerMOVaddrPAC</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa50d150829937efa73527accf23a184d">LowerLOADgotAUTH</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53106ebeaa731a23f1cfcb2056717726">lowerPseudoInstExpansion</a> (const MachineInstr *MI, MCInst &amp;Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tblgen'erated driver function for lowering simple MI-&gt;MC pseudo instructions. <a href="#a53106ebeaa731a23f1cfcb2056717726">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f2d85b2edc88b7eef2b10f54506ed77">emitAttributes</a> (unsigned Flags, uint64_t PAuthABIPlatform, uint64_t PAuthABIVersion, AArch64TargetStreamer *TS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a> (MCStreamer &amp;S, const MCInst &amp;Inst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a076ef4dbaa244a975bacf1cef55a68a5">EmitToStreamer</a> (const MCInst &amp;Inst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a> (const MachineInstr *MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets should implement this to emit instructions. <a href="#acdf3f4cb6342e67c42191cf29984df97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8acc616b7a053eae35f4e286905561e6">emitFunctionHeaderComment</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method emits a comment next to header for the current function. <a href="#a8acc616b7a053eae35f4e286905561e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17d725ff2e1212ba5b883e21e03a8040">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a17d725ff2e1212ba5b883e21e03a8040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12edfb6e1007405924bead34e1094488">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a12edfb6e1007405924bead34e1094488">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98344bf2ff39658d712a0715b593e294">lowerConstant</a> (const Constant *CV) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower the specified LLVM Constant to an MCExpr. <a href="#a98344bf2ff39658d712a0715b593e294">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93136fe8e9c29d279acb9857df3d5e45">printOperand</a> (const MachineInstr *MI, unsigned OpNum, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5601e468a107add4678c8bf23d6950e">printAsmMRegister</a> (const MachineOperand &amp;MO, char Mode, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9302fe321e74df05e0581af991980391">printAsmRegInClass</a> (const MachineOperand &amp;MO, const TargetRegisterClass *RC, unsigned AltName, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca8cdd9245e96ea418eadd178f166c59">PrintAsmOperand</a> (const MachineInstr *MI, unsigned OpNum, const char *ExtraCode, raw_ostream &amp;O) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant. <a href="#aca8cdd9245e96ea418eadd178f166c59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0faaa94ab2b79a3da969d8fdfc277559">PrintAsmMemoryOperand</a> (const MachineInstr *MI, unsigned OpNum, const char *ExtraCode, raw_ostream &amp;O) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant as an address. <a href="#a0faaa94ab2b79a3da969d8fdfc277559">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa697c21dd83271adbb10146119d72439">PrintDebugValueComment</a> (const MachineInstr *MI, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26bf6aaf463af108bd651a016498bdbe">emitFunctionBodyEnd</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can override this to emit stuff after the last basic block in the function. <a href="#a26bf6aaf463af108bd651a016498bdbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a680fe1527f7ea4896ffc41579daa24cc">emitGlobalAlias</a> (const Module &amp;M, const GlobalAlias &amp;GA) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ac137a140e1c486f927c31c832186d">GetCPISymbol</a> (unsigned CPID) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetCPISymbol - Return the symbol for the specified constant pool entry. <a href="#a46ac137a140e1c486f927c31c832186d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26852762ffb57a0de3e876717ddd88b4">emitEndOfAsmFile</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This virtual method can be overridden by targets that want to emit something at the end of their file. <a href="#a26852762ffb57a0de3e876717ddd88b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7901297f47afe0c9011a3fa7b761ea55">emitLOHs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the LOHs contained in AArch64FI. <a href="#a7901297f47afe0c9011a3fa7b761ea55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f03b50815725f7303ca0d641bd5dbb7">emitMovXReg</a> (Register Dest, Register Src)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01219c22198d4bf97bbc80614d725dee">emitMOVZ</a> (Register Dest, uint64_t Imm, unsigned Shift)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45cd3ebb211362ac1cb75dc87cd9589a">emitMOVK</a> (Register Dest, uint64_t Imm, unsigned Shift)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaf5a680481887f4e12eb1c05ea88246">emitFMov0</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit instruction to set float register to zero. <a href="#adaf5a680481887f4e12eb1c05ea88246">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e5d3fbea430b05e2ab66e59272dad74">shouldEmitWeakSwiftAsyncExtendedFramePointerFlags</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4a3b5addb966936642ca3e739821dae">getIFuncMCSubtargetInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aebe7e48735a59049062e384e810c108a">getSubtargetInfo()</a> cannot be used where this is needed because we don't have a MachineFunction when we're lowering a GlobalIFunc, and getSubtargetInfo requires one. <a href="#aa4a3b5addb966936642ca3e739821dae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63598a46552eebe6c97a73eff19c92eb">emitMachOIFuncStubBody</a> (Module &amp;M, const GlobalIFunc &amp;GI, MCSymbol *LazyPointer) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc7f7e7dd9a92f9b341769e35ce3342">emitMachOIFuncStubHelperBody</a> (Module &amp;M, const GlobalIFunc &amp;GI, MCSymbol *LazyPointer) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a05e623abac07886816e57e1d98a4b">recordIfImportCall</a> (const MachineInstr *BranchInst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if this instruction is part of a sequence that is eligle for import call optimization and, if so, records it to be emitted in the import call section. <a href="#aa8a05e623abac07886816e57e1d98a4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="#a407c5b30287f1ed88cbfe58fa3243b59">HwasanMemaccessTuple</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8176dd790cc6ce20c0854ee8373788d5">HwasanMemaccessSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower">AArch64MCInstLower</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a835553ea49764c8664ed2cb0ec36bae2">MCInstLowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/faultmaps">FaultMaps</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f63b3c1765d8ba2ef1eb56e18f0b2a8">FM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96558d1445f3b7b5cc612aaf7fc0adf8">STI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e20c2ccf75eb5469cbae6d626f72a17">ShouldEmitWeakSwiftAsyncExtendedFramePointerFlags</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbf433a9809bab5a6b55573cdaa4dd5f">InstsEmitted</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *, std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033a49f0a3ab777caac2e1853309c661">SectionToImportedFunctionCalls</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo">AArch64FunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16a6b5862f9f83212dd78dad76812bf1">AArch64FI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MInstToMCSymbol</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adccf68774f4a4d8264875363e3f330b2">LOHInstToLabel</a></td>
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


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### HwasanMemaccessTuple {#a407c5b30287f1ed88cbfe58fa3243b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::tuple&lt;unsigned, bool, uint32_t, bool, uint64_t&gt; anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::HwasanMemaccessTuple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### MInstToMCSymbol {#a9e731c6cf972a3720a14d02242ee289a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::MInstToMCSymbol =  std::map&lt;const MachineInstr *, MCSymbol *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AArch64AsmPrinter() {#a6147c1328dbba40094c5b4fa45f8e6d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::AArch64AsmPrinter (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &gt; Streamer)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#afcfe4636c15aaef711e33ecc8638f9b4">llvm::AsmPrinter::AsmPrinter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitAttributes() {#a9f2d85b2edc88b7eef2b10f54506ed77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitAttributes (unsigned Flags, uint64_t PAuthABIPlatform, uint64_t PAuthABIVersion, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer">AArch64TargetStreamer</a> * TS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#ad2f2d095653918c60172f948524442a0a8040351a645af569f250de2e02b541d4">llvm::AArch64BuildAttrs::AEABI_FEATURE_AND_BITS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#ad2f2d095653918c60172f948524442a0a1d86e09f81241e3af64dbee7469869e0">llvm::AArch64BuildAttrs::AEABI_PAUTHABI</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a1b052670a8e9d827535baa7fbddf87de">llvm::AArch64TargetStreamer::emitAtributesSubsection</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a9781e70abbf0d410b270711d57097666">llvm::AArch64TargetStreamer::emitAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a02cbf821981385925f75eba32badbe8eab816b190d63b3b96519a82af9b9a125f">llvm::AArch64BuildAttrs::Feature_BTI_Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a02cbf821981385925f75eba32badbe8ea58cb58cf47368adad995c77f76dd6e92">llvm::AArch64BuildAttrs::Feature_GCS_Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a02cbf821981385925f75eba32badbe8ea34cd5242b7d08fc2fbab8c9198e5548a">llvm::AArch64BuildAttrs::Feature_PAC_Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a26559a9763f5d95c22f17698ec2c8c06">llvm::AArch64BuildAttrs::getVendorName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#aed8b1a71c71c0448f7abc8a6ee32c95ca177d5447cb7a2b6e6c8b13397fdecab0">llvm::AArch64BuildAttrs::OPTIONAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#aed8b1a71c71c0448f7abc8a6ee32c95ca1be39cb5280290892398ab312e199b8a">llvm::AArch64BuildAttrs::REQUIRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a898116664a716f1ccf6c58afc7718863a18ca061e3f2810477c52f9de8801f975">llvm::AArch64BuildAttrs::TAG_FEATURE_BTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a898116664a716f1ccf6c58afc7718863aa310972cb7b9330a266fbde0acaca074">llvm::AArch64BuildAttrs::TAG_FEATURE_GCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a898116664a716f1ccf6c58afc7718863a0ce80b04d6976789fedea754ab2061bc">llvm::AArch64BuildAttrs::TAG_FEATURE_PAC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#ac35783f29186ae9f470ec2969c9cb952a293cacaac39b4f7083fd3a9ddea61791">llvm::AArch64BuildAttrs::TAG_PAUTH_PLATFORM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#ac35783f29186ae9f470ec2969c9cb952a399da32a3e92753a305b2bbe05dc77af">llvm::AArch64BuildAttrs::TAG_PAUTH_SCHEMA</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#ad81567845cc9fba4339ba1a69712f211a8032b483a40e2c705a7e6cafecf8c1a7">llvm::AArch64BuildAttrs::ULEB128</a>.</p>


<p>Referenced by <a href="#adae657ab9991540e975726434ee1f053">emitStartOfAsmFile</a> and <a href="#a53106ebeaa731a23f1cfcb2056717726">lowerPseudoInstExpansion</a>.</p>

</div>
</div>

### emitFunctionEntryLabel() {#aed12387a77f0d475d9cb9b247580257b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitFunctionEntryLabel ()</td>
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

<p>EmitFunctionEntryLabel - Emit the label that is the entrypoint for the function.</p>


<p>This can be overridden by targets as required to do custom stuff.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca300efd85d130657d0d06f0469980bd0f">llvm::CallingConv::AArch64_SVE_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca0e62ecb2c693281fafd77f39b2ddd284">llvm::CallingConv::AArch64_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa06f7388d0cc9b44ece08cdf56c0ecf0">llvm::AsmPrinter::CurrentFnSym</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#aa018a060cbd20ff0e227cff1f329cbdd">llvm::AArch64TargetStreamer::emitDirectiveVariantPCS</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae8edc50d690d43b67f033f0acf46cd04">llvm::AsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a093615ad7a3c3eac2dc8c8655d0ac00b">llvm::AArch64FunctionInfo::isSVECC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243aa96e85228ec0460e2b923801660b33f9">llvm::MCSA_WeakAntiDep</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa1316da87e093c08b6657877572b19a4">llvm::AsmPrinter::MMI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>

</div>
</div>

### emitFunctionHeaderComment() {#a8acc616b7a053eae35f4e286905561e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitFunctionHeaderComment ()</td>
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

<p>This method emits a comment next to header for the current function.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#adda0b11bd1bc8d81e88218a69f78b309">llvm::AArch64FunctionInfo::getOutliningStyle</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>.</p>

</div>
</div>

### emitHwasanMemaccessSymbols() {#aac53de41a4af1d12db6ce7d5a0cf6678}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitHwasanMemaccessSymbols (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hwasanaccessinfo/#a77974eb2159da3c86095fa98c8c148f1a3d9acaec708a77cbe6c60c019588fe15">llvm::HWASanAccessInfo::AccessSizeShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hwasanaccessinfo/#a77974eb2159da3c86095fa98c8c148f1a93a25190198abc8bb4ada84b62c1c312">llvm::HWASanAccessInfo::CompileKernelShift</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#a84d44e8b0d35d0b19946a50e8229ab86">llvm::AArch64MCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a832ad315a355f4ddcc32f189f34e28a9">llvm::AArch64_AM::encodeLogicalImmediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28a756347c46f7abfa1e1fefcc39502c680">llvm::AArch64CC::EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#aeae88f12b667477f90db9b726556b337">llvm::AArch64_AM::getShifterImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hwasanaccessinfo/#a77974eb2159da3c86095fa98c8c148f1a2be060e0fe7732ea7b7cfda87b33282d">llvm::HWASanAccessInfo::HasMatchAllShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28aa5506efe3dc67f7b794331f0cbffddaf">llvm::AArch64CC::HI</a>, <a href="#a8176dd790cc6ce20c0854ee8373788d5">HwasanMemaccessSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28afdd8238d6005774fe2bb9067de76eb8c">llvm::AArch64CC::LS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a7e1384a3b7d612a03b54d9c8f2071a04">llvm::AArch64_AM::LSR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hwasanaccessinfo/#a77974eb2159da3c86095fa98c8c148f1abcbf592cb37a50340733b22e9c5edcb5">llvm::HWASanAccessInfo::MatchAllShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ad0efc318f7416b800a38c5cc42ddbfa9">llvm::MCSA_ELF_TypeFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ae472359b991bb5235c8f6714f4cacb6a">llvm::MCSA_Hidden</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a83df6138e7dba38c0c80380486544ea0">llvm::MCSA_Weak</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28a191e89dbc4939ebd0b572cae44aac05f">llvm::AArch64CC::NE</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hwasanaccessinfo/#a6a60d4a4e7d76d3079a1c65c0f1d545ea480da4492bfc24f8380714233b147084">llvm::HWASanAccessInfo::RuntimeMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015affae0e6af56cc351c85d9c208e27af02">llvm::ELF::SHF_EXECINSTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa4128c7283d8e6e763e8810a91c2dc1e">llvm::ELF::SHF_GROUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaa3e719e2fda5e6446235fedc1024897e">llvm::AArch64MCExpr::VK_GOT_LO12</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa9df90d2efd141370b894bd4749ed184c">llvm::AArch64MCExpr::VK_GOT_PAGE</a>.</p>

</div>
</div>

### emitInstruction() {#acdf3f4cb6342e67c42191cf29984df97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *)</td>
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

<p>Targets should implement this to emit instructions.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a47f45e65244c17ec9fa8771a5c6d60e1">llvm::ARM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa92c1e2c33abf7fb64f544b67f234df6">llvm::AsmPrinter::createTempSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a13e61d356736ddb78b0bfadf043860cc">llvm::AsmPrinter::CurrentFnBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ab7c176a4950570191e032fbe706d2f4a">llvm::AsmPrinter::CurrentPatchableFunctionEntrySym</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84ab4fe87e4046ecd1f9f3d96bbf63822b3">llvm::DwarfCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#aa5c4a37e333231fdd859c3ceb075e6e8">llvm::AArch64TargetStreamer::emitARM64WinCFIAddFP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a82ca910e7320cb63ab53987c6fb677c0">llvm::AArch64TargetStreamer::emitARM64WinCFIAllocStack</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#aca4f219b20d84d22c459efa5e2c254e0">llvm::AArch64TargetStreamer::emitARM64WinCFIEpilogEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#afc5e153b1f317f9ba752e6dbb5c0392a">llvm::AArch64TargetStreamer::emitARM64WinCFIEpilogStart</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ae08fadf21209c54325db3056968d5203">llvm::AArch64TargetStreamer::emitARM64WinCFINop</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a4b9a743db10cc6c897cd0ac678ff1c4c">llvm::AArch64TargetStreamer::emitARM64WinCFIPACSignLR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#aceec3dbba21113d555ea94fe4b472de2">llvm::AArch64TargetStreamer::emitARM64WinCFIPrologEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a31ba33e6b992f002b916b0224f900282">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegQP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ac1013120808337fef474c1264a592ba9">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegQPX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#aa8de48c0a4da7b3a8b4994d451b9b246">llvm::AArch64TargetStreamer::emitARM64WinCFISaveFPLR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a84fdbba804aaa3bddeca1a69c2bb4029">llvm::AArch64TargetStreamer::emitARM64WinCFISaveFPLRX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a44677421d479b0f5839d10e2ef35f299">llvm::AArch64TargetStreamer::emitARM64WinCFISaveFReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ab41f05f5b25ee7961c198f5f19002e16">llvm::AArch64TargetStreamer::emitARM64WinCFISaveFRegP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a7314b9feb4a2f444de19656f2ec6b2c2">llvm::AArch64TargetStreamer::emitARM64WinCFISaveFRegPX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ac2d469ec3052bb66b3d1c6dcd2ea93a9">llvm::AArch64TargetStreamer::emitARM64WinCFISaveFRegX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ae75c9f81c7fa8aee8813c6bd9023eee9">llvm::AArch64TargetStreamer::emitARM64WinCFISaveLRPair</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ae0235fe4ba101b9cdd00f83ed0044b7f">llvm::AArch64TargetStreamer::emitARM64WinCFISaveReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a105a5c8833b0af64cfa8b33929a26e99">llvm::AArch64TargetStreamer::emitARM64WinCFISaveRegP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a249025898dbac8185b1083fb3d33d163">llvm::AArch64TargetStreamer::emitARM64WinCFISaveRegPX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a7698b71bb0682ee226911926deded1b6">llvm::AArch64TargetStreamer::emitARM64WinCFISaveRegX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ac393333718fb952b901dddd7c02d0f33">llvm::AArch64TargetStreamer::emitARM64WinCFISetFP</a>, <a href="#a3227bdb52724365458abe5cb94be8766">emitPtrauthAuthResign</a>, <a href="#a17a879a7a14ff0a9e63980908bc502d9">emitPtrauthBranch</a>, <a href="#ae260c2b32968b1f83af078cb6a1af74d">emitPtrauthDiscriminator</a>, <a href="#a143e4c2358a1f5d46268f20f0fc52ba7">emitPtrauthTailCallHardening</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a58ce8a43545e21a3a78975f2ee6e1576">llvm::AsmPrinter::getFunctionCFISectionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a22f623563f43de6d1aabcdfa9d341031">llvm::AArch64_AM::getShiftValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46aaf2ff1a10f3f3b211d7781a33e4c1e05">llvm::AArch64PACKey::IA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46a438dbcc76b79fb10acb447ec5d141287">llvm::AArch64PACKey::IB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a0b4cc9aee6e5aaf329ecd8e3856833e8">llvm::AArch64InstrInfo::isTailCallReturnInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ad50f5d7186d7a17abb53860320a2a5b1">llvm::AsmPrinter::isVerbose</a>, <a href="#a72864dd5479176074c3bbcc3b0e50c22">LowerFAULTING_OP</a>, <a href="#ab55c74c151c09190ab2204e33e77b299">LowerHardenedBRJumpTable</a>, <a href="#a03f07768097bdb66d5e2b5bd82e629c3">LowerHWASAN_CHECK_MEMACCESS</a>, <a href="#a164e68b3a2bec7c004e7fe6632611400">LowerJumpTableDest</a>, <a href="#a6a5214da5fedd168431b377870b2eaea">LowerKCFI_CHECK</a>, <a href="#adaf899f496f2ac717a79e58b4e439058">LowerLOADauthptrstatic</a>, <a href="#aa50d150829937efa73527accf23a184d">LowerLOADgotAUTH</a>, <a href="#ae6002788c3c056672d7af9931f11baf3">LowerMOPS</a>, <a href="#a22c90a0d582e484ad655a9f337002b05">LowerMOVaddrPAC</a>, <a href="#ab1c4cab46120a38ac573508e15189f9e">LowerPATCHABLE_EVENT_CALL</a>, <a href="#a6a868e574facfcc4125c0ecac72cfca7">LowerPATCHABLE_FUNCTION_ENTER</a>, <a href="#afaaf077b7bd69dd161b4fa6257f535e8">LowerPATCHABLE_FUNCTION_EXIT</a>, <a href="#ab9856c715cc73b3fc0e951d4cac490b9">LowerPATCHABLE_TAIL_CALL</a>, <a href="#af3ec8e57004a88ea5cb892311c3c81ff">LowerPATCHPOINT</a>, <a href="#a53106ebeaa731a23f1cfcb2056717726">lowerPseudoInstExpansion</a>, <a href="#a727cd7e7e9065ed9ac33e69075c51352">LowerSTACKMAP</a>, <a href="#a010b554002b5c2fdbc6e2d2b64afedb9">LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a47692fd7344d1adc2916ad4cc31d26c8">llvm::AsmPrinter::MAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a6d9cfbe4ea54a3ce9d5308efab7200b9">llvm::AArch64II::MO_G0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a30eefa1143a0a238486ada4ff95bc34b">llvm::AArch64II::MO_G1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a028a4adc46c746ba1501e1e6fefb54cc">llvm::AArch64II::MO_NC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a7f04634c15a04a59d5f234002e613b5b">llvm::AArch64II::MO_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a3a5053185998bdf24f3167c234915785">llvm::AArch64II::MO_PAGEOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a39261c05ab3afff5126eb55ee51fed44">llvm::AArch64II::MO_S</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71add46ede0892fdd429e940eb97c1e6e55">llvm::AArch64II::MO_TLS</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af13923757ac4e6379f33a942c8e57295a6adf97f83acf6453d4a6a4b1070f3754">llvm::AsmPrinter::None</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad407b071bad6c9a435cade250ec8c8b6">llvm::MachineOperand::setTargetFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#adfcde4e021a2e59edfa21733753ef8f9">llvm::AsmPrinter::SM</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>.</p>

</div>
</div>

### emitJumpTableInfo() {#a7b744276265a7587d11961d5cbf82dd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitJumpTableInfo ()</td>
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

<p>Print assembly representations of the jump tables used by the current function to the current output stream.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a18a49f94de6b90d6fbc0c730b6a2ae5b">llvm::MCBinaryExpr::createLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa321836ddd72df66be5551323b3090d9">llvm::AsmPrinter::emitAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a6394f827ff52599d99f5dcb5f046efc3">llvm::AsmPrinter::GetJTISymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#af9c60f4a0193375a5dd205fb945107a8">llvm::MachineJumpTableInfo::getJumpTables</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a0580b05cc0794957d4ac1ce2f209ac87">llvm::AsmPrinter::getObjFileLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2e6b27fe4ea0394cff6ef3071a84ccc8">llvm::TargetLoweringObjectFile::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>

</div>
</div>

### emitPtrauthAuthResign() {#a3227bdb52724365458abe5cb94be8766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitPtrauthAuthResign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa92c1e2c33abf7fb64f544b67f234df6">llvm::AsmPrinter::createTempSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba79935518a3889663d8688b6b01fff051">Default</a>, <a href="#ae2871329035b9e43047202b4ee2198fd">emitPtrauthCheckAuthenticatedValue</a>, <a href="#ae260c2b32968b1f83af078cb6a1af74d">emitPtrauthDiscriminator</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adeaafd19e35dd177bb6c9daa0247fbda">llvm::getAUTOpcodeForKey</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcbcb9cd48f8f0399387bfa5c2b6e80d">llvm::getPACOpcodeForKey</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba02b848adda8d7d33a2b25d87dbef1d75">Poison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a2d74031c97cfd5385d4273d39c37a2f8">PtrauthAuthChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba178e499decd0c21272bc34e4b3056eab">Trap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286badf8edafdc44e6862bee7a37abddd6b28">Unchecked</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64pauth/#abf78b4a589091577668be8331dbf3e10ae34527c9d45ac8d5e68634911bfcd36e">llvm::AArch64PAuth::XPAC</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### emitPtrauthBranch() {#a17a879a7a14ff0a9e63980908bc502d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitPtrauthBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#ae260c2b32968b1f83af078cb6a1af74d">emitPtrauthDiscriminator</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46aaf2ff1a10f3f3b211d7781a33e4c1e05">llvm::AArch64PACKey::IA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46a438dbcc76b79fb10acb447ec5d141287">llvm::AArch64PACKey::IB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### emitPtrauthCheckAuthenticatedValue() {#ae2871329035b9e43047202b4ee2198fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitPtrauthCheckAuthenticatedValue (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> TestedReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ScratchReg, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46">AArch64PACKey::ID</a> Key, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64pauth/#abf78b4a589091577668be8331dbf3e10">AArch64PAuth::AuthCheckMethod</a> Method, bool ShouldTrap, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * OnFailure)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits a code sequence to check an authenticated pointer value.</p>


<p>If OnFailure argument is passed, jump there on check failure instead of proceeding to the next instruction (only if ShouldTrap is false).</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa92c1e2c33abf7fb64f544b67f234df6">llvm::AsmPrinter::createTempSymbol</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28a756347c46f7abfa1e1fefcc39502c680">llvm::AArch64CC::EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd04b8a497d63d4f11a884ac2ec54f53">llvm::getWRegFromXReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c635acfc68033798540dea72a03fced">llvm::getXPACOpcodeForKey</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46aaf2ff1a10f3f3b211d7781a33e4c1e05">llvm::AArch64PACKey::IA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46a438dbcc76b79fb10acb447ec5d141287">llvm::AArch64PACKey::IB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>.</p>


<p>Referenced by <a href="#a3227bdb52724365458abe5cb94be8766">emitPtrauthAuthResign</a>, <a href="#a143e4c2358a1f5d46268f20f0fc52ba7">emitPtrauthTailCallHardening</a>, <a href="#aa50d150829937efa73527accf23a184d">LowerLOADgotAUTH</a> and <a href="#a22c90a0d582e484ad655a9f337002b05">LowerMOVaddrPAC</a>.</p>

</div>
</div>

### emitPtrauthDiscriminator() {#ae260c2b32968b1f83af078cb6a1af74d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register AArch64AsmPrinter::emitPtrauthDiscriminator (uint16_t Disc, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> AddrDisc, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ScratchReg, bool MayUseAddrAsScratch=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>, <a href="#a3227bdb52724365458abe5cb94be8766">emitPtrauthAuthResign</a>, <a href="#a17a879a7a14ff0a9e63980908bc502d9">emitPtrauthBranch</a> and <a href="#a22c90a0d582e484ad655a9f337002b05">LowerMOVaddrPAC</a>.</p>

</div>
</div>

### emitPtrauthTailCallHardening() {#a143e4c2358a1f5d46268f20f0fc52ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitPtrauthTailCallHardening (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * TC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae2871329035b9e43047202b4ee2198fd">emitPtrauthCheckAuthenticatedValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46aaf2ff1a10f3f3b211d7781a33e4c1e05">llvm::AArch64PACKey::IA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46a438dbcc76b79fb10acb447ec5d141287">llvm::AArch64PACKey::IB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64pauth/#abf78b4a589091577668be8331dbf3e10a6adf97f83acf6453d4a6a4b1070f3754">llvm::AArch64PAuth::None</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a2380c209ae5339835b5e6ea6d5c197ad">llvm::MachineInstr::readsRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### emitSled() {#ae02526f6beecce739c07e81ad631eccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitSled (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac40b688a96b903167e07f7555c2a1e11">SledKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aebe7e48735a59049062e384e810c108a">llvm::AsmPrinter::getSubtargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a7c868807760d76531432d5a31b6938dc">llvm::AsmPrinter::recordSled</a>.</p>


<p>Referenced by <a href="#a6a868e574facfcc4125c0ecac72cfca7">LowerPATCHABLE_FUNCTION_ENTER</a>, <a href="#afaaf077b7bd69dd161b4fa6257f535e8">LowerPATCHABLE_FUNCTION_EXIT</a> and <a href="#ab9856c715cc73b3fc0e951d4cac490b9">LowerPATCHABLE_TAIL_CALL</a>.</p>

</div>
</div>

### emitStartOfAsmFile() {#adae657ab9991540e975726434ee1f053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitStartOfAsmFile (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>This virtual method can be overridden by targets that want to emit something at the start of their file.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="#a9f2d85b2edc88b7eef2b10f54506ed77">emitAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a86397deb1d9d25f7a17ce22c4d66482f">llvm::mdconst::extract_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a02cbf821981385925f75eba32badbe8eab816b190d63b3b96519a82af9b9a125f">llvm::AArch64BuildAttrs::Feature_BTI_Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a02cbf821981385925f75eba32badbe8ea58cb58cf47368adad995c77f76dd6e92">llvm::AArch64BuildAttrs::Feature_GCS_Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a02cbf821981385925f75eba32badbe8ea34cd5242b7d08fc2fbab8c9198e5548a">llvm::AArch64BuildAttrs::Feature_PAC_Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ad7c1a423dcb8902227d283ae557d796daaee4b4612443a368a6cde0ce5290e63e">llvm::ELF::GNU_PROPERTY_AARCH64_FEATURE_1_BTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ad7c1a423dcb8902227d283ae557d796dafeddef35e624a89d2d853a48b03d08fb">llvm::ELF::GNU_PROPERTY_AARCH64_FEATURE_1_GCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ad7c1a423dcb8902227d283ae557d796daee1620a4dde012c1639e5d326a2ea626">llvm::ELF::GNU_PROPERTY_AARCH64_FEATURE_1_PAC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#aeffa16735e18df727a173beaf748c392ab83c0455617c46ec3925cdde3af8eae1">llvm::COFF::GuardCF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#aeffa16735e18df727a173beaf748c392a68904e24926ad660410211e499d0103c">llvm::COFF::GuardEHCont</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115afc617a23fd5e4cce7f2adfc7c2966e1c">llvm::COFF::IMAGE_SYM_CLASS_STATIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120a33430600d344c962f55f3c48635d0e3d">llvm::COFF::IMAGE_SYM_DTYPE_NULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#aeffa16735e18df727a173beaf748c392afc9a0b86b447c82c074e8773b04391e1">llvm::COFF::Kernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243aa1e94c23156e37812e4d6e078af1d728">llvm::MCSA_Global</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa1316da87e093c08b6657877572b19a4">llvm::AsmPrinter::MMI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>

</div>
</div>

### EmitToStreamer() {#ad227b3ae621f2b01c29ad057c72348e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::EmitToStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a>.</p>


<p>Referenced by <a href="#aac53de41a4af1d12db6ce7d5a0cf6678">emitHwasanMemaccessSymbols</a>, <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>, <a href="#a3227bdb52724365458abe5cb94be8766">emitPtrauthAuthResign</a>, <a href="#a17a879a7a14ff0a9e63980908bc502d9">emitPtrauthBranch</a>, <a href="#ae2871329035b9e43047202b4ee2198fd">emitPtrauthCheckAuthenticatedValue</a>, <a href="#ae02526f6beecce739c07e81ad631eccc">emitSled</a>, <a href="#a076ef4dbaa244a975bacf1cef55a68a5">EmitToStreamer</a>, <a href="#a72864dd5479176074c3bbcc3b0e50c22">LowerFAULTING_OP</a>, <a href="#ab55c74c151c09190ab2204e33e77b299">LowerHardenedBRJumpTable</a>, <a href="#a03f07768097bdb66d5e2b5bd82e629c3">LowerHWASAN_CHECK_MEMACCESS</a>, <a href="#a164e68b3a2bec7c004e7fe6632611400">LowerJumpTableDest</a>, <a href="#a6a5214da5fedd168431b377870b2eaea">LowerKCFI_CHECK</a>, <a href="#adaf899f496f2ac717a79e58b4e439058">LowerLOADauthptrstatic</a>, <a href="#aa50d150829937efa73527accf23a184d">LowerLOADgotAUTH</a>, <a href="#ae6002788c3c056672d7af9931f11baf3">LowerMOPS</a>, <a href="#a22c90a0d582e484ad655a9f337002b05">LowerMOVaddrPAC</a>, <a href="#ab1c4cab46120a38ac573508e15189f9e">LowerPATCHABLE_EVENT_CALL</a>, <a href="#af3ec8e57004a88ea5cb892311c3c81ff">LowerPATCHPOINT</a>, <a href="#a53106ebeaa731a23f1cfcb2056717726">lowerPseudoInstExpansion</a>, <a href="#a727cd7e7e9065ed9ac33e69075c51352">LowerSTACKMAP</a> and <a href="#a010b554002b5c2fdbc6e2d2b64afedb9">LowerSTATEPOINT</a>.</p>

</div>
</div>

### EmitToStreamer() {#a076ef4dbaa244a975bacf1cef55a68a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::EmitToStreamer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>.</p>

</div>
</div>

### emitXXStructor() {#ad1972cf6987294034e568c6423348acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitXXStructor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * CV)</td>
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

<p>Targets can override this to change how global constants that are part of a C++ static/global constructor list are emitted.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantptrauth/#a1aafc5d3e329d810097927b58f8e9018a4d2079851c19a7b47d074466789d9268">llvm::ConstantPtrAuth::AddrDiscriminator_CtorsDtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ad7397e97eeca3d8738c3524df6cf17db">llvm::AsmPrinter::emitXXStructor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a17d725ff2e1212ba5b883e21e03a8040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a83d7606b4830b8a51e2b3e12bf83632a">llvm::AsmPrinter::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af22b06a6a4f9df80454071685a0d6a02">llvm::AnalysisUsage::setPreservesAll</a>.</p>

</div>
</div>

### getCodeViewJumpTableInfo() {#aea4e708dcae44f8eb91e02c3a3d2e847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; const MCSymbol *, uint64_t, const MCSymbol *, codeview::JumpTableEntrySize &gt; AArch64AsmPrinter::getCodeViewJumpTableInfo (int JTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * BranchInstr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * BranchLabel)</td>
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

<p>Gets information required to create a CodeView debug symbol for a jump table.</p>


<p>Return value is &lt;Base Address, Base Offset, Branch Address, Entry Size&gt;</p>


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a747205569fe3391e3d051822f17c6df3ac06129f6e6e15c09328365e553f1dc31">llvm::codeview::Int32</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a747205569fe3391e3d051822f17c6df3a8fe014122e48544f0d8aa9f113231269">llvm::codeview::UInt16ShiftLeft</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a747205569fe3391e3d051822f17c6df3a391fef06cae4aaaea682ae6fb79824f4">llvm::codeview::UInt8ShiftLeft</a>.</p>

</div>
</div>

### getPassName() {#a98d2a67d3ff90b12911cb002fc8528ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### lowerBlockAddressConstant() {#aa491a3f3efd1663381a0b3788cbac643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * AArch64AsmPrinter::lowerBlockAddressConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> &amp; BA)</td>
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

<p>Lower the specified BlockAddress to an MCExpr.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a59ab715efa8fa45d1299021a831eb619">llvm::AArch64AuthMCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddress/#abb524f716e3a2a50acacf3e3df344662">llvm::BlockAddress::getFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46aaf2ff1a10f3f3b211d7781a33e4c1e05">llvm::AArch64PACKey::IA</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#afde96322ddbdb044b3ab0525ce73e775">llvm::AsmPrinter::lowerBlockAddressConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>.</p>

</div>
</div>

### lowerConstant() {#a98344bf2ff39658d712a0715b593e294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * AArch64AsmPrinter::lowerConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * CV)</td>
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

<p>Lower the specified LLVM Constant to an MCExpr.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac2b1c517d194a6bdd00f66bce97f52c3">llvm::AsmPrinter::lowerConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>.</p>

</div>
</div>

### lowerConstantPtrAuth() {#a55d9cc47f7041c1afad87f88ec5c7636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * AArch64AsmPrinter::lowerConstantPtrAuth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantptrauth">ConstantPtrAuth</a> &amp; CPA)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a59ab715efa8fa45d1299021a831eb619">llvm::AArch64AuthMCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a4447dfc5ac5a8784a0a933a5be56bbf5">llvm::LLVMContext::emitError</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae4a28f2ce2647934f469d4bb2144612a">llvm::AsmPrinter::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/constantptrauth/#aa847cae058691cafe0cbc8f2eecb331a">llvm::ConstantPtrAuth::getDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/constantptrauth/#a9c3928485f63866f20e21c67776300e7">llvm::ConstantPtrAuth::getKey</a>, <a href="/web-llvm/docs/api/classes/llvm/constantptrauth/#a3c2cbd0f884675d985f2aa0ee4509ddf">llvm::ConstantPtrAuth::getPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantptrauth/#aa00425fe33970121f8400670ad3534f3">llvm::ConstantPtrAuth::hasAddressDiscriminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46a759ecca259756790f64e470254a4e886">llvm::AArch64PACKey::LAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a23c582e2452eeb2b2cf6e0c43eca617e">llvm::Value::stripAndAccumulateConstantOffsets</a>.</p>

</div>
</div>

### LowerFAULTING\_OP() {#a72864dd5479176074c3bbcc3b0e50c22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerFAULTING_OP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/faultmaps/#a2ac4523a1a2880c65cac16a68fefa123a9b39cb664cbe64ecfba3f4bf6e81958c">llvm::FaultMaps::FaultKindMax</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1cc134bd22a318835dc929323da70ea4">llvm::MachineBasicBlock::getSymbol</a>, <a href="#ad81b329962e40cb6da3060ad31f0201b">lowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerHardenedBRJumpTable() {#ab55c74c151c09190ab2204e33e77b299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerHardenedBRJumpTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#af9c60f4a0193375a5dd205fb945107a8">llvm::MachineJumpTableInfo::getJumpTables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28afdd8238d6005774fe2bb9067de76eb8c">llvm::AArch64CC::LS</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a028a4adc46c746ba1501e1e6fefb54cc">llvm::AArch64II::MO_NC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a7f04634c15a04a59d5f234002e613b5b">llvm::AArch64II::MO_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a3a5053185998bdf24f3167c234915785">llvm::AArch64II::MO_PAGEOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad407b071bad6c9a435cade250ec8c8b6">llvm::MachineOperand::setTargetFlags</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerHWASAN\_CHECK\_MEMACCESS() {#a03f07768097bdb66d5e2b5bd82e629c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerHWASAN_CHECK_MEMACCESS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="#a8176dd790cc6ce20c0854ee8373788d5">HwasanMemaccessSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a41972fe6f3fab862543b7b835a714f9b">llvm::utostr</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerJumpTableDest() {#a164e68b3a2bec7c004e7fe6632611400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerJumpTableDest (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Small jump tables contain an unsigned byte or half, representing the offset from the lowest-addressed possible destination to the desired basic block.</p>


<p>Since all instructions are 4-byte aligned, this is further compressed by counting in instructions rather than bytes (i.e. divided by 4). So, to materialize the correct destination we need:</p>



<pre><code>        adr xDest, .LBB0_0
        ldrb wScratch, [xTable, xEntry]   (with "lsl #1" for ldrh).
        add xDest, xDest, xScratch (with "lsl #2" for smaller entries)
</code></pre>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerKCFI\_CHECK() {#a6a5214da5fedd168431b377870b2eaea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerKCFI_CHECK (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28a756347c46f7abfa1e1fefcc39502c680">llvm::AArch64CC::EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd04b8a497d63d4f11a884ac2ec54f53">llvm::getWRegFromXReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5690bb8ba0b629acff71bb5b4f2e5b4">llvm::getXRegFromWReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerLOADauthptrstatic() {#adaf899f496f2ac717a79e58b4e439058}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerLOADauthptrstatic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a081ab7d53b85dfd7a2f8609689147393">llvm::MachineOperand::CreateMCSymbol</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a0580b05cc0794957d4ac1ce2f209ac87">llvm::AsmPrinter::getObjFileLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46a759ecca259756790f64e470254a4e886">llvm::AArch64PACKey::LAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa1316da87e093c08b6657877572b19a4">llvm::AsmPrinter::MMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a028a4adc46c746ba1501e1e6fefb54cc">llvm::AArch64II::MO_NC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a7f04634c15a04a59d5f234002e613b5b">llvm::AArch64II::MO_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a3a5053185998bdf24f3167c234915785">llvm::AArch64II::MO_PAGEOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerLOADgotAUTH() {#aa50d150829937efa73527accf23a184d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerLOADgotAUTH (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ace845d7da04db4610b2d051c7b44e832">llvm::MachineOperand::addTargetFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa92c1e2c33abf7fb64f544b67f234df6">llvm::AsmPrinter::createTempSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46a4babe0d4b2a36f887f48dfeb4b4a7cc6">llvm::AArch64PACKey::DA</a>, <a href="#ae2871329035b9e43047202b4ee2198fd">emitPtrauthCheckAuthenticatedValue</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a51af265dc931258cdb8ffb37ee6decee">llvm::GlobalValue::hasExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46aaf2ff1a10f3f3b211d7781a33e4c1e05">llvm::AArch64PACKey::IA</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aba930e0564c4207f112d9243eb2fc13a">llvm::Type::isFunctionTy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a028a4adc46c746ba1501e1e6fefb54cc">llvm::AArch64II::MO_NC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a7f04634c15a04a59d5f234002e613b5b">llvm::AArch64II::MO_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a3a5053185998bdf24f3167c234915785">llvm::AArch64II::MO_PAGEOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa686bcdfaefdfe3f49acbfe6f680bc22d">llvm::CodeModel::Tiny</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64pauth/#abf78b4a589091577668be8331dbf3e10ae34527c9d45ac8d5e68634911bfcd36e">llvm::AArch64PAuth::XPAC</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerMOPS() {#ae6002788c3c056672d7af9931f11baf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerMOPS (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerMOVaddrPAC() {#a22c90a0d582e484ad655a9f337002b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerMOVaddrPAC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#a2b9700052102985a61c9cf62b71d68f0">llvm::MCInstBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ace845d7da04db4610b2d051c7b44e832">llvm::MachineOperand::addTargetFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46a4babe0d4b2a36f887f48dfeb4b4a7cc6">llvm::AArch64PACKey::DA</a>, <a href="#ae2871329035b9e43047202b4ee2198fd">emitPtrauthCheckAuthenticatedValue</a>, <a href="#ae260c2b32968b1f83af078cb6a1af74d">emitPtrauthDiscriminator</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcbcb9cd48f8f0399387bfa5c2b6e80d">llvm::getPACOpcodeForKey</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#aeae88f12b667477f90db9b726556b337">llvm::AArch64_AM::getShifterImm</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46aaf2ff1a10f3f3b211d7781a33e4c1e05">llvm::AArch64PACKey::IA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aba930e0564c4207f112d9243eb2fc13a">llvm::Type::isFunctionTy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46a759ecca259756790f64e470254a4e886">llvm::AArch64PACKey::LAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a4144c2ee93286fba09bd8f14fb11f27a">llvm::AArch64II::MO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a028a4adc46c746ba1501e1e6fefb54cc">llvm::AArch64II::MO_NC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a7f04634c15a04a59d5f234002e613b5b">llvm::AArch64II::MO_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a3a5053185998bdf24f3167c234915785">llvm::AArch64II::MO_PAGEOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aa233a8fe996a2045f5b02f5161e145c2">llvm::MachineOperand::setOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad407b071bad6c9a435cade250ec8c8b6">llvm::MachineOperand::setTargetFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64pauth/#abf78b4a589091577668be8331dbf3e10ae34527c9d45ac8d5e68634911bfcd36e">llvm::AArch64PAuth::XPAC</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### lowerOperand() {#ad81b329962e40cb6da3060ad31f0201b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::lowerOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; MCOp)</td>
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

<p>Wrapper for MCInstLowering.lowerOperand() for the tblgen'erated pseudo lowering.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>Referenced by <a href="#a72864dd5479176074c3bbcc3b0e50c22">LowerFAULTING_OP</a>.</p>

</div>
</div>

### LowerPATCHABLE\_EVENT\_CALL() {#ab1c4cab46120a38ac573508e15189f9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerPATCHABLE_EVENT_CALL (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool Typed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac40b688a96b903167e07f7555c2a1e11a624782357b787994e7624c941d945a0b">llvm::AsmPrinter::CUSTOM_EVENT</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a7c868807760d76531432d5a31b6938dc">llvm::AsmPrinter::recordSled</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac40b688a96b903167e07f7555c2a1e11af5f044ed2f1c57504ebd8016581116f4">llvm::AsmPrinter::TYPED_EVENT</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerPATCHABLE\_FUNCTION\_ENTER() {#a6a868e574facfcc4125c0ecac72cfca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerPATCHABLE_FUNCTION_ENTER (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a11dc1e48c7d0e0da77a6d6d377fd391b">llvm::AsmPrinter::emitNops</a>, <a href="#ae02526f6beecce739c07e81ad631eccc">emitSled</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac40b688a96b903167e07f7555c2a1e11ac5a963d0fca7d2453c04dda884ebda0f">llvm::AsmPrinter::FUNCTION_ENTER</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerPATCHABLE\_FUNCTION\_EXIT() {#afaaf077b7bd69dd161b4fa6257f535e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerPATCHABLE_FUNCTION_EXIT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="#ae02526f6beecce739c07e81ad631eccc">emitSled</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac40b688a96b903167e07f7555c2a1e11a9fc24e2ef1ac1d5634e9def062cc94ee">llvm::AsmPrinter::FUNCTION_EXIT</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerPATCHABLE\_TAIL\_CALL() {#ab9856c715cc73b3fc0e951d4cac490b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerPATCHABLE_TAIL_CALL (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="#ae02526f6beecce739c07e81ad631eccc">emitSled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac40b688a96b903167e07f7555c2a1e11a458a4992e96ce2b84b0e0756466ce51f">llvm::AsmPrinter::TAIL_CALL</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerPATCHPOINT() {#af3ec8e57004a88ea5cb892311c3c81ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerPATCHPOINT (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/stackmaps">StackMaps</a> &amp; SM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#ad86c02ad0c56344cf19e482d1924c9f6">llvm::PatchPointOpers::getCallTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a4ecfe362fe15df202b5605e5378eca1b">llvm::PatchPointOpers::getNextScratchIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#aa319bb1da5a106c84bfa9a1fdca084bc">llvm::PatchPointOpers::getNumPatchBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#adfcde4e021a2e59edfa21733753ef8f9">llvm::AsmPrinter::SM</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### lowerPseudoInstExpansion() {#a53106ebeaa731a23f1cfcb2056717726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::lowerPseudoInstExpansion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>tblgen'erated driver function for lowering simple MI-&gt;MC pseudo instructions.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="#a9f2d85b2edc88b7eef2b10f54506ed77">emitAttributes</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerSTACKMAP() {#a727cd7e7e9065ed9ac33e69075c51352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerSTACKMAP (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/stackmaps">StackMaps</a> &amp; SM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/stackmapopers/#a4330cae153bbaadcf79bb4917a6c3924">llvm::StackMapOpers::getNumPatchBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#adfcde4e021a2e59edfa21733753ef8f9">llvm::AsmPrinter::SM</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### LowerSTATEPOINT() {#a010b554002b5c2fdbc6e2d2b64afedb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::LowerSTATEPOINT (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, <a href="/web-llvm/docs/api/classes/llvm/stackmaps">StackMaps</a> &amp; SM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#ad227b3ae621f2b01c29ad057c72348e3">EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a95c1e25f9b75ebe8647c3576add3c8b3">llvm::StatepointOpers::getCallTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a0eeee60ca2931edc9e1f653fbc66373c">llvm::StatepointOpers::getNumPatchBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab313591ae4ea1e3a4ab59121a7dc2a2b">llvm::MachineOperand::getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119">llvm::MachineOperand::MO_ExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">llvm::MachineOperand::MO_GlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">llvm::MachineOperand::MO_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">llvm::MachineOperand::MO_Register</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#adfcde4e021a2e59edfa21733753ef8f9">llvm::AsmPrinter::SM</a>.</p>


<p>Referenced by <a href="#acdf3f4cb6342e67c42191cf29984df97">emitInstruction</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a12edfb6e1007405924bead34e1094488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa06f7388d0cc9b44ece08cdf56c0ecf0">llvm::AsmPrinter::CurrentFnSym</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5b7c6daec7e647061052e0947de4703b">llvm::AsmPrinter::emitFunctionBody</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25e51557ff442df4d50f2ad5d1f55743">llvm::AsmPrinter::emitXRayTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115a8b4296b2d59a622e33b331345fc9507b">llvm::COFF::IMAGE_SYM_CLASS_EXTERNAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115afc617a23fd5e4cce7f2adfc7c2966e1c">llvm::COFF::IMAGE_SYM_CLASS_STATIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120aabbef750c1bc8143f79535ea20699385">llvm::COFF::IMAGE_SYM_DTYPE_FUNCTION</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/globalmergefunctions-h/#a54f7429fa5826ff9909619b76d2bf319a509820290d57f333403f490dde7316f4">Local</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120af01942289377f5c52c8771699eea5144">llvm::COFF::SCT_COMPLEX_TYPE_SHIFT</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5b05d795913638143ef01b80fb151e89">llvm::AsmPrinter::SetupMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitEndOfAsmFile() {#a26852762ffb57a0de3e876717ddd88b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitEndOfAsmFile (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>This virtual method can be overridden by targets that want to emit something at the end of their file.</p>

<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### emitFMov0() {#adaf5a680481887f4e12eb1c05ea88246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitFMov0 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit instruction to set float register to zero.</p>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### emitFunctionBodyEnd() {#a26bf6aaf463af108bd651a016498bdbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitFunctionBodyEnd ()</td>
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

<p>Targets can override this to emit stuff after the last basic block in the function.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### emitGlobalAlias() {#a680fe1527f7ea4896ffc41579daa24cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitGlobalAlias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> &amp; GA)</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### emitLOHs() {#a7901297f47afe0c9011a3fa7b761ea55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitLOHs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the LOHs contained in AArch64FI.</p>

<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### emitMachOIFuncStubBody() {#a63598a46552eebe6c97a73eff19c92eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitMachOIFuncStubBody (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalifunc">GlobalIFunc</a> &amp; GI, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LazyPointer)</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### emitMachOIFuncStubHelperBody() {#a5fc7f7e7dd9a92f9b341769e35ce3342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitMachOIFuncStubHelperBody (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalifunc">GlobalIFunc</a> &amp; GI, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LazyPointer)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### emitMOVK() {#a45cd3ebb211362ac1cb75dc87cd9589a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitMOVK (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dest, uint64_t Imm, unsigned Shift)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### emitMovXReg() {#a4f03b50815725f7303ca0d641bd5dbb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitMovXReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dest, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### emitMOVZ() {#a01219c22198d4bf97bbc80614d725dee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::emitMOVZ (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dest, uint64_t Imm, unsigned Shift)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### GetCPISymbol() {#a46ac137a140e1c486f927c31c832186d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * AArch64AsmPrinter::GetCPISymbol (unsigned CPID)</td>
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

<p>GetCPISymbol - Return the symbol for the specified constant pool entry.</p>

<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### getIFuncMCSubtargetInfo() {#aa4a3b5addb966936642ca3e739821dae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo * anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::getIFuncMCSubtargetInfo ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aebe7e48735a59049062e384e810c108a">getSubtargetInfo()</a> cannot be used where this is needed because we don't have a MachineFunction when we're lowering a GlobalIFunc, and getSubtargetInfo requires one.</p>


<p>Override the implementation in targets that support the Mach-O IFunc lowering.</p>


<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### PrintAsmMemoryOperand() {#a0faaa94ab2b79a3da969d8fdfc277559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64AsmPrinter::PrintAsmMemoryOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ExtraCode, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant as an address.</p>


<p>Targets should override this to format as appropriate. This method can return true if the operand is erroneous.</p>


<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### printAsmMRegister() {#ac5601e468a107add4678c8bf23d6950e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64AsmPrinter::printAsmMRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, char Mode, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### PrintAsmOperand() {#aca8cdd9245e96ea418eadd178f166c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64AsmPrinter::PrintAsmOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ExtraCode, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant.</p>


<p>PrintAsmOperand - Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant.</p>


<p>Targets should override this to format as appropriate. This method can return true if the operand is erroneous.</p>


<p>Targets should override this to format as appropriate for machine specific ExtraCodes or when the arch-independent handling would be too complex otherwise.</p>


<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### printAsmRegInClass() {#a9302fe321e74df05e0581af991980391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64AsmPrinter::printAsmRegInClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned AltName, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### PrintDebugValueComment() {#aa697c21dd83271adbb10146119d72439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::PrintDebugValueComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### printOperand() {#a93136fe8e9c29d279acb9857df3d5e45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::printOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNum, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### recordIfImportCall() {#aa8a05e623abac07886816e57e1d98a4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64AsmPrinter::recordIfImportCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * BranchInst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if this instruction is part of a sequence that is eligle for import call optimization and, if so, records it to be emitted in the import call section.</p>

<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### shouldEmitWeakSwiftAsyncExtendedFramePointerFlags() {#a3e5d3fbea430b05e2ab66e59272dad74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::shouldEmitWeakSwiftAsyncExtendedFramePointerFlags ()</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### HwasanMemaccessSymbols {#a8176dd790cc6ce20c0854ee8373788d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;HwasanMemaccessTuple, MCSymbol *&gt; anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::HwasanMemaccessSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>


<p>Referenced by <a href="#aac53de41a4af1d12db6ce7d5a0cf6678">emitHwasanMemaccessSymbols</a> and <a href="#a03f07768097bdb66d5e2b5bd82e629c3">LowerHWASAN_CHECK_MEMACCESS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AArch64FI {#a16a6b5862f9f83212dd78dad76812bf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64FunctionInfo* anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::AArch64FI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### FM {#a1f63b3c1765d8ba2ef1eb56e18f0b2a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FaultMaps anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::FM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### InstsEmitted {#acbf433a9809bab5a6b55573cdaa4dd5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::InstsEmitted</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### LOHInstToLabel {#adccf68774f4a4d8264875363e3f330b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MInstToMCSymbol anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LOHInstToLabel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### MCInstLowering {#a835553ea49764c8664ed2cb0ec36bae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64MCInstLower anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::MCInstLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### SectionToImportedFunctionCalls {#a033a49f0a3ab777caac2e1853309c661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MCSection *, std::vector&lt;std::pair&lt;MCSymbol *, MCSymbol *&gt; &gt; &gt; anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::SectionToImportedFunctionCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### ShouldEmitWeakSwiftAsyncExtendedFramePointerFlags {#a7e20c2ccf75eb5469cbae6d626f72a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::ShouldEmitWeakSwiftAsyncExtendedFramePointerFlags = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

### STI {#a96558d1445f3b7b5cc612aaf7fc0adf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64Subtarget* anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp">AArch64AsmPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
