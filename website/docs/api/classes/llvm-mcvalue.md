---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCValue` Class Reference

<p>This represents an "assembler immediate". <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeb0d3729924a0325f79f5f33c634a5b">MCValue</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a435bfff1f2697dbccd406b2e03112443">getConstant</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced07a0d8eb8031ff0c2a6d691277667">getSymA</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e7a76b67d50b7136eabb2599982ae41">getSymB</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48eebfa5f9f069075bc6412fd4371c7b">getRefKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a96a0245ea7da2779a023ab07829e4">isAbsolute</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this an absolute (as opposed to relocatable) value. <a href="#af9a96a0245ea7da2779a023ab07829e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b46e1e94efb7cad1dd48d20f68f177">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the value to the stream <span class="doxyComputerOutput">OS</span>. <a href="#af3b46e1e94efb7cad1dd48d20f68f177">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac16bc08d78240466f90fbc5641efdcec">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the value to stderr. <a href="#ac16bc08d78240466f90fbc5641efdcec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985">MCSymbolRefExpr::VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dc0553c3db26d1d6f95c9da133fbe15">getAccessVariant</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa147a7d1185cfab3117be49d8b80a2f4">SymA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9e37c3b88e7097a844289e31a75373e">SymB</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4153653525d310528e539b68c9a0c7f">Cst</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da9a506f99b3145ed5e80ed6b58f11f">RefKind</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9749211eb432ffc5b2bbef35eed9e429">get</a> (const MCSymbolRefExpr *SymA, const MCSymbolRefExpr *SymB=nullptr, int64_t Val=0, uint32_t RefKind=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac84f459c3c4f0957bf2f128680bf630b">get</a> (int64_t Val)</td>
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

<p>This represents an "assembler immediate".</p>


<p>In its most general form, this can hold ":Kind:(SymbolA - SymbolB +
 imm64)". Not all targets supports relocations of this general form, but we need to represent this anyway.</p>


<p>In general both SymbolA and SymbolB will also have a modifier analogous to the top-level Kind. Current targets are not expected to make use of both though. The choice comes down to whether relocation modifiers apply to the closest symbol or the whole expression.</p>


<p>Note that this class must remain a simple POD value class, because we need it to live in unions etc.</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCValue() {#aeeb0d3729924a0325f79f5f33c634a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCValue::MCValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>


<p>Referenced by <a href="#a9749211eb432ffc5b2bbef35eed9e429">get</a> and <a href="#ac84f459c3c4f0957bf2f128680bf630b">get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#ac16bc08d78240466f90fbc5641efdcec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MCValue::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the value to stderr.</p>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcvalue-cpp">MCValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#af3b46e1e94efb7cad1dd48d20f68f177">print</a>.</p>

</div>
</div>

### getAccessVariant() {#a4dc0553c3db26d1d6f95c9da133fbe15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolRefExpr::VariantKind MCValue::getAccessVariant ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcvalue-cpp">MCValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aced07a0d8eb8031ff0c2a6d691277667">getSymA</a>, <a href="#a9e7a76b67d50b7136eabb2599982ae41">getSymB</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>

</div>
</div>

### getConstant() {#a435bfff1f2697dbccd406b2e03112443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MCValue::getConstant ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a714bb267b4fc2935142836b944e9bef8">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::classifySymbolRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a34ce30f596de6334b5f17323b15e4fa4">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a8dfc15625ed04fb03d221eaebf38fd56">llvm::MCObjectStreamer::emitRelocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a3a820802f6d625824fc6adb2daadd8a4">llvm::AArch64AuthMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#a2ee670ab9e4208096e0aff88d1a28034">llvm::AArch64MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac7ea2a3563181056354939fd2ed18e7e">llvm::AMDGPUMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#a29aa1db738708f442d758f92d754d8fe">llvm::LanaiMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#af2cae3779c4cf6161a29b19196c789c5">llvm::LoongArchMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ae6611e2e9cb3a7eea00a5150360c2e98">llvm::MipsMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a99dde8d50bac6a7bb455e6558fa95efa">llvm::RISCVMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcexpr/#a7065956ed71b1a1beeb5b65081742b49">llvm::SystemZMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a8c7ef1f889fba81bf6d37bbaec0c1c8a">llvm::VEMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-elftargetobjectfile/#ab479db6c0dce9d07c70ea70016ed99ff">llvm::AArch64_ELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#aab2cc2813c5a774bb4f83b6f9ae5a98b">llvm::AArch64_MachoTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#a62d13f21f5dde00137a248d95cf8acd6">llvm::ARMElfTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#affc824acbbe220a54656c5519b408c4b">llvm::RISCVELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64elftargetobjectfile/#a7fade16e9dc1ebc9b6974b12857f5abe">llvm::X86_64ELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64machotargetobjectfile/#abe4296cf38fa7bebb355865172c0acac">llvm::X86_64MachoTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#ac26abdfac1cfc54efe4ffa6f5ca8bd17">getOffsetAndDataFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a5fe1d9854fec640792f7f305f75002f3">handleIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsasmparser/#a1d5112681065033b21957cce5c39a006">anonymous{MipsAsmParser.cpp}::MipsAsmParser::isJalrRelocAvailable</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a60819faf5feac719be273b62d3231aae">anonymous{MipsAsmParser.cpp}::MipsOperand::isMemWithPtrSizeOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a7db5e2ad04fd4996780652207e5ae06a">anonymous{MipsAsmParser.cpp}::MipsOperand::isMemWithSimmOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a0aa2ecd5566b1a6c5eecaf51a464291e">anonymous{MipsAsmParser.cpp}::MipsOperand::isScaledSImm</a> and <a href="#af3b46e1e94efb7cad1dd48d20f68f177">print</a>.</p>

</div>
</div>

### getRefKind() {#a48eebfa5f9f069075bc6412fd4371c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCValue::getRefKind ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a402cdf1e65b003605c1db8647861c353">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::classifySymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ae6611e2e9cb3a7eea00a5150360c2e98">llvm::MipsMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a89f3c31cf14a9542b52fd208ce5093ac">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::isSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64elfobjectwriter-cpp-/aarch64elfobjectwriter/#ab26b820ccb3610a404a7a77cf1816ea3">anonymous{AArch64ELFObjectWriter.cpp}::AArch64ELFObjectWriter::needsRelocateWithSymbol</a> and <a href="#af3b46e1e94efb7cad1dd48d20f68f177">print</a>.</p>

</div>
</div>

### getSymA() {#aced07a0d8eb8031ff0c2a6d691277667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbolRefExpr * llvm::MCValue::getSymA ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a714bb267b4fc2935142836b944e9bef8">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::classifySymbolRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a34ce30f596de6334b5f17323b15e4fa4">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a8dfc15625ed04fb03d221eaebf38fd56">llvm::MCObjectStreamer::emitRelocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a3a820802f6d625824fc6adb2daadd8a4">llvm::AArch64AuthMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#a2ee670ab9e4208096e0aff88d1a28034">llvm::AArch64MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a3cee463d58774d5fade0dce5de3b86e6">llvm::CSKYMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#a29aa1db738708f442d758f92d754d8fe">llvm::LanaiMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#af2cae3779c4cf6161a29b19196c789c5">llvm::LoongArchMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ae6611e2e9cb3a7eea00a5150360c2e98">llvm::MipsMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a99dde8d50bac6a7bb455e6558fa95efa">llvm::RISCVMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcexpr/#a7065956ed71b1a1beeb5b65081742b49">llvm::SystemZMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a8c7ef1f889fba81bf6d37bbaec0c1c8a">llvm::VEMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a>, <a href="#a4dc0553c3db26d1d6f95c9da133fbe15">getAccessVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#ac26abdfac1cfc54efe4ffa6f5ca8bd17">getOffsetAndDataFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a4b6a90d8388aab90babe76b13765ddf6">llvm::RISCVMCExpr::getPCRelHiFixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a5fe1d9854fec640792f7f305f75002f3">handleIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a89f3c31cf14a9542b52fd208ce5093ac">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::isSymbolDiff</a>, <a href="#af3b46e1e94efb7cad1dd48d20f68f177">print</a> and <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a3f3abd737c618cd14f32c74a1ac03ef1">llvm::ELFObjectWriter::shouldRelocateWithSymbol</a>.</p>

</div>
</div>

### getSymB() {#a9e7a76b67d50b7136eabb2599982ae41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbolRefExpr * llvm::MCValue::getSymB ()</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a714bb267b4fc2935142836b944e9bef8">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::classifySymbolRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a34ce30f596de6334b5f17323b15e4fa4">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a8dfc15625ed04fb03d221eaebf38fd56">llvm::MCObjectStreamer::emitRelocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a3a820802f6d625824fc6adb2daadd8a4">llvm::AArch64AuthMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#a2ee670ab9e4208096e0aff88d1a28034">llvm::AArch64MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a3cee463d58774d5fade0dce5de3b86e6">llvm::CSKYMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#a29aa1db738708f442d758f92d754d8fe">llvm::LanaiMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#af2cae3779c4cf6161a29b19196c789c5">llvm::LoongArchMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ae6611e2e9cb3a7eea00a5150360c2e98">llvm::MipsMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a99dde8d50bac6a7bb455e6558fa95efa">llvm::RISCVMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcexpr/#a7065956ed71b1a1beeb5b65081742b49">llvm::SystemZMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a8c7ef1f889fba81bf6d37bbaec0c1c8a">llvm::VEMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a>, <a href="#a4dc0553c3db26d1d6f95c9da133fbe15">getAccessVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#ac26abdfac1cfc54efe4ffa6f5ca8bd17">getOffsetAndDataFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a5fe1d9854fec640792f7f305f75002f3">handleIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsasmparser/#a1d5112681065033b21957cce5c39a006">anonymous{MipsAsmParser.cpp}::MipsAsmParser::isJalrRelocAvailable</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a89f3c31cf14a9542b52fd208ce5093ac">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::isSymbolDiff</a> and <a href="#af3b46e1e94efb7cad1dd48d20f68f177">print</a>.</p>

</div>
</div>

### isAbsolute() {#af9a96a0245ea7da2779a023ab07829e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCValue::isAbsolute ()</td>
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

<p>Is this an absolute (as opposed to relocatable) value.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/delayedmcexprs/#a463e5963bd9b6fdcbb33e4fd003d2863">llvm::DelayedMCExprs::assignDocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a8dfc15625ed04fb03d221eaebf38fd56">llvm::MCObjectStreamer::emitRelocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac7ea2a3563181056354939fd2ed18e7e">llvm::AMDGPUMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ae6611e2e9cb3a7eea00a5150360c2e98">llvm::MipsMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#ac26abdfac1cfc54efe4ffa6f5ca8bd17">getOffsetAndDataFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a5fe1d9854fec640792f7f305f75002f3">handleIndirectSymViaGOTPCRel</a>, <a href="#af3b46e1e94efb7cad1dd48d20f68f177">print</a> and <a href="/web-llvm/docs/api/classes/llvm/delayedmcexprs/#afde1d15893de3e2295907d9d88911f08">llvm::DelayedMCExprs::resolveDelayedExpressions</a>.</p>

</div>
</div>

### print() {#af3b46e1e94efb7cad1dd48d20f68f177}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCValue::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the value to the stream <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcvalue-cpp">MCValue.cpp</a>.</p>


<p>References <a href="#a435bfff1f2697dbccd406b2e03112443">getConstant</a>, <a href="#a48eebfa5f9f069075bc6412fd4371c7b">getRefKind</a>, <a href="#aced07a0d8eb8031ff0c2a6d691277667">getSymA</a>, <a href="#a9e7a76b67d50b7136eabb2599982ae41">getSymB</a> and <a href="#af9a96a0245ea7da2779a023ab07829e4">isAbsolute</a>.</p>


<p>Referenced by <a href="#ac16bc08d78240466f90fbc5641efdcec">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Cst {#af4153653525d310528e539b68c9a0c7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MCValue::Cst = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>

</div>
</div>

### RefKind {#a9da9a506f99b3145ed5e80ed6b58f11f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCValue::RefKind = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>

</div>
</div>

### SymA {#aa147a7d1185cfab3117be49d8b80a2f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbolRefExpr* llvm::MCValue::SymA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>

</div>
</div>

### SymB {#ad9e37c3b88e7097a844289e31a75373e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbolRefExpr * llvm::MCValue::SymB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a9749211eb432ffc5b2bbef35eed9e429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCValue llvm::MCValue::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * SymA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * SymB=nullptr, int64_t Val=0, uint32_t RefKind=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>


<p>Reference <a href="#aeeb0d3729924a0325f79f5f33c634a5b">MCValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a3a820802f6d625824fc6adb2daadd8a4">llvm::AArch64AuthMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#a2ee670ab9e4208096e0aff88d1a28034">llvm::AArch64MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac7ea2a3563181056354939fd2ed18e7e">llvm::AMDGPUMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#af576492babedf4292598955c5adcf76b">llvm::AVRMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#a29aa1db738708f442d758f92d754d8fe">llvm::LanaiMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#af2cae3779c4cf6161a29b19196c789c5">llvm::LoongArchMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ae6611e2e9cb3a7eea00a5150360c2e98">llvm::MipsMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a14cdd09b5f7fc6f29b081579146a17dd">llvm::PPCMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a99dde8d50bac6a7bb455e6558fa95efa">llvm::RISCVMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcexpr/#a7065956ed71b1a1beeb5b65081742b49">llvm::SystemZMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a8c7ef1f889fba81bf6d37bbaec0c1c8a">llvm::VEMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/mccoffsectionnumbertargetexpr/#ac05d89dfeaa6bc46182ef589991840e5">MCCOFFSectionNumberTargetExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/mccoffsectionoffsettargetexpr/#aab68a571e295eed277817386b2234234">MCCOFFSectionOffsetTargetExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#afa1844c524c0ee91d2cca0f3eac95382">evaluateSymbolicAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#ad8e9bd47b27dc42d0fc9b49ca743ba8d">llvm::LoongArchAsmBackend::handleAddSubRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a9f4b22b2ab12c7d26784790f13aeb273">llvm::RISCVAsmBackend::handleAddSubRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a36a4b135a95576724f4b520be6063ef1">llvm::LoongArchAsmBackend::shouldInsertFixupForCodeAlign</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a9f78db3a67945349cd7bcee045f65b1b">llvm::RISCVAsmBackend::shouldInsertFixupForCodeAlign</a>.</p>

</div>
</div>

### get() {#ac84f459c3c4f0957bf2f128680bf630b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCValue llvm::MCValue::get (int64_t Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a>.</p>


<p>Reference <a href="#aeeb0d3729924a0325f79f5f33c634a5b">MCValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">MCValue.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcvalue-cpp">MCValue.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
