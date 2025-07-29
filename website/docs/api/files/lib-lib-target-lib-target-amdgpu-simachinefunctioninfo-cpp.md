---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `SIMachineFunctionInfo.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusubtarget-h">AMDGPUSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-h">MCTargetDesc/AMDGPUMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">Utils/AMDGPUBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">llvm/CodeGen/LiveIntervals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">llvm/CodeGen/MIRParser/MIParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/callingconv-h">llvm/IR/CallingConv.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include &lt;cassert&gt;
#include &lt;optional&gt;
#include &lt;vector&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#aaea1918f0ff993b3ccae04f1355b088d">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine">GCNTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c3673d61ea1313b5546587d80bdbe83">getTM</a> (const GCNSubtarget *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">yaml::StringValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac18edb1d91090c7614b8fcd4dc45d532">regToString</a> (Register Reg, const TargetRegisterInfo &amp;TRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo">yaml::SIArgumentInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc60d756c70f47b2a9a048c5b4cefa5">convertArgumentInfo</a> (const AMDGPUFunctionArgInfo &amp;ArgInfo, const TargetRegisterInfo &amp;TRI)</td>
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

## Enumerations

### anonymous enum  {#aaea1918f0ff993b3ccae04f1355b088d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">MAX_LANES<a id="aaea1918f0ff993b3ccae04f1355b088da3f15a7385f4533e7ade8b8100afbb8e2"></a></td>
<td class="doxyEnumItemDescription"> (= 64)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp">SIMachineFunctionInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### convertArgumentInfo() {#a7bc60d756c70f47b2a9a048c5b4cefa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; yaml::SIArgumentInfo &gt; convertArgumentInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo">AMDGPUFunctionArgInfo</a> &amp; ArgInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
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



<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp">SIMachineFunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargument/#ad8ac06219747f8ed558a3d748f604a9a">llvm::yaml::SIArgument::createArgument</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a5d66404dbaa77294b81fb71ab6e9f2fa">llvm::yaml::SIArgumentInfo::DispatchID</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a51a96ea8e2bce5933cefe7036c1bbfb8">llvm::yaml::SIArgumentInfo::DispatchPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a4af476884b5c20aff875bfd795311a82">llvm::yaml::SIArgumentInfo::FlatScratchInit</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a73c408dbdc8c66c16cf4470ed757dc0d">llvm::yaml::SIArgumentInfo::ImplicitArgPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a9e9e627cbc58f005c9700fad6dba44c8">llvm::yaml::SIArgumentInfo::ImplicitBufferPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#ad8363f7760da238bb3cfdfac8c6c4b1e">llvm::yaml::SIArgumentInfo::KernargSegmentPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a98bcda097f96f762a3434c7af027a28f">llvm::yaml::SIArgumentInfo::LDSKernelId</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargument/#a61a423bbf703639b5544f79020749b97">llvm::yaml::SIArgument::Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#ae4215850b2039396d9d74fbff0338c73">llvm::yaml::SIArgumentInfo::PrivateSegmentBuffer</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#ae416904af24a6e327a9753d56fe823df">llvm::yaml::SIArgumentInfo::PrivateSegmentSize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a15a48fa21d3f8f742377af427cf0ee5b">llvm::yaml::SIArgumentInfo::PrivateSegmentWaveByteOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a803d6f6f03b46f9c067d597646038fe2">llvm::yaml::SIArgumentInfo::QueuePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargument/#a98359a94cdeab1caf05848042302ecfc">llvm::yaml::SIArgument::RegisterName</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargument/#a5612812addaf08457c9dd5f13497f7da">llvm::yaml::SIArgument::StackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue/#a7b5941aef995e9272fb38c7b69fbb6e4">llvm::yaml::StringValue::Value</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a6970047063845d652bfefd629aa9fcd7">llvm::yaml::SIArgumentInfo::WorkGroupIDX</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a307994d74df71358c89e0cfde00bbfa6">llvm::yaml::SIArgumentInfo::WorkGroupIDY</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#af6104f43042e18823465bd004224f4c0">llvm::yaml::SIArgumentInfo::WorkGroupIDZ</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a88cb82a772743739bbd017585a6f1a73">llvm::yaml::SIArgumentInfo::WorkGroupInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#ad4a62c3bd12c696f954f911be1203a20">llvm::yaml::SIArgumentInfo::WorkItemIDX</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#a5ee4ff91ef2a74105cd4d7ae4a241f9b">llvm::yaml::SIArgumentInfo::WorkItemIDY</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo/#ae10fad23e7a89515721e9dd05fd398df">llvm::yaml::SIArgumentInfo::WorkItemIDZ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a80f6630b845109786f0840f4b15737f9">llvm::yaml::SIMachineFunctionInfo::SIMachineFunctionInfo</a>.</p>

</div>
</div>

### getTM() {#a6c3673d61ea1313b5546587d80bdbe83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNTargetMachine &amp; getTM (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp">SIMachineFunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a7d34f15ff5049d93e832e39c3693b29f">llvm::GCNSubtarget::getTargetLowering</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-nvptxtargetmachine-cpp-/nvptxpassconfig/#a579752615e6d1eb6de1d78a9c96f984e">anonymous{NVPTXTargetMachine.cpp}::NVPTXPassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ade45842956ab309874aa98e6b65932ff">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::getAArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-arctargetmachine-cpp-/arcpassconfig/#abfbcc34c2343af8291863ab518a35ea2">anonymous{ARCTargetMachine.cpp}::ARCPassConfig::getARCTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-armtargetmachine-cpp-/armpassconfig/#a7fb7e7d09ed76f9395fcac65a100175a">anonymous{ARMTargetMachine.cpp}::ARMPassConfig::getARMTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-avrtargetmachine-cpp-/avrpassconfig/#a92b46ca8b670bd88994b22d5fa7ce6cc">llvm::anonymous{AVRTargetMachine.cpp}::AVRPassConfig::getAVRTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpftargetmachine-cpp-/bpfpassconfig/#a0687dda755a5a66fcf89770fe0d64c10">anonymous{BPFTargetMachine.cpp}::BPFPassConfig::getBPFTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskytargetmachine-cpp-/cskypassconfig/#a365facfc015ea2b4f8064f8f85913ff0">anonymous{CSKYTargetMachine.cpp}::CSKYPassConfig::getCSKYTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#ac2231566b709be60b56bf00c6b29a4b8">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::getGCNTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a22ac6eaa6cd0f2a0007defff436c81e1">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::getHexagonTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaitargetmachine-cpp-/lanaipassconfig/#a045b8778f398392425e1a588078e2baf">anonymous{LanaiTargetMachine.cpp}::LanaiPassConfig::getLanaiTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchtargetmachine-cpp-/loongarchpassconfig/#af156183b49978f1e6942b26ca93b3840">anonymous{LoongArchTargetMachine.cpp}::LoongArchPassConfig::getLoongArchTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68ktargetmachine-cpp-/m68kpassconfig/#aafafadac314eedb06011d14d9fbf826b">anonymous{M68kTargetMachine.cpp}::M68kPassConfig::getM68kTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipstargetmachine-cpp-/mipspassconfig/#a03bcc70174be6bd83646005b9c11187c">anonymous{MipsTargetMachine.cpp}::MipsPassConfig::getMipsTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430targetmachine-cpp-/msp430passconfig/#aa47cba04378431eba847505cf926c7ad">anonymous{MSP430TargetMachine.cpp}::MSP430PassConfig::getMSP430TargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxtargetmachine-cpp-/nvptxpassconfig/#aee7479abb2de25ebc1a1040af93bb8e1">anonymous{NVPTXTargetMachine.cpp}::NVPTXPassConfig::getNVPTXTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppctargetmachine-cpp-/ppcpassconfig/#a76b19ec81ad31becf686f35ae5becfdb">anonymous{PPCTargetMachine.cpp}::PPCPassConfig::getPPCTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#ac27a64323276bc614dfbad7ccaea6969">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::getRISCVTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparctargetmachine-cpp-/sparcpassconfig/#ad76cb81e6b3b09e06812382d5776ceb7">anonymous{SparcTargetMachine.cpp}::SparcPassConfig::getSparcTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvtargetmachine-cpp-/spirvpassconfig/#a24fa7714b59e37b0d9d98490bf917c3c">anonymous{SPIRVTargetMachine.cpp}::SPIRVPassConfig::getSPIRVTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemztargetmachine-cpp-/systemzpassconfig/#ad72edd4fc67f57e6bb8efd1c06065c90">anonymous{SystemZTargetMachine.cpp}::SystemZPassConfig::getSystemZTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-vetargetmachine-cpp-/vepassconfig/#ab2efa8ab163d71fd0c7896da3305d48d">anonymous{VETargetMachine.cpp}::VEPassConfig::getVETargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblytargetmachine-cpp-/webassemblypassconfig/#ab4d67bca5947563e8d8a263a99f4222d">anonymous{WebAssemblyTargetMachine.cpp}::WebAssemblyPassConfig::getWebAssemblyTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86targetmachine-cpp-/x86passconfig/#a4818c762893e8d487fb10381f455aa23">anonymous{X86TargetMachine.cpp}::X86PassConfig::getX86TargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoretargetmachine-cpp-/xcorepassconfig/#af21f5b42c6cbed64dfd681a632231cb9">anonymous{XCoreTargetMachine.cpp}::XCorePassConfig::getXCoreTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-xtensatargetmachine-cpp-/xtensapassconfig/#a3cf500187a0ba0538486298183b6c2aa">anonymous{XtensaTargetMachine.cpp}::XtensaPassConfig::getXtensaTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/#adb730b989e00361a8278e1e55f5b85df">anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#af63d1fba23bc323d27c9dc50313698eb">llvm::SIMachineFunctionInfo::SIMachineFunctionInfo</a>.</p>

</div>
</div>

### regToString() {#ac18edb1d91090c7614b8fcd4dc45d532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::StringValue regToString (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
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



<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp">SIMachineFunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue/#a7b5941aef995e9272fb38c7b69fbb6e4">llvm::yaml::StringValue::Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a80f6630b845109786f0840f4b15737f9">llvm::yaml::SIMachineFunctionInfo::SIMachineFunctionInfo</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
