---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DXContainerGlobals.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-h">DXILShaderFlags.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directx-h">DirectX.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">llvm/Analysis/DXILMetadataAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">llvm/Analysis/DXILResource.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">llvm/BinaryFormat/DXContainer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">llvm/MC/DXContainerPSVInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">llvm/Support/MD5.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/moduleutils-h">llvm/Transforms/Utils/ModuleUtils.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-dxcontainerglobals-cpp-">anonymous{DXContainerGlobals.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dxcontainerglobals-cpp-/dxcontainerglobals">DXContainerGlobals</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68619ff4a2bbf3f93a52743885e179ad">INITIALIZE_PASS_BEGIN</a> (DXContainerGlobals, "dxil-globals", "DXContainer Global Emitter", false, true) INITIALIZE_PASS_END(DXContainerGlobals</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">dxil</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9918659ef4a022d158646784619514">globals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">dxil DXContainer Global</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">dxil DXContainer Global</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a25b87844c190bda8bf07383a050395">false</a></td>
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

### INITIALIZE\_PASS\_BEGIN() {#a68619ff4a2bbf3f93a52743885e179ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (DXContainerGlobals, "dxil-globals", "DXContainer Global Emitter", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp">DXContainerGlobals.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Emitter {#a4e37c99d7f846fd82966c68def83c4fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil DXContainer Global Emitter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp">DXContainerGlobals.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64elfstreamer-cpp-/aarch64elfstreamer/#ab3c1d7ab672f0bd15bc00752eb7f8c4d">anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::AArch64ELFStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuelfstreamer-cpp-/amdgpuelfstreamer/#ae424ddf5a356a760902d2b4ad18e7313">anonymous{AMDGPUELFStreamer.cpp}::AMDGPUELFStreamer::AMDGPUELFStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a039b5e6ab81cb5875ca14bf9359570d2">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::ARMELFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcelfstreamer/#a7acfee4eb44a2df6d470ca678f63720e">llvm::AVRMCELFStreamer::AVRMCELFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcelfstreamer/#acc13c8ce908a4c94fd2d819e0a8d51f2">llvm::AVRMCELFStreamer::AVRMCELFStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addbc7c1650a854f77cc27eeb437a179f">llvm::createAArch64ELFStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a437d6950335e06fd6f5bf90cf2d9ec5e">llvm::createAArch64WinCOFFStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95933b754570640373fbbe2ce90f0061">llvm::createAMDGPUELFStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a15dcc6a38741063acd0487d992b468f6">llvm::createARMELFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a380e0347f04ded0876cd8c8575636537">createARMMachOStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeec163f86d0b3e3b850e1841e886a92e">llvm::createARMWinCOFFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmctargetdesc-cpp/#a00329e0996613e36d0aad1d60617a92e">createBPFMCStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a95bcc6e56c597fcd3c634ff9d24c0326">createELFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a95bcc6e56c597fcd3c634ff9d24c0326">createELFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#a13f0ae6d8c2cdbbd9efd0f0dc65a38d8">createELFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#a83eb4dab1000a452d338fbfc218b2277">createMachOStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a2e145aae51e0dbfdc45799f2b81d314c">llvm::Target::createMCObjectStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a7c1c0e56c4d13dab0c027120fadcafe7">llvm::Target::createMCObjectStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#a4108c77c9b7670161fa060ebad07e167">createMCStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-cpp/#a4108c77c9b7670161fa060ebad07e167">createMCStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaimctargetdesc-cpp/#a4108c77c9b7670161fa060ebad07e167">createMCStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a4108c77c9b7670161fa060ebad07e167">createMCStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a5487e8e0178ee833202fada9a613f78b">createMCStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14ae33e5816dd180d6ee5fc94d881306">llvm::createMipsELFStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab37facf9804c17bbda0f72150ba14e54">llvm::createMipsNaClELFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#af537b04469a47e3f8b28aa192f69c4c9">createPPCELFStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac864eaef71f8fa49cc3ee232b0cb0269">llvm::createPPCELFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#ae26be93079075d3e9683304182977614">createPPCXCOFFStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6a487cd63c92b1878cfaace1eccc98a4">llvm::createPPCXCOFFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#a366acce4681d4f1c2c8d331917392146">createWinCOFFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyelfstreamer/#a35d8710afe05956cd2a18d831ab0c078">llvm::CSKYELFStreamer::CSKYELFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a7c3ab4bc92e5a22d3ab1a70e63e04251">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitAppleAcceleratorSections</a>, <a href="/web-llvm/docs/api/groups/methods/#ga4353067d272bae6ec1a934e5ea39f924">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a267b3ad88431cb638221b36a45f7600f">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitDWARFv5DebugNamesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcelfstreamer/#abd418120b6155f0727d4bbf2dfeafe97">llvm::PPCELFStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcxcoffstreamer/#a8c2e9fc7b5dc34b2dc99e6b7216d7ec2">llvm::PPCXCOFFStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledaglinearize/#a16c498db76eb73d37731b36c18879ee4">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGLinearize::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a9436bfa1d0740af8c93bcb8bda0d1d44">llvm::HexagonMCELFStreamer::HexagonMCELFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#abf4c03302466c28c8a1cdd267060cad5">llvm::HexagonMCELFStreamer::HexagonMCELFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdxcontainerstreamer/#a7d4f70a9ddbcb2a69b46fbf2fd24240a">llvm::MCDXContainerStreamer::MCDXContainerStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#aec09c5b9322b90f034d51bd3c0903563">llvm::MCELFStreamer::MCELFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgoffstreamer/#ad8a08d827421a34ca4a21fbc081ce677">llvm::MCGOFFStreamer::MCGOFFStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a9bd111c579cbfedf31833c63a942e56d">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::MCMachOStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ad1da683a018add519fd96cd22cc785">llvm::MCObjectStreamer::MCObjectStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcspirvstreamer/#ac47a9def31efa66a4e5a4d3040d6920c">llvm::MCSPIRVStreamer::MCSPIRVStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwasmstreamer/#a1d6cd7e8cf02e3cbbe6cdfd67c35287b">llvm::MCWasmStreamer::MCWasmStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#a7b7d35e652afcfe9d01785d07682c93b">llvm::MCXCOFFStreamer::MCXCOFFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a89436f547bd435b64736fc0ec57c04f6">llvm::MipsELFStreamer::MipsELFStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsnaclelfstreamer-cpp-/mipsnaclelfstreamer/#afaf18fc563bb9ebd904c10213aa8789d">anonymous{MipsNaClELFStreamer.cpp}::MipsNaClELFStreamer::MipsNaClELFStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a2fab033607162e6ab1a1d6fb7ed5e07b">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionEncoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#aec5e1563ca339dbf7905cf069c364e39">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a112639954fd036a8748791f74d0db6fb">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcelfstreamer/#ac558199bf4ba000421543f08b7adf8f0">llvm::PPCELFStreamer::PPCELFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcxcoffstreamer/#a6327661699bd482538dcf1a0ffd6af0f">llvm::PPCXCOFFStreamer::PPCXCOFFStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#aab3e2639c5eed5d618705678090fa23f">ProcessSDDbgValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a10d5495926e5659dbcefde78541b29a8">ProcessSourceNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#ab3c001f01a280aefade681724cc88f7f">llvm::dwarf_linker::classic::DWARFLinker::setOutputDWARFEmitter</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86elfstreamer/#a253791543bb716b279f4b8fa475a5df5">anonymous{X86AsmBackend.cpp}::X86ELFStreamer::X86ELFStreamer</a>.</p>

</div>
</div>

### false {#a5a25b87844c190bda8bf07383a050395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil DXContainer Global false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp">DXContainerGlobals.cpp</a>.</p>

</div>
</div>

### globals {#ace9918659ef4a022d158646784619514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil globals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp">DXContainerGlobals.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
