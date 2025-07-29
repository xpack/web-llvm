---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `PPCTLSDynamicCall.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppc-h">PPC.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetmachine-h">PPCTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">llvm/CodeGen/LiveIntervals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-ppctlsdynamiccall-cpp-">anonymous{PPCTLSDynamicCall.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall">PPCTLSDynamicCall</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae005d66f0db86d0d82cfce05120c6563">INITIALIZE_PASS_BEGIN</a> (PPCTLSDynamicCall, DEBUG_TYPE, "PowerPC TLS Dynamic Call Fixup", false, false) INITIALIZE_PASS_END(PPCTLSDynamicCall</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030569d5a541b6110f2ae1b6a3413a58">DEBUG_TYPE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PowerPC TLS Dynamic Call</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PowerPC TLS Dynamic Call</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac65a7c2f24a6388f7a72b630b6510c73">false</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"ppc-tls-dynamic-call"</td>
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

### INITIALIZE\_PASS\_BEGIN() {#ae005d66f0db86d0d82cfce05120c6563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (PPCTLSDynamicCall, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "PowerPC TLS Dynamic Call Fixup", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp">PPCTLSDynamicCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DEBUG\_TYPE {#a030569d5a541b6110f2ae1b6a3413a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_TYPE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp">PPCTLSDynamicCall.cpp</a>.</p>

</div>
</div>

### false {#ac65a7c2f24a6388f7a72b630b6510c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PowerPC TLS Dynamic Call false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp">PPCTLSDynamicCall.cpp</a>.</p>

</div>
</div>

### Fixup {#a4a235aedca5bbfc39934045b6cbf9c70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PowerPC TLS Dynamic Call Fixup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp">PPCTLSDynamicCall.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/adjust/#a180e97360df3a3083f13bde03d4ffe46">adjust::adjustBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp/#ae03bfc95ecd6ac86582ade86cd2711f1">adjustFixupValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp/#ab33289282719ea97ec8e54acbee45fbe">adjustFixupValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchasmbackend-cpp/#ab33289282719ea97ec8e54acbee45fbe">adjustFixupValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp/#a419a69e7c102339588b7f4dcebe94387">adjustFixupValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp/#ab33289282719ea97ec8e54acbee45fbe">adjustFixupValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensaasmbackend-cpp/#ab33289282719ea97ec8e54acbee45fbe">adjustFixupValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpuasmbackend-cpp/#a6fd1dc9828f75b52e3927417f8edb0f7">adjustFixupValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#acd2d48bd67d42ac499c2b0acdef4c2c3">llvm::ARMAsmBackend::adjustFixupValue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a78aafef1cfb9e7f16f7cd87ac1f806bc">llvm::AVRAsmBackend::adjustFixupValue</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#ad6888126cb2adb886258b17447e5a205">adjust::adjustRelativeBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/aarch64asmbackend/#a2815f5697eeeba8167e7b5fe3a15646c">anonymous{AArch64AsmBackend.cpp}::AArch64AsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#a979741100c68b692ca83bfcad260bef9">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmbackend-cpp-/bpfasmbackend/#a8042e91ea8d66d25a0e45e9f03465395">anonymous{BPFAsmBackend.cpp}::BPFAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/dxilasmbackend/#a263b9d8d10bb2bbf8c37c7182f6f7f3a">anonymous{DirectXMCTargetDesc.cpp}::DXILAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#acb84e0118cb55bac7f2f1b46ccc6ff3d">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmbackend-cpp-/lanaiasmbackend/#add6d8b6bffc49d914c7c9de795b39abe">anonymous{LanaiAsmBackend.cpp}::LanaiAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmbackend-cpp-/m68kasmbackend/#acf5f133a716098bab81058fd1bcded74">anonymous{M68kAsmBackend.cpp}::M68kAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmbackend-cpp-/msp430asmbackend/#adb0cc224134dc1ac6a8900af03a8f900">anonymous{MSP430AsmBackend.cpp}::MSP430AsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmbackend-cpp-/ppcasmbackend/#ab1ae338b47ff1cd8cbc085953ec2d49f">anonymous{PPCAsmBackend.cpp}::PPCAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmbackend-cpp-/elfsparcasmbackend/#a4dc7dcc1a9c3ad6e859bcc7bec7967f2">anonymous{SparcAsmBackend.cpp}::ELFSparcAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmbackend-cpp-/spirvasmbackend/#a18ab734fe067eac2f40577b170ec8fb4">anonymous{SPIRVAsmBackend.cpp}::SPIRVAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzmcasmbackend-cpp-/systemzmcasmbackend/#a9b897519cd359a1020496070eab065a5">anonymous{SystemZMCAsmBackend.cpp}::SystemZMCAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmbackend-cpp-/elfveasmbackend/#abd041028f7735a1ecef64b4d1a5a7b73">anonymous{VEAsmBackend.cpp}::ELFVEAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmbackend-cpp-/webassemblyasmbackend/#a2bdba3a6a5e7fb575dccda18ca975edd">anonymous{WebAssemblyAsmBackend.cpp}::WebAssemblyAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#ac4f1ecc11d292a77e74ca1043c72c8d2">anonymous{X86AsmBackend.cpp}::X86AsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#a454671b28fb42060da505e5692fccc77">llvm::ARMAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a863fe7b0cd779f309ac493e93c952d37">llvm::AVRAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#a9770a1a9fb4e41322c32fe546c3145d6">llvm::CSKYAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a07f68977860b1721db6a7271f2861555">llvm::LoongArchAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ae38b6e0fdf26adde1fa4ac04e12931f7">llvm::MCAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmbackend/#aa68834049f70b768351aa29223d33a44">llvm::MipsAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a29e40738fcf4d771be936969f54b2d1a">llvm::RISCVAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensamcasmbackend/#a477fb51301414b682fd444cd5d3181b8">llvm::XtensaMCAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aa12378426474ba414b8bc234a26fd19b">canHoistIVInc</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a402cdf1e65b003605c1db8647861c353">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::classifySymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a1b7e117c34782423f4cab2396b42b059">llvm::MCWinCOFFStreamer::emitCOFFImgRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#ab111e0970f34dbb0c62ace14e515819c">llvm::MCWinCOFFStreamer::emitCOFFSecNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a4231cebc046e4dba7b742b6d31bd1d01">llvm::MCWinCOFFStreamer::emitCOFFSecOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a6dbbe16f1a57144b250b2b3ba1243e93">llvm::MCWinCOFFStreamer::emitCOFFSecRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a0cce678ce28a97e39af6a60a52daac7f">llvm::MCWinCOFFStreamer::emitCOFFSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#a4dc19532d6ff14ce17e330c87e60411d">llvm::MCXCOFFStreamer::emitInstToData</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#a74f3eb9157be6847f5bf0f9cd228ad01">llvm::MCXCOFFStreamer::emitXCOFFRefDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#adc24c0346dea71c12facfce5d4d4d4b7">llvm::BTFDebug::endModule</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64authmcexpr/#a3a820802f6d625824fc6adb2daadd8a4">llvm::AArch64AuthMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#a2ee670ab9e4208096e0aff88d1a28034">llvm::AArch64MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac7ea2a3563181056354939fd2ed18e7e">llvm::AMDGPUMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armmcexpr/#a429114323337d426eb531108880e7c34">llvm::ARMMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#af576492babedf4292598955c5adcf76b">llvm::AVRMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcexpr/#a3cee463d58774d5fade0dce5de3b86e6">llvm::CSKYMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcexpr/#a8d38c1312f839e6d789932230e6d420f">llvm::HexagonMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#a29aa1db738708f442d758f92d754d8fe">llvm::LanaiMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#af2cae3779c4cf6161a29b19196c789c5">llvm::LoongArchMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetexpr/#a87e1ec7054ebe06f7eda613e0e6beca5">llvm::MCTargetExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ae6611e2e9cb3a7eea00a5150360c2e98">llvm::MipsMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxfloatmcexpr/#ad367fceda810b824fe3b725bdbb9c4b8">llvm::NVPTXFloatMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxgenericmcsymbolrefexpr/#aaf306792895ee25d314c85a591909f6d">llvm::NVPTXGenericMCSymbolRefExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a14cdd09b5f7fc6f29b081579146a17dd">llvm::PPCMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a99dde8d50bac6a7bb455e6558fa95efa">llvm::RISCVMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#a408cec492b050bec5d09a6780b2fa980">llvm::SparcMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcexpr/#a7065956ed71b1a1beeb5b65081742b49">llvm::SystemZMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a8c7ef1f889fba81bf6d37bbaec0c1c8a">llvm::VEMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86mcexpr/#a7ab4aa50cedd49d2239432c5eadb9021">llvm::X86MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensamcexpr/#a6874f1bf101eb054bfac298fd0bd3f53">llvm::XtensaMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/mccoffsectionnumbertargetexpr/#ac05d89dfeaa6bc46182ef589991840e5">MCCOFFSectionNumberTargetExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/mccoffsectionoffsettargetexpr/#aab68a571e295eed277817386b2234234">MCCOFFSectionOffsetTargetExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ab3a34a70fe72eeb58c98a1e76dae9af4">llvm::MCAsmBackend::evaluateTargetFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcasmbackend-cpp/#a168829419d2b83e6f25315bba6ccd103">extractBitsForFixup</a>, <a href="/web-llvm/docs/api/namespaces/adjust/ldi/#aeeddcc1e750e09610ab189e07a2d5bc8">adjust::ldi::fixup</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a7e640b2e159d95523eb58b80cb80f064">adjust::fixup_13_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a54054e19c3f70129290ae0799251c33f">adjust::fixup_6</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a5791905065ceec04294a3f165a266ed4">adjust::fixup_6_adiw</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a7daa33e05e9d8389d7e8e518eb5c9391">adjust::fixup_7_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a94f440bc48fa8490137415c9d2f80492">adjust::fixup_call</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a50754b5bcafbd04e7ff2e61265d6134b">adjust::fixup_lds_sts_16</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a76b2dfc5fe543286d452c7411d6048ce">adjust::fixup_port5</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a77526d3cac35e63f1f829d28b14fd108">adjust::fixup_port6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchasmbackend-cpp/#ad42ea2f8b22fe8d8c94bf6a668751e37">fixupLeb128</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/aarch64asmbackend/#ad9ec3f9b6dad7f8ef92f4e76e16415cb">anonymous{AArch64AsmBackend.cpp}::AArch64AsmBackend::fixupNeedsRelaxation</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#a7d963ba5c73056f5e63cedabf6b16959">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::fixupNeedsRelaxation</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmbackend-cpp-/m68kasmbackend/#a79cf4966914cf2de146fdd40c02171e7">anonymous{M68kAsmBackend.cpp}::M68kAsmBackend::fixupNeedsRelaxation</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a6e29d4c5ce17dd4e45009a0cfb31931f">anonymous{X86AsmBackend.cpp}::X86AsmBackend::fixupNeedsRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#a2cc579d4500f6930f47bf75146de3ceb">llvm::ARMAsmBackend::fixupNeedsRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#a4ad13795ffc171e5e2cfd4ad867dbab3">llvm::CSKYAsmBackend::fixupNeedsRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a7edeefd618df3232669834a7db552ac3">llvm::MCAsmBackend::fixupNeedsRelaxation</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#aabc01e9899fccd76ffd3a0c7da023fb5">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmbackend-cpp-/msp430asmbackend/#a6f390708a8bc13276757f775e4ffdcdb">anonymous{MSP430AsmBackend.cpp}::MSP430AsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#ae536aee2760cede7e1b8532bf821759e">llvm::CSKYAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a7512181881a347126c56fe3456e74f8f">llvm::MCAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a67f770e0c7076b7fc767f1aee60edcd3">llvm::RISCVAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfobjectwriter-cpp/#aa46e35fd185109152c2cece337dcb1e8">getAccessVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#ad6d3a088c61bdd49d330e0847cc53203">llvm::PPCMCCodeEmitter::getImm34Encoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64elfobjectwriter-cpp-/aarch64elfobjectwriter/#a85d0607dba50e8b55a836f53bc8184ca">anonymous{AArch64ELFObjectWriter.cpp}::AArch64ELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64wincoffobjectwriter-cpp-/aarch64wincoffobjectwriter/#ac4bbe9cdad8b662d3467e8cb63d87b74">anonymous{AArch64WinCOFFObjectWriter.cpp}::AArch64WinCOFFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuelfobjectwriter-cpp-/amdgpuelfobjectwriter/#a043414060262e4212a05425d809505fa">anonymous{AMDGPUELFObjectWriter.cpp}::AMDGPUELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfobjectwriter-cpp-/armelfobjectwriter/#a63161bfeff04b7ed6966d7cba8dfbf47">anonymous{ARMELFObjectWriter.cpp}::ARMELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffobjectwriter-cpp-/armwincoffobjectwriter/#abe849d4183df6b5464a0db9b6a2a8b35">anonymous{ARMWinCOFFObjectWriter.cpp}::ARMWinCOFFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfelfobjectwriter-cpp-/bpfelfobjectwriter/#a6a865396f00972a6e0d0c4f731128e31">anonymous{BPFELFObjectWriter.cpp}::BPFELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyelfobjectwriter-cpp-/cskyelfobjectwriter/#adcfdb6cf22cdaa14533e19d6c71d71a1">anonymous{CSKYELFObjectWriter.cpp}::CSKYELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonelfobjectwriter-cpp-/hexagonelfobjectwriter/#aa78b32c3792c457ebc7638e3d590f63d">anonymous{HexagonELFObjectWriter.cpp}::HexagonELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaielfobjectwriter-cpp-/lanaielfobjectwriter/#a22bd8567d67941a97b5948e2fad50823">anonymous{LanaiELFObjectWriter.cpp}::LanaiELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchelfobjectwriter-cpp-/loongarchelfobjectwriter/#ab173c1990abd5bd3bd9b397cab725eec">anonymous{LoongArchELFObjectWriter.cpp}::LoongArchELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kelfobjectwriter-cpp-/m68kelfobjectwriter/#a8715a150e0f35a58255f4cc042d9ff87">anonymous{M68kELFObjectWriter.cpp}::M68kELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipselfobjectwriter-cpp-/mipselfobjectwriter/#a8ce0a61a47b9839aeb123796d9558fe5">anonymous{MipsELFObjectWriter.cpp}::MipsELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipswincoffobjectwriter-cpp-/mipswincoffobjectwriter/#a632527f1e63c3a9e06ed64fc7e0cd51c">anonymous{MipsWinCOFFObjectWriter.cpp}::MipsWinCOFFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430elfobjectwriter-cpp-/msp430elfobjectwriter/#a7381e62ae0123e1999ecc28e141a5431">anonymous{MSP430ELFObjectWriter.cpp}::MSP430ELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcelfobjectwriter-cpp-/ppcelfobjectwriter/#aae19b9f8e4df7fe44b0ae56d07f88d46">anonymous{PPCELFObjectWriter.cpp}::PPCELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvelfobjectwriter-cpp-/riscvelfobjectwriter/#a292b37d2a3f3fb782daf79fed6123098">anonymous{RISCVELFObjectWriter.cpp}::RISCVELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcelfobjectwriter-cpp-/sparcelfobjectwriter/#a122189d3180d72c2146b9637b59e679b">anonymous{SparcELFObjectWriter.cpp}::SparcELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzelfobjectwriter-cpp-/systemzelfobjectwriter/#ae6894dac4d7b06693f2eedb5432d5b6d">anonymous{SystemZELFObjectWriter.cpp}::SystemZELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-veelfobjectwriter-cpp-/veelfobjectwriter/#a81f6d77fdd397bc5312da8d6ffa4e782">anonymous{VEELFObjectWriter.cpp}::VEELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86elfobjectwriter-cpp-/x86elfobjectwriter/#a4d354a06d39b9d042b7d4e830f688988">anonymous{X86ELFObjectWriter.cpp}::X86ELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincoffobjectwriter-cpp-/x86wincoffobjectwriter/#a0243074481f98b09727ac1f90c1bd7b1">anonymous{X86WinCOFFObjectWriter.cpp}::X86WinCOFFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-xtensaelfobjectwriter-cpp-/xtensaobjectwriter/#a7495dc8aba72084e4e7c900c1426949f">anonymous{XtensaELFObjectWriter.cpp}::XtensaObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/llvm/avrelfobjectwriter/#a6d1153ad58a6a11c307ae506cc3439e1">llvm::AVRELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#a65f5a849898158c5f6fa5831ee0b06e7">llvm::MCELFObjectTargetWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwasmobjecttargetwriter/#af88f8382aca5cf0193e77269052e96bd">llvm::MCWasmObjectTargetWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffobjecttargetwriter/#a98341ab438d64a9e78cdee6ad0bb3e92">llvm::MCWinCOFFObjectTargetWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcxcoffobjectwriter-cpp-/ppcxcoffobjectwriter/#a3dc93394c5603441fbdd9cc42141e792">anonymous{PPCXCOFFObjectWriter.cpp}::PPCXCOFFObjectWriter::getRelocTypeAndSignSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffobjecttargetwriter/#a74f2390c50d0b75537d94b59fcf68b18">llvm::MCXCOFFObjectTargetWriter::getRelocTypeAndSignSize</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#ad8e9bd47b27dc42d0fc9b49ca743ba8d">llvm::LoongArchAsmBackend::handleAddSubRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#aa08889e0000751b3c1d39489bc4eaf48">llvm::MCAsmBackend::handleAddSubRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a9f4b22b2ab12c7d26784790f13aeb273">llvm::RISCVAsmBackend::handleAddSubRelocations</a>, <a href="/web-llvm/docs/api/namespaces/adjust/ldi/#aca951e95d0a0cf12c676f91ef7c31740">adjust::ldi::hh8</a>, <a href="/web-llvm/docs/api/namespaces/adjust/ldi/#a189a46e268c912f577fa2c59e92bb149">adjust::ldi::hi8</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aa847a3eff7b875035d9f887587291940">isAMCompletelyFolded</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a07e234e9b040a89b10635c52640987c9">isAMCompletelyFolded</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64elfobjectwriter-cpp/#af654489f3ea4efd14082ffe899b1ce58">isNonILP32reloc</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a89f3c31cf14a9542b52fd208ce5093ac">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::isSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a4172c40c16e915c478ab94311e76e1a8">llvm::MCAssembler::layout</a>, <a href="/web-llvm/docs/api/namespaces/adjust/ldi/#aaec3d8a144e99bceb790607e542834c0">adjust::ldi::lo8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4b50dba6968ef240c092133600946ef9">LowerMULH</a>, <a href="/web-llvm/docs/api/namespaces/adjust/ldi/#a0ffd933c06c7daefad330577b403516b">adjust::ldi::ms8</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse/#a223ebe6602a0309788a0c3906a683175">anonymous{LoopStrengthReduce.cpp}::LSRUse::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupvectorconstants-cpp-/x86fixupvectorconstantspass/#a82e64653e573981933ea8bdc240fad3c">anonymous{X86FixupVectorConstants.cpp}::X86FixupVectorConstantsPass::processInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/cost/#abd90406531e76ab0007b8cf6ebe8b34d">anonymous{LoopStrengthReduce.cpp}::Cost::RateFormula</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#a2dbae0b9fd70753e65a348ef9eaf1aaf">llvm::ARMAsmBackend::reasonForFixupRelaxation</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64wincoffobjectwriter-cpp-/aarch64wincoffobjectwriter/#a432080a1f772c4079dba8c63432e30d8">anonymous{AArch64WinCOFFObjectWriter.cpp}::AArch64WinCOFFObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#a03347d16edde093da0fc95c0e4a51420">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffobjectwriter-cpp-/armwincoffobjectwriter/#a9144cb4b03f7d3996b85fbffd65b9247">anonymous{ARMWinCOFFObjectWriter.cpp}::ARMWinCOFFObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-goffobjectwriter-cpp-/goffobjectwriter/#ab804e28f2b38ee3b8ff61c1b03f83668">anonymous{GOFFObjectWriter.cpp}::GOFFObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86machobjectwriter-cpp-/x86machobjectwriter/#ae86630c0128bf3d964ca61e862679cca">anonymous{X86MachObjectWriter.cpp}::X86MachObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dxcontainerobjectwriter/#a5d8234cc9e27a3eecc8dc542af36ec15">llvm::DXContainerObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a73aed7794053594cfb9536d55eac30fd">llvm::ELFObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a6dbd1184c383c03fb43f26365d095b50">llvm::MachObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/mcmachobjecttargetwriter/#a43d8b06533488625f599a722d3442b35">llvm::MCMachObjectTargetWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#ac50b0371115af97e5155bd535f285dd7">llvm::MCObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/wincoffobjectwriter/#a25ccd828a9ce444bcfcb33af6b1ffb37">llvm::WinCOFFObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/wincoffwriter/#ae083e4782d3a3ca6e98fbaacbb8d3f8f">llvm::WinCOFFWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a172850f33ba1afc4850ad347040d02a7">llvm::RISCVAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a056a7266fa88806c3f88ab217fac6e4e">llvm::RISCVAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/aarch64asmbackend/#aeef50e019f2d2c28849d27a4df4f3afb">anonymous{AArch64AsmBackend.cpp}::AArch64AsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#a60333ca436b71b31b4b63bb9a470f392">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#ac398fae75ecf58a6927e06f0a6206bf6">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmbackend-cpp-/ppcasmbackend/#a55a288079b1267fdfb06085bcf3f8e34">anonymous{PPCAsmBackend.cpp}::PPCAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmbackend-cpp-/sparcasmbackend/#abaa3a6d5861cbf78f52714b6749874b2">anonymous{SparcAsmBackend.cpp}::SparcAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzmcasmbackend-cpp-/systemzmcasmbackend/#aa875cba7c1a84e93dc83c0832891362e">anonymous{SystemZMCAsmBackend.cpp}::SystemZMCAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmbackend-cpp-/veasmbackend/#afcacac536fc6309b61f5b1a425e7e6ef">anonymous{VEAsmBackend.cpp}::VEAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a7ab0419e0b93d5d9ae6c68b7857b9b72">anonymous{X86AsmBackend.cpp}::X86AsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#a69d646b59f77217c6a669115f4a30283">llvm::ARMAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#acaeae6c0754ca9264b9ad0bb5c4f5916">llvm::AVRAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#a9b8d2ec2c857eeaca14a0ef9376e7403">llvm::CSKYAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a2c78f0030b21fa3d13dc0cca7433d9d9">llvm::LoongArchAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a5adf8255bfcc9dc609a86ad7fc8b4b11">llvm::MCAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmbackend/#a60e28438af4a885993c78ad8b77a4f40">llvm::MipsAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a6a95c754e0453aefe81ebad98e4ff895">llvm::RISCVAsmBackend::shouldForceRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a36a4b135a95576724f4b520be6063ef1">llvm::LoongArchAsmBackend::shouldInsertFixupForCodeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a9f78db3a67945349cd7bcee045f65b1b">llvm::RISCVAsmBackend::shouldInsertFixupForCodeAlign</a>, <a href="/web-llvm/docs/api/namespaces/adjust/#a06a2da2b39e1834223e10c3d33ade866">adjust::unsigned_width</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64elfobjectwriter-cpp-/aarch64elfobjectwriter/#a08f97f63455a07245e3ab6f6fb70ba4b">anonymous{AArch64ELFObjectWriter.cpp}::AArch64ELFObjectWriter::~AArch64ELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64wincoffobjectwriter-cpp-/aarch64wincoffobjectwriter/#a1ea9da5e7c4b94572f69b7dfd74cb64f">anonymous{AArch64WinCOFFObjectWriter.cpp}::AArch64WinCOFFObjectWriter::~AArch64WinCOFFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfobjectwriter-cpp-/armelfobjectwriter/#a7d4429fdde165ce38291fea133e6d67d">anonymous{ARMELFObjectWriter.cpp}::ARMELFObjectWriter::~ARMELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-armwincoffobjectwriter-cpp-/armwincoffobjectwriter/#ae260158901d71c97b28071295ce757c9">anonymous{ARMWinCOFFObjectWriter.cpp}::ARMWinCOFFObjectWriter::~ARMWinCOFFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrelfobjectwriter/#ab77bbaa6fcb1680e6880efbafac01bd7">llvm::AVRELFObjectWriter::~AVRELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmbackend-cpp-/bpfasmbackend/#aabfb60b52e7e4a345801a1016407863c">anonymous{BPFAsmBackend.cpp}::BPFAsmBackend::~BPFAsmBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfelfobjectwriter-cpp-/bpfelfobjectwriter/#a2127725016f07552a00003422d01f29a">anonymous{BPFELFObjectWriter.cpp}::BPFELFObjectWriter::~BPFELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaielfobjectwriter-cpp-/lanaielfobjectwriter/#a116edf514cc410b70943eff3793c9052">anonymous{LanaiELFObjectWriter.cpp}::LanaiELFObjectWriter::~LanaiELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipselfobjectwriter-cpp-/mipselfobjectwriter/#a9d7113ad912833e0fadec1ec516e6854">anonymous{MipsELFObjectWriter.cpp}::MipsELFObjectWriter::~MipsELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmbackend-cpp-/msp430asmbackend/#aed8112797259448babef0271b5abc478">anonymous{MSP430AsmBackend.cpp}::MSP430AsmBackend::~MSP430AsmBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a8717bb6e777f0b049dfe139e8719eabf">llvm::PPCMCCodeEmitter::~PPCMCCodeEmitter</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcelfobjectwriter-cpp-/sparcelfobjectwriter/#a1713ce57e1fe3c7c6fec72a9901e6eb2">anonymous{SparcELFObjectWriter.cpp}::SparcELFObjectWriter::~SparcELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzelfobjectwriter-cpp-/systemzelfobjectwriter/#a65239f0b68c37be6443d8a3fa8ab2afa">anonymous{SystemZELFObjectWriter.cpp}::SystemZELFObjectWriter::~SystemZELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-veelfobjectwriter-cpp-/veelfobjectwriter/#ada316bc5de740b209894e1fae6e0fad7">anonymous{VEELFObjectWriter.cpp}::VEELFObjectWriter::~VEELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86elfobjectwriter-cpp-/x86elfobjectwriter/#a34bc80c705072df0215d71249ed04821">anonymous{X86ELFObjectWriter.cpp}::X86ELFObjectWriter::~X86ELFObjectWriter</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86wincoffobjectwriter-cpp-/x86wincoffobjectwriter/#a0003f12de600b11fab37ffb75678c0b8">anonymous{X86WinCOFFObjectWriter.cpp}::X86WinCOFFObjectWriter::~X86WinCOFFObjectWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"ppc-tls-dynamic-call"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp">PPCTLSDynamicCall.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
