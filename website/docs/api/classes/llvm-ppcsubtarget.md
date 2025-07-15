---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ppcsubtarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PPCSubtarget` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::PPCSubtarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">Target/PowerPC/PPCSubtarget.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/ppcgensubtargetinfo">PPCGenSubtargetInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">POPCNTDKind { <a href="#a2eeb56ba19044c9c01c2c0606ada7083">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a> (const Triple &amp;TT, const std::string &amp;CPU, const std::string &amp;TuneCPU, const std::string &amp;FS, const PPCTargetMachine &amp;TM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructor initializes the data members to match that of the specified triple. <a href="#ae14557250e6afc406b994fd40e8f5f93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48e64dd0e8d19b4c797abb71622008f0">~PPCSubtarget</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afec26f51f40af3d2379093d906cae749">ParseSubtargetFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options. <a href="#afec26f51f40af3d2379093d906cae749">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf53e983185d3f9a87ecfd9a898a1e18">getStackAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStackAlignment - Returns the minimum alignment known to hold of the stack frame on entry to the function and which must be maintained by every function for this subtarget. <a href="#acf53e983185d3f9a87ecfd9a898a1e18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fdcf13a56a07a0f207e0b0f66bbdbb6">getCPUDirective</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getCPUDirective - Returns the -m directive specified for the cpu. <a href="#a9fdcf13a56a07a0f207e0b0f66bbdbb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a702223f397ca63948ec6596c70339c18">getInstrItineraryData</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getInstrItins - Return the instruction itineraries based on subtarget selection. <a href="#a702223f397ca63948ec6596c70339c18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering">PPCFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a575f4bd95265cbe937901965fe1a53af">getFrameLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo">PPCInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d4c954967e0e3b24114ed438446cf22">getInstrInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering">PPCTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9ac5a1dc657c32bc2999b98bcd7a6b">getTargetLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9d91d08c3f6f73b6043b32e25da222c">getSelectionDAGInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo">PPCRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeefe52b8561be26c1281d79be439cd26">getRegisterInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine">PPCTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae11f695a5e7b6ec5a3c360ecc426ba45">getTargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad002c0a854d56f248f27c0ec622904f0">initializeSubtargetDependencies</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>initializeSubtargetDependencies - Initializes using a CPU, a TuneCPU, and feature string so that we can use initializer lists for subtarget initialization. <a href="#ad002c0a854d56f248f27c0ec622904f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6622b99b3c00a3938d969957312b1b52">isPPC64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isPPC64 - Return true if we are generating code for 64-bit pointer mode. <a href="#a6622b99b3c00a3938d969957312b1b52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a462fd748e4761c8fc497591934179405">useSoftFloat</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ff1051f03e5d6cb2ab582a0ff90409">isLittleEndian</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7589f4c7bffae5ef1ce1de44bf5109a">getPlatformStackAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e3633b3242b24aefa8db459348c92f0">getRedZoneSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d5b9bb6de332cb318e7ee0acf8c213">needsSwapsForVSXMemOps</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2eeb56ba19044c9c01c2c0606ada7083">POPCNTDKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b2fdeebc982821e2817a6f2741dc6d">hasPOPCNTD</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af28c6e546f92baadcbc2aaa5a155324d">getTargetTriple</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3448d554a511f9338fe66a7ea5cede4">isTargetELF</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3764752b29e761af740311eac0b1021c">isTargetMachO</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abadbfa907a7aadce4c75b1191aed2260">isTargetLinux</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ff0ba05eddb8771ac2f2ff7e56aa054">isAIXABI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba17ee6253b371840a5541b1a21b298">isSVR4ABI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad49c3ce74dc865eec4728be0850a7697">isELFv2ABI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a6a1f934a55d58ec73ea20aacbbb68">is64BitELFABI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137ee29e981a9a091e81b79888d8b4a6">is32BitELFABI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2a00931f022fa78f6cdadb07e6d775">isUsingPCRelativeCalls</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8393d417856b52b265f8c5f5566bf980">enableEarlyIfConversion</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Originally, this function return hasISEL(). <a href="#a8393d417856b52b265f8c5f5566bf980">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae769da17ba8233ef473ad066e258e98e">enableMachineScheduler</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scheduling customization. <a href="#ae769da17ba8233ef473ad066e258e98e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d6327aed5635c20926eb30e65db5e83">enableMachinePipeliner</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pipeliner customization. <a href="#a0d6327aed5635c20926eb30e65db5e83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135c18be9f228a8fb4452c637c1eb848">useDFAforSMS</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Machine Pipeliner customization. <a href="#a135c18be9f228a8fb4452c637c1eb848">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd412cc00b537182eb908ef6ab14e593">enablePostRAScheduler</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This overrides the PostRAScheduler bit in the SchedModel for each CPU. <a href="#afd412cc00b537182eb908ef6ab14e593">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">AntiDepBreakMode</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a332e9eb338b0d076c0b72925f375f">getAntiDepBreakMode</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682640efb34dd5fd07ceb328f624fd53">getCriticalPathRCs</a> (RegClassVector &amp;CriticalPathRCs) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b85cc5821fb2328cf0040aa9f8230b">overrideSchedPolicy</a> (MachineSchedPolicy &amp;Policy, unsigned NumRegionInstrs) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5130477b9afca4e4fea2926da75a5e">useAA</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2a694b5523a3f2d469e7c6063e3856">enableSubRegLiveness</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3590f66d425ff4c04858909eddf1735">enableSpillageCopyElimination</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af216ae10b12114faf1ddde74d3520cf0">isGVIndirectSymbol</a> (const GlobalValue *GV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the GV will be accessed via an indirect symbol. <a href="#af216ae10b12114faf1ddde74d3520cf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e8f6570461d1fd818dbfbf7ff03283a">getScalarIntVT</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1da03c90232fadc79f4c8d041bbce56">getCodeModel</a> (const TargetMachine &amp;TM, const GlobalValue *GV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculates the effective code model for argument GV. <a href="#ad1da03c90232fadc79f4c8d041bbce56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b7e50f5c53f9dd5d5ebbb3a0bfb434c">usesFunctionDescriptors</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the ABI is descriptor based. <a href="#a6b7e50f5c53f9dd5d5ebbb3a0bfb434c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a359e26a7b0adfd51f672f641ee8abaad">descriptorTOCAnchorOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2f4a081a9b592223710411a8365bd7b">descriptorEnvironmentPointerOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ffd45d02f1a8d9920e4508c5ec0970">getEnvironmentPointerRegister</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1ff4a166a708dddd7c3df1d2fac540f">getTOCPointerRegister</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a994ad0d5f0a6e9204731109727cbee4e">getThreadPointerRegister</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3d33dfd2b7568f38f08c7e6a60496b6">getStackPointerRegister</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cfcf444385eba48f1f603ef34960733">isXRaySupported</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae372a0cbd193dd4f2899d36a930c067e">isPredictableSelectIsExpensive</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45dcc471c5873a662f47aa7d69c26567">getGPRAllocationOrderIdx</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4079b922a58ba583f374e9d1cfb7a458">getCallLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed509f888e5ce6fbfa3af691724d701d">getRegBankInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4331a66b57da79a5818926b746854508">getLegalizerInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c3b235492fe91efccbadef1ef5b1f0b">getInstructionSelector</a> () const override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30efd7e41c884e00b7301de6bc3a0446">initializeEnvironment</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac8a9b11564e84b7b1ab582b8b571e1e">initSubtargetFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42143f998fef45d515043b7d47249db2">TargetTriple</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TargetTriple - What processor and OS we're targeting. <a href="#a42143f998fef45d515043b7d47249db2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5615780de41c907a7b5b48d1f3b94e15">StackAlignment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>stackAlignment - The minimum alignment known to hold of the stack frame on entry to the function and which must be maintained by every function. <a href="#a5615780de41c907a7b5b48d1f3b94e15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a556a987e65c2ba607b0bd95b9addc794">InstrItins</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Selected instruction itineraries (one entry per itinerary class.) <a href="#a556a987e65c2ba607b0bd95b9addc794">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf430e8f55311f8a5c915f934b10564">CPUDirective</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Which cpu directive was used. <a href="#a8cf430e8f55311f8a5c915f934b10564">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe1a03cb47163239bf6af7300a56f47a">IsPPC64</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033667dfabbb37781612b299275b2cd4">IsLittleEndian</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2eeb56ba19044c9c01c2c0606ada7083">POPCNTDKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4ee519b7eb7c0b01b4c4f21e1bfe77">HasPOPCNTD</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine">PPCTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2ea016ce9b29b6f90eb058aedceca4b">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppcframelowering">PPCFrameLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e9bfe3064232d157505fe041db301d2">FrameLowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo">PPCInstrInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b8ad9569e3edf6f8ec8bddd7e15e7f">InstrInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering">PPCTargetLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ca38e98ae387775c7fda7da2b26d6b">TLInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae705899524cc9dc65eb8e90be1c342ca">TSInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa9390b7bdd37d7aa6fc1316915ed92d">CallLoweringInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GlobalISel related APIs. <a href="#afa9390b7bdd37d7aa6fc1316915ed92d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15a2cf75558dd706b0e1220972c7ea0b">Legalizer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f84c3ba6bace6ecc50e2eb96bdbea2">RegBankInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0536561eb82f66bd686edc267b707da3">InstSelector</a></td>
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


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### POPCNTDKind {#a2eeb56ba19044c9c01c2c0606ada7083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PPCSubtarget::POPCNTDKind </td>
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
<td class="doxyEnumItemName">POPCNTD_Unavailable<a id="a2eeb56ba19044c9c01c2c0606ada7083adf6cd18e5546a8897639fa528f81f375"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">POPCNTD_Slow<a id="a2eeb56ba19044c9c01c2c0606ada7083ab0fb8c03d2414c080c21b73aeae5a13c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">POPCNTD_Fast<a id="a2eeb56ba19044c9c01c2c0606ada7083a5905b4b9443e62f9efe0c22aab6260d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PPCSubtarget() {#ae14557250e6afc406b994fd40e8f5f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCSubtarget::PPCSubtarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; CPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; TuneCPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine">PPCTargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This constructor initializes the data members to match that of the specified triple.</p>

<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>References <a href="#afa9390b7bdd37d7aa6fc1316915ed92d">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb28aa21ad009ea562a40afec008df87">llvm::createPPCInstructionSelector</a>, <a href="#a3e9bfe3064232d157505fe041db301d2">FrameLowering</a>, <a href="#aeefe52b8561be26c1281d79be439cd26">getRegisterInfo</a>, <a href="#a6c9ac5a1dc657c32bc2999b98bcd7a6b">getTargetLowering</a>, <a href="#ad002c0a854d56f248f27c0ec622904f0">initializeSubtargetDependencies</a>, <a href="#a65b8ad9569e3edf6f8ec8bddd7e15e7f">InstrInfo</a>, <a href="#a0536561eb82f66bd686edc267b707da3">InstSelector</a>, <a href="#afe1a03cb47163239bf6af7300a56f47a">IsPPC64</a>, <a href="#a15a2cf75558dd706b0e1220972c7ea0b">Legalizer</a>, <a href="#a47f84c3ba6bace6ecc50e2eb96bdbea2">RegBankInfo</a>, <a href="#a42143f998fef45d515043b7d47249db2">TargetTriple</a>, <a href="#a16ca38e98ae387775c7fda7da2b26d6b">TLInfo</a>, <a href="#ae2ea016ce9b29b6f90eb058aedceca4b">TM</a> and <a href="#ae705899524cc9dc65eb8e90be1c342ca">TSInfo</a>.</p>


<p>Referenced by <a href="#ad002c0a854d56f248f27c0ec622904f0">initializeSubtargetDependencies</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PPCSubtarget() {#a48e64dd0e8d19b4c797abb71622008f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCSubtarget::~PPCSubtarget ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### descriptorEnvironmentPointerOffset() {#af2f4a081a9b592223710411a8365bd7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPCSubtarget::descriptorEnvironmentPointerOffset ()</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afe1a03cb47163239bf6af7300a56f47a">IsPPC64</a> and <a href="#a6b7e50f5c53f9dd5d5ebbb3a0bfb434c">usesFunctionDescriptors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aefc8b558bcaf81b735d0f6e634279aef">prepareDescriptorIndirectCall</a>.</p>

</div>
</div>

### descriptorTOCAnchorOffset() {#a359e26a7b0adfd51f672f641ee8abaad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPCSubtarget::descriptorTOCAnchorOffset ()</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afe1a03cb47163239bf6af7300a56f47a">IsPPC64</a> and <a href="#a6b7e50f5c53f9dd5d5ebbb3a0bfb434c">usesFunctionDescriptors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aefc8b558bcaf81b735d0f6e634279aef">prepareDescriptorIndirectCall</a>.</p>

</div>
</div>

### enableEarlyIfConversion() {#a8393d417856b52b265f8c5f5566bf980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::enableEarlyIfConversion ()</td>
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

<p>Originally, this function return hasISEL().</p>


<p>Now we always enable it, but may expand the ISEL instruction later.</p>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>

</div>
</div>

### enableMachinePipeliner() {#a0d6327aed5635c20926eb30e65db5e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCSubtarget::enableMachinePipeliner ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pipeliner customization.</p>

<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#adf236a077b71d539a7e12cbf9df34313">EnableMachinePipeliner</a>.</p>

</div>
</div>

### enableMachineScheduler() {#ae769da17ba8233ef473ad066e258e98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCSubtarget::enableMachineScheduler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scheduling customization.</p>

<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>

</div>
</div>

### enablePostRAScheduler() {#afd412cc00b537182eb908ef6ab14e593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCSubtarget::enablePostRAScheduler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This overrides the PostRAScheduler bit in the SchedModel for each CPU.</p>

<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>

</div>
</div>

### enableSpillageCopyElimination() {#aa3590f66d425ff4c04858909eddf1735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::enableSpillageCopyElimination ()</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>

</div>
</div>

### enableSubRegLiveness() {#a6a2a694b5523a3f2d469e7c6063e3856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCSubtarget::enableSubRegLiveness ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>

</div>
</div>

### getAntiDepBreakMode() {#a98a332e9eb338b0d076c0b72925f375f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCGenSubtargetInfo::AntiDepBreakMode PPCSubtarget::getAntiDepBreakMode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>

</div>
</div>

### getCallLowering() {#a4079b922a58ba583f374e9d1cfb7a458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallLowering * PPCSubtarget::getCallLowering ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>Reference <a href="#afa9390b7bdd37d7aa6fc1316915ed92d">CallLoweringInfo</a>.</p>

</div>
</div>

### getCodeModel() {#ad1da03c90232fadc79f4c8d041bbce56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeModel::Model PPCSubtarget::getCodeModel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculates the effective code model for argument GV.</p>

<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a311a097af4f0f77da22ac7acddc496f5">llvm::GlobalAlias::getAliaseeObject</a>, <a href="#a3ff0ba05eddb8771ac2f2ff7e56aa054">isAIXABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a> and <a href="#ae2ea016ce9b29b6f90eb058aedceca4b">TM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#aa85a26f5f6b24110a2388e4726cdd282">getCodeModel</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a5d70066b330f0860014d91d4974e56b0">getCodeModel</a>.</p>

</div>
</div>

### getCPUDirective() {#a9fdcf13a56a07a0f207e0b0f66bbdbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPCSubtarget::getCPUDirective ()</td>
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

<p>getCPUDirective - Returns the -m directive specified for the cpu.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a8cf430e8f55311f8a5c915f934b10564">CPUDirective</a>.</p>

</div>
</div>

### getCriticalPathRCs() {#a682640efb34dd5fd07ceb328f624fd53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCSubtarget::getCriticalPathRCs (RegClassVector &amp; CriticalPathRCs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>Reference <a href="#a6622b99b3c00a3938d969957312b1b52">isPPC64</a>.</p>

</div>
</div>

### getEnvironmentPointerRegister() {#a83ffd45d02f1a8d9920e4508c5ec0970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::PPCSubtarget::getEnvironmentPointerRegister ()</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afe1a03cb47163239bf6af7300a56f47a">IsPPC64</a> and <a href="#a6b7e50f5c53f9dd5d5ebbb3a0bfb434c">usesFunctionDescriptors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aefc8b558bcaf81b735d0f6e634279aef">prepareDescriptorIndirectCall</a>.</p>

</div>
</div>

### getFrameLowering() {#a575f4bd95265cbe937901965fe1a53af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCFrameLowering * llvm::PPCSubtarget::getFrameLowering ()</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a3e9bfe3064232d157505fe041db301d2">FrameLowering</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#acca11c9d64a646da497e82dcf6e9636e">EmitTailCallStoreFPAndRetAddr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a0ccb1948e466b25257ec5f95a2b8e11e">needStackSlotPassParameters</a>.</p>

</div>
</div>

### getGPRAllocationOrderIdx() {#a45dcc471c5873a662f47aa7d69c26567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPCSubtarget::getGPRAllocationOrderIdx ()</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="#ad1a6a1f934a55d58ec73ea20aacbbb68">is64BitELFABI</a> and <a href="#a3ff0ba05eddb8771ac2f2ff7e56aa054">isAIXABI</a>.</p>

</div>
</div>

### getInstrInfo() {#a8d4c954967e0e3b24114ed438446cf22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCInstrInfo * llvm::PPCSubtarget::getInstrInfo ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a65b8ad9569e3edf6f8ec8bddd7e15e7f">InstrInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">llvm::PPCRegisterInfo::eliminateFrameIndex</a>, <a href="#aeefe52b8561be26c1281d79be439cd26">getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#af971878700ebbaf8580902e09691cb03">llvm::PPCRegisterInfo::lowerACCRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a3a48db1e7d2f40e7a4ce6aed74b35d6d">llvm::PPCRegisterInfo::lowerACCSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aa90550e5d59f68a547e28c8beeefb3ed">llvm::PPCRegisterInfo::lowerCRBitRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a38572a53736b568d95a5adc23bcd67f0">llvm::PPCRegisterInfo::lowerCRBitSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a7f3c8b41556bad389b00bd408c9b969f">llvm::PPCRegisterInfo::lowerCRRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a49453cd92df6e63d0c2c45e1d5ace04b">llvm::PPCRegisterInfo::lowerCRSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a4d0bcb536bd3b6491c535f206275ad89">llvm::PPCRegisterInfo::lowerDynamicAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a4b9f5c287ed918ba764f534b79876702">llvm::PPCRegisterInfo::lowerDynamicAreaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ae9e97e19c06502185a9f18648de069eb">llvm::PPCRegisterInfo::lowerOctWordSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#abd8bb8f19f51d30e31b0acac86d8b27c">llvm::PPCRegisterInfo::lowerPrepareProbedAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a989635d1db601cdd8a25fe859221a1d6">llvm::PPCRegisterInfo::lowerQuadwordRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#acca986611114a82bcfb66e10bb9853f0">llvm::PPCRegisterInfo::lowerQuadwordSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ab2c246f45a8786eb5745c6cd9664d088">llvm::PPCRegisterInfo::lowerWACCRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ae7ec7dfcb6babc9f95a9d27ca37dddcc">llvm::PPCRegisterInfo::lowerWACCSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ab0c9dd2c74f5a4d226e5f57423aa53b9">llvm::PPCRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a355a1f30be913f4dc74c51af277fd74a">llvm::PPCRegisterInfo::prepareDynamicAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a454cc7f0c0075624df31b3ae121c3506">llvm::PPCRegisterInfo::requiresFrameIndexScavenging</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a08197b04118de1d943982bbe9a7ca533">llvm::PPCRegisterInfo::resolveFrameIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxcopy-cpp-/ppcvsxcopy/#a50947d09cf680568c73cf95de9f8cafe">anonymous{PPCVSXCopy.cpp}::PPCVSXCopy::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#a4d6db0f25025bd365ee0251e88bda4fd">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::runOnMachineFunction</a>.</p>

</div>
</div>

### getInstrItineraryData() {#a702223f397ca63948ec6596c70339c18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrItineraryData * llvm::PPCSubtarget::getInstrItineraryData ()</td>
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

<p>getInstrItins - Return the instruction itineraries based on subtarget selection.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a556a987e65c2ba607b0bd95b9addc794">InstrItins</a>.</p>

</div>
</div>

### getInstructionSelector() {#a7c3b235492fe91efccbadef1ef5b1f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector * PPCSubtarget::getInstructionSelector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>Reference <a href="#a0536561eb82f66bd686edc267b707da3">InstSelector</a>.</p>

</div>
</div>

### getLegalizerInfo() {#a4331a66b57da79a5818926b746854508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo * PPCSubtarget::getLegalizerInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>Reference <a href="#a15a2cf75558dd706b0e1220972c7ea0b">Legalizer</a>.</p>

</div>
</div>

### getPlatformStackAlignment() {#ad7589f4c7bffae5ef1ce1de44bf5109a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::PPCSubtarget::getPlatformStackAlignment ()</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>

</div>
</div>

### getRedZoneSize() {#a8e3633b3242b24aefa8db459348c92f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPCSubtarget::getRedZoneSize ()</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="#a3ff0ba05eddb8771ac2f2ff7e56aa054">isAIXABI</a> and <a href="#a6622b99b3c00a3938d969957312b1b52">isPPC64</a>.</p>

</div>
</div>

### getRegBankInfo() {#aed509f888e5ce6fbfa3af691724d701d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo * PPCSubtarget::getRegBankInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>Reference <a href="#a47f84c3ba6bace6ecc50e2eb96bdbea2">RegBankInfo</a>.</p>

</div>
</div>

### getRegisterInfo() {#aeefe52b8561be26c1281d79be439cd26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCRegisterInfo * llvm::PPCSubtarget::getRegisterInfo ()</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="#a8d4c954967e0e3b24114ed438446cf22">getInstrInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a4689e7af05ff1347bf7f4be83521a3ae">llvm::PPCInstrInfo::getRegisterInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a38572a53736b568d95a5adc23bcd67f0">llvm::PPCRegisterInfo::lowerCRBitSpilling</a>, <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a> and <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ac6cddb4c330de0e51a5977de243a3ded">llvm::PPCTargetLowering::PPCTargetLowering</a>.</p>

</div>
</div>

### getScalarIntVT() {#a3e8f6570461d1fd818dbfbf7ff03283a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::PPCSubtarget::getScalarIntVT ()</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a6622b99b3c00a3938d969957312b1b52">isPPC64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a63e41a021ab399fe0054faade8a184b3">CC_AIX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aa8731851366e0258bc7a96535eb33a91">convertFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#acca11c9d64a646da497e82dcf6e9636e">EmitTailCallStoreFPAndRetAddr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aefc8b558bcaf81b735d0f6e634279aef">prepareDescriptorIndirectCall</a>.</p>

</div>
</div>

### getSelectionDAGInfo() {#ac9d91d08c3f6f73b6043b32e25da222c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SelectionDAGTargetInfo * PPCSubtarget::getSelectionDAGInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>Reference <a href="#ae705899524cc9dc65eb8e90be1c342ca">TSInfo</a>.</p>

</div>
</div>

### getStackAlignment() {#acf53e983185d3f9a87ecfd9a898a1e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::PPCSubtarget::getStackAlignment ()</td>
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

<p>getStackAlignment - Returns the minimum alignment known to hold of the stack frame on entry to the function and which must be maintained by every function for this subtarget.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a5615780de41c907a7b5b48d1f3b94e15">StackAlignment</a>.</p>

</div>
</div>

### getStackPointerRegister() {#ac3d33dfd2b7568f38f08c7e6a60496b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::PPCSubtarget::getStackPointerRegister ()</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#afe1a03cb47163239bf6af7300a56f47a">IsPPC64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a6fdba831dfffefd06bd242697b32ff72">llvm::PPCRegisterInfo::isCallerPreservedPhysReg</a>.</p>

</div>
</div>

### getTargetLowering() {#a6c9ac5a1dc657c32bc2999b98bcd7a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCTargetLowering * llvm::PPCSubtarget::getTargetLowering ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a16ca38e98ae387775c7fda7da2b26d6b">TLInfo</a>.</p>


<p>Referenced by <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a0f3fc21d30eef606c68c9882dd8a97b0">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::runOnMachineFunction</a>.</p>

</div>
</div>

### getTargetMachine() {#ae11f695a5e7b6ec5a3c360ecc426ba45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCTargetMachine &amp; llvm::PPCSubtarget::getTargetMachine ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#ae2ea016ce9b29b6f90eb058aedceca4b">TM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#afcf9c9efe452f11d4713cc9657c1c4cd">computeBasePointerSaveOffset</a>, <a href="#a6a2a00931f022fa78f6cdadb07e6d775">isUsingPCRelativeCalls</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a>.</p>

</div>
</div>

### getTargetTriple() {#af28c6e546f92baadcbc2aaa5a155324d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::PPCSubtarget::getTargetTriple ()</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a42143f998fef45d515043b7d47249db2">TargetTriple</a>.</p>

</div>
</div>

### getThreadPointerRegister() {#a994ad0d5f0a6e9204731109727cbee4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::PPCSubtarget::getThreadPointerRegister ()</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1a6a1f934a55d58ec73ea20aacbbb68">is64BitELFABI</a>, <a href="#a3ff0ba05eddb8771ac2f2ff7e56aa054">isAIXABI</a> and <a href="#afe1a03cb47163239bf6af7300a56f47a">IsPPC64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a23bdd93cc79ae6095f38f4bc4f7eec80">isEligibleToFoldADDIForFasterLocalAccesses</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a46bc06dfe642d862d66026b7e1546b23">isThreadPointerAcquisitionNode</a>.</p>

</div>
</div>

### getTOCPointerRegister() {#ac1ff4a166a708dddd7c3df1d2fac540f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::PPCSubtarget::getTOCPointerRegister ()</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1a6a1f934a55d58ec73ea20aacbbb68">is64BitELFABI</a>, <a href="#a3ff0ba05eddb8771ac2f2ff7e56aa054">isAIXABI</a> and <a href="#afe1a03cb47163239bf6af7300a56f47a">IsPPC64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a6fdba831dfffefd06bd242697b32ff72">llvm::PPCRegisterInfo::isCallerPreservedPhysReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aefc8b558bcaf81b735d0f6e634279aef">prepareDescriptorIndirectCall</a>.</p>

</div>
</div>

### hasPOPCNTD() {#aa4b2fdeebc982821e2817a6f2741dc6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">POPCNTDKind llvm::PPCSubtarget::hasPOPCNTD ()</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a4f4ee519b7eb7c0b01b4c4f21e1bfe77">HasPOPCNTD</a>.</p>

</div>
</div>

### initializeSubtargetDependencies() {#ad002c0a854d56f248f27c0ec622904f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCSubtarget &amp; PPCSubtarget::initializeSubtargetDependencies (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>initializeSubtargetDependencies - Initializes using a CPU, a TuneCPU, and feature string so that we can use initializer lists for subtarget initialization.</p>

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>Reference <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>


<p>Referenced by <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>

</div>
</div>

### is32BitELFABI() {#a137ee29e981a9a091e81b79888d8b4a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::is32BitELFABI ()</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="#a6622b99b3c00a3938d969957312b1b52">isPPC64</a> and <a href="#a9ba17ee6253b371840a5541b1a21b298">isSVR4ABI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#afcf9c9efe452f11d4713cc9657c1c4cd">computeBasePointerSaveOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aed31f9e731d0e88307aa322db45a11d8">llvm::PPCRegisterInfo::getReservedRegs</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a>.</p>

</div>
</div>

### is64BitELFABI() {#ad1a6a1f934a55d58ec73ea20aacbbb68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::is64BitELFABI ()</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="#a6622b99b3c00a3938d969957312b1b52">isPPC64</a> and <a href="#a9ba17ee6253b371840a5541b1a21b298">isSVR4ABI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a04db783920e3a77ee7d48c5bc4d10b9a">getCallOpcode</a>, <a href="#a45dcc471c5873a662f47aa7d69c26567">getGPRAllocationOrderIdx</a>, <a href="#a994ad0d5f0a6e9204731109727cbee4e">getThreadPointerRegister</a>, <a href="#ac1ff4a166a708dddd7c3df1d2fac540f">getTOCPointerRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a6fdba831dfffefd06bd242697b32ff72">llvm::PPCRegisterInfo::isCallerPreservedPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a31220864cbe46fe951bcf083015c5456">isTOCSaveRestoreRequired</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a0ccb1948e466b25257ec5f95a2b8e11e">needStackSlotPassParameters</a> and <a href="#a6b7e50f5c53f9dd5d5ebbb3a0bfb434c">usesFunctionDescriptors</a>.</p>

</div>
</div>

### isAIXABI() {#a3ff0ba05eddb8771ac2f2ff7e56aa054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::isAIXABI ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a42143f998fef45d515043b7d47249db2">TargetTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a2860a7b9656bf72a5002647efbb7a1f7">computeCRSaveOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#aad761a684381fe97901b2ca83b112b9b">computeLinkageSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a5fa3d40d2c434f1e70a98776e4922870">computeReturnSaveOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#aedfad9d0242953049a125df37ac8daa3">computeTOCSaveOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aaeae02cd060afb658b3e1e17ad7e42c5">llvm::PPCRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a04db783920e3a77ee7d48c5bc4d10b9a">getCallOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a58726f6c4ef9c4395ca278c3266c97f6">llvm::PPCRegisterInfo::getCallPreservedMask</a>, <a href="#ad1da03c90232fadc79f4c8d041bbce56">getCodeModel</a>, <a href="#a45dcc471c5873a662f47aa7d69c26567">getGPRAllocationOrderIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aef6a94b763376e95e861f14451a12d5b">llvm::PPCRegisterInfo::getLargestLegalSuperClass</a>, <a href="#a8e3633b3242b24aefa8db459348c92f0">getRedZoneSize</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ab0d7ef2c34f8283a7ae1891dbe6a9321">llvm::PPCRegisterInfo::getRegPressureLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aed31f9e731d0e88307aa322db45a11d8">llvm::PPCRegisterInfo::getReservedRegs</a>, <a href="#a994ad0d5f0a6e9204731109727cbee4e">getThreadPointerRegister</a>, <a href="#ac1ff4a166a708dddd7c3df1d2fac540f">getTOCPointerRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a6fdba831dfffefd06bd242697b32ff72">llvm::PPCRegisterInfo::isCallerPreservedPhysReg</a>, <a href="#af216ae10b12114faf1ddde74d3520cf0">isGVIndirectSymbol</a>, <a href="#a9ba17ee6253b371840a5541b1a21b298">isSVR4ABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a31220864cbe46fe951bcf083015c5456">isTOCSaveRestoreRequired</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aefc8b558bcaf81b735d0f6e634279aef">prepareDescriptorIndirectCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a>, <a href="#a6b7e50f5c53f9dd5d5ebbb3a0bfb434c">usesFunctionDescriptors</a> and <a href="#a462fd748e4761c8fc497591934179405">useSoftFloat</a>.</p>

</div>
</div>

### isELFv2ABI() {#ad49c3ce74dc865eec4728be0850a7697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCSubtarget::isELFv2ABI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>Reference <a href="#ae2ea016ce9b29b6f90eb058aedceca4b">TM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#aad761a684381fe97901b2ca83b112b9b">computeLinkageSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#aedfad9d0242953049a125df37ac8daa3">computeTOCSaveOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchselector-cpp/#a6ce9d801876c8c6c8d4653a1dcf18acd">GetInitialOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aed64046c04e9e3d1c58346b9754ca258">isIndirectCall</a>, <a href="#a6a2a00931f022fa78f6cdadb07e6d775">isUsingPCRelativeCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a> and <a href="#a6b7e50f5c53f9dd5d5ebbb3a0bfb434c">usesFunctionDescriptors</a>.</p>

</div>
</div>

### isGVIndirectSymbol() {#af216ae10b12114faf1ddde74d3520cf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCSubtarget::isGVIndirectSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the GV will be accessed via an indirect symbol.</p>

<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a3ff0ba05eddb8771ac2f2ff7e56aa054">isAIXABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a> and <a href="#ae2ea016ce9b29b6f90eb058aedceca4b">TM</a>.</p>

</div>
</div>

### isLittleEndian() {#ab9ff1051f03e5d6cb2ab582a0ff90409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::isLittleEndian ()</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a033667dfabbb37781612b299275b2cd4">IsLittleEndian</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a9df1b82e469730d220e3a8d28eb985e8">fixupShuffleMaskForPermutedSToV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a9c14200e1f694991be37e9f9c9d9d576">getDataClassTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6388d46f1b629bc93ef3a8b25d61c141">getSToVPermuted</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#af971878700ebbaf8580902e09691cb03">llvm::PPCRegisterInfo::lowerACCRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a3a48db1e7d2f40e7a4ce6aed74b35d6d">llvm::PPCRegisterInfo::lowerACCSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ae9e97e19c06502185a9f18648de069eb">llvm::PPCRegisterInfo::lowerOctWordSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a989635d1db601cdd8a25fe859221a1d6">llvm::PPCRegisterInfo::lowerQuadwordRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#acca986611114a82bcfb66e10bb9853f0">llvm::PPCRegisterInfo::lowerQuadwordSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ab2c246f45a8786eb5745c6cd9664d088">llvm::PPCRegisterInfo::lowerWACCRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ae7ec7dfcb6babc9f95a9d27ca37dddcc">llvm::PPCRegisterInfo::lowerWACCSpilling</a> and <a href="#a57d5b9bb6de332cb318e7ee0acf8c213">needsSwapsForVSXMemOps</a>.</p>

</div>
</div>

### isPPC64() {#a6622b99b3c00a3938d969957312b1b52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCSubtarget::isPPC64 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isPPC64 - Return true if we are generating code for 64-bit pointer mode.</p>

<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>Reference <a href="#ae2ea016ce9b29b6f90eb058aedceca4b">TM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a63e41a021ab399fe0054faade8a184b3">CC_AIX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1cb8184c9c7806da491d6facc22a7fba">combineADDToADDZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#afcf9c9efe452f11d4713cc9657c1c4cd">computeBasePointerSaveOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a2860a7b9656bf72a5002647efbb7a1f7">computeCRSaveOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#ab24a042363e1e4863d84c337bd79cefd">computeFramePointerSaveOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#aad761a684381fe97901b2ca83b112b9b">computeLinkageSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a5fa3d40d2c434f1e70a98776e4922870">computeReturnSaveOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#aedfad9d0242953049a125df37ac8daa3">computeTOCSaveOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a2cd7fb94f62f409bc4faf2a20e0904eb">llvm::PPC::createFastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcinstrinfo-cpp-/ppcpipelinerloopinfo/#a849593db21c6c97b0f31b2e29e33483d">anonymous{PPCInstrInfo.cpp}::PPCPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#acca11c9d64a646da497e82dcf6e9636e">EmitTailCallStoreFPAndRetAddr</a>, <a href="#a682640efb34dd5fd07ceb328f624fd53">getCriticalPathRCs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a9c14200e1f694991be37e9f9c9d9d576">getDataClassTest</a>, <a href="#a8e3633b3242b24aefa8db459348c92f0">getRedZoneSize</a>, <a href="#a3e8f6570461d1fd818dbfbf7ff03283a">getScalarIntVT</a>, <a href="#a137ee29e981a9a091e81b79888d8b4a6">is32BitELFABI</a>, <a href="#ad1a6a1f934a55d58ec73ea20aacbbb68">is64BitELFABI</a>, <a href="#a6a2a00931f022fa78f6cdadb07e6d775">isUsingPCRelativeCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aefc8b558bcaf81b735d0f6e634279aef">prepareDescriptorIndirectCall</a> and <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a>.</p>

</div>
</div>

### isPredictableSelectIsExpensive() {#ae372a0cbd193dd4f2899d36a930c067e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::isPredictableSelectIsExpensive ()</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>

</div>
</div>

### isSVR4ABI() {#a9ba17ee6253b371840a5541b1a21b298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::isSVR4ABI ()</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a3ff0ba05eddb8771ac2f2ff7e56aa054">isAIXABI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a2820765d9ab1a6dcb83de3d870d2c7b8">llvm::PPCRegisterInfo::getBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aed31f9e731d0e88307aa322db45a11d8">llvm::PPCRegisterInfo::getReservedRegs</a>, <a href="#a137ee29e981a9a091e81b79888d8b4a6">is32BitELFABI</a>, <a href="#ad1a6a1f934a55d58ec73ea20aacbbb68">is64BitELFABI</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a78b9ad4b9b246aab32ff14d856f5769a">llvm::PPCInstrInfo::isSignOrZeroExtended</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a62a1e2af50ab6132cd2d8d168835ef57">llvm::PPCInstrInfo::promoteInstr32To64ForElimEXTSW</a>.</p>

</div>
</div>

### isTargetELF() {#ac3448d554a511f9338fe66a7ea5cede4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::isTargetELF ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a42143f998fef45d515043b7d47249db2">TargetTriple</a>.</p>

</div>
</div>

### isTargetLinux() {#abadbfa907a7aadce4c75b1191aed2260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::isTargetLinux ()</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a42143f998fef45d515043b7d47249db2">TargetTriple</a>.</p>

</div>
</div>

### isTargetMachO() {#a3764752b29e761af740311eac0b1021c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::isTargetMachO ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#a42143f998fef45d515043b7d47249db2">TargetTriple</a>.</p>

</div>
</div>

### isUsingPCRelativeCalls() {#a6a2a00931f022fa78f6cdadb07e6d775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCSubtarget::isUsingPCRelativeCalls ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ae106f6c6362377b3016f0d174227e193">llvm::TargetMachine::getCodeModel</a>, <a href="#ae11f695a5e7b6ec5a3c360ecc426ba45">getTargetMachine</a>, <a href="#ad49c3ce74dc865eec4728be0850a7697">isELFv2ABI</a>, <a href="#a6622b99b3c00a3938d969957312b1b52">isPPC64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a43a17d867ea4d3bca00dfb065f8cc811">callsShareTOCBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a2fc82b70727afff2c18b36c0a6c280cd">combineADDToMAT_PCREL_ADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aaeae02cd060afb658b3e1e17ad7e42c5">llvm::PPCRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a04db783920e3a77ee7d48c5bc4d10b9a">getCallOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a31220864cbe46fe951bcf083015c5456">isTOCSaveRestoreRequired</a> and <a href="/web-llvm/docs/api/structs/anonymous-ppcmipeephole-cpp-/ppcmipeephole/#a835b87b88f0868fb797ae3d27da54081">anonymous{PPCMIPeephole.cpp}::PPCMIPeephole::runOnMachineFunction</a>.</p>

</div>
</div>

### isXRaySupported() {#a4cfcf444385eba48f1f603ef34960733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::isXRaySupported ()</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="#a033667dfabbb37781612b299275b2cd4">IsLittleEndian</a> and <a href="#afe1a03cb47163239bf6af7300a56f47a">IsPPC64</a>.</p>

</div>
</div>

### needsSwapsForVSXMemOps() {#a57d5b9bb6de332cb318e7ee0acf8c213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::needsSwapsForVSXMemOps ()</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Reference <a href="#ab9ff1051f03e5d6cb2ab582a0ff90409">isLittleEndian</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxswapremoval-cpp-/ppcvsxswapremoval/#a9ddff289404aac49861d6bacccbbb057">anonymous{PPCVSXSwapRemoval.cpp}::PPCVSXSwapRemoval::runOnMachineFunction</a>.</p>

</div>
</div>

### overrideSchedPolicy() {#a62b85cc5821fb2328cf0040aa9f8230b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCSubtarget::overrideSchedPolicy (<a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy">MachineSchedPolicy</a> &amp; Policy, unsigned NumRegionInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#a47ee8ec29daa3551f798ff4449fbf4d5">llvm::MachineSchedPolicy::OnlyBottomUp</a> and <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#aee4e3964174cee8cf362508ccef135ca">llvm::MachineSchedPolicy::ShouldTrackPressure</a>.</p>

</div>
</div>

### ParseSubtargetFeatures() {#afec26f51f40af3d2379093d906cae749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PPCSubtarget::ParseSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options.</p>


<p>Definition of function is auto generated by tblgen.</p>


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>

</div>
</div>

### useAA() {#acb5130477b9afca4e4fea2926da75a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCSubtarget::useAA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>

</div>
</div>

### useDFAforSMS() {#a135c18be9f228a8fb4452c637c1eb848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCSubtarget::useDFAforSMS ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Machine Pipeliner customization.</p>

<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>

</div>
</div>

### usesFunctionDescriptors() {#a6b7e50f5c53f9dd5d5ebbb3a0bfb434c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::usesFunctionDescriptors ()</td>
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

<p>True if the ABI is descriptor based.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="#ad1a6a1f934a55d58ec73ea20aacbbb68">is64BitELFABI</a>, <a href="#a3ff0ba05eddb8771ac2f2ff7e56aa054">isAIXABI</a> and <a href="#ad49c3ce74dc865eec4728be0850a7697">isELFv2ABI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="#af2f4a081a9b592223710411a8365bd7b">descriptorEnvironmentPointerOffset</a>, <a href="#a359e26a7b0adfd51f672f641ee8abaad">descriptorTOCAnchorOffset</a>, <a href="#a83ffd45d02f1a8d9920e4508c5ec0970">getEnvironmentPointerRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aed64046c04e9e3d1c58346b9754ca258">isIndirectCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a>.</p>

</div>
</div>

### useSoftFloat() {#a462fd748e4761c8fc497591934179405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::useSoftFloat ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>References <a href="#a3ff0ba05eddb8771ac2f2ff7e56aa054">isAIXABI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### initializeEnvironment() {#a30efd7e41c884e00b7301de6bc3a0446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCSubtarget::initializeEnvironment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>

</div>
</div>

### initSubtargetFeatures() {#aac8a9b11564e84b7b1ab582b8b571e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCSubtarget::initSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CallLoweringInfo {#afa9390b7bdd37d7aa6fc1316915ed92d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CallLowering&gt; llvm::PPCSubtarget::CallLoweringInfo</td>
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

<p>GlobalISel related APIs.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#a4079b922a58ba583f374e9d1cfb7a458">getCallLowering</a> and <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>

</div>
</div>

### CPUDirective {#a8cf430e8f55311f8a5c915f934b10564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPCSubtarget::CPUDirective</td>
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

<p>Which cpu directive was used.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#a9fdcf13a56a07a0f207e0b0f66bbdbb6">getCPUDirective</a>.</p>

</div>
</div>

### FrameLowering {#a3e9bfe3064232d157505fe041db301d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCFrameLowering llvm::PPCSubtarget::FrameLowering</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#a575f4bd95265cbe937901965fe1a53af">getFrameLowering</a> and <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>

</div>
</div>

### HasPOPCNTD {#a4f4ee519b7eb7c0b01b4c4f21e1bfe77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">POPCNTDKind llvm::PPCSubtarget::HasPOPCNTD</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa4b2fdeebc982821e2817a6f2741dc6d">hasPOPCNTD</a>.</p>

</div>
</div>

### InstrInfo {#a65b8ad9569e3edf6f8ec8bddd7e15e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCInstrInfo llvm::PPCSubtarget::InstrInfo</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#a8d4c954967e0e3b24114ed438446cf22">getInstrInfo</a> and <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>

</div>
</div>

### InstrItins {#a556a987e65c2ba607b0bd95b9addc794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrItineraryData llvm::PPCSubtarget::InstrItins</td>
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

<p>Selected instruction itineraries (one entry per itinerary class.)</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#a702223f397ca63948ec6596c70339c18">getInstrItineraryData</a>.</p>

</div>
</div>

### InstSelector {#a0536561eb82f66bd686edc267b707da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InstructionSelector&gt; llvm::PPCSubtarget::InstSelector</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#a7c3b235492fe91efccbadef1ef5b1f0b">getInstructionSelector</a> and <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>

</div>
</div>

### IsLittleEndian {#a033667dfabbb37781612b299275b2cd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::IsLittleEndian</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#ab9ff1051f03e5d6cb2ab582a0ff90409">isLittleEndian</a> and <a href="#a4cfcf444385eba48f1f603ef34960733">isXRaySupported</a>.</p>

</div>
</div>

### IsPPC64 {#afe1a03cb47163239bf6af7300a56f47a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCSubtarget::IsPPC64</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#af2f4a081a9b592223710411a8365bd7b">descriptorEnvironmentPointerOffset</a>, <a href="#a359e26a7b0adfd51f672f641ee8abaad">descriptorTOCAnchorOffset</a>, <a href="#a83ffd45d02f1a8d9920e4508c5ec0970">getEnvironmentPointerRegister</a>, <a href="#ac3d33dfd2b7568f38f08c7e6a60496b6">getStackPointerRegister</a>, <a href="#a994ad0d5f0a6e9204731109727cbee4e">getThreadPointerRegister</a>, <a href="#ac1ff4a166a708dddd7c3df1d2fac540f">getTOCPointerRegister</a>, <a href="#a4cfcf444385eba48f1f603ef34960733">isXRaySupported</a> and <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>

</div>
</div>

### Legalizer {#a15a2cf75558dd706b0e1220972c7ea0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LegalizerInfo&gt; llvm::PPCSubtarget::Legalizer</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#a4331a66b57da79a5818926b746854508">getLegalizerInfo</a> and <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>

</div>
</div>

### RegBankInfo {#a47f84c3ba6bace6ecc50e2eb96bdbea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;RegisterBankInfo&gt; llvm::PPCSubtarget::RegBankInfo</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#aed509f888e5ce6fbfa3af691724d701d">getRegBankInfo</a> and <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>

</div>
</div>

### StackAlignment {#a5615780de41c907a7b5b48d1f3b94e15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::PPCSubtarget::StackAlignment</td>
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

<p>stackAlignment - The minimum alignment known to hold of the stack frame on entry to the function and which must be maintained by every function.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#acf53e983185d3f9a87ecfd9a898a1e18">getStackAlignment</a>.</p>

</div>
</div>

### TargetTriple {#a42143f998fef45d515043b7d47249db2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::PPCSubtarget::TargetTriple</td>
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

<p>TargetTriple - What processor and OS we're targeting.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#af28c6e546f92baadcbc2aaa5a155324d">getTargetTriple</a>, <a href="#a3ff0ba05eddb8771ac2f2ff7e56aa054">isAIXABI</a>, <a href="#ac3448d554a511f9338fe66a7ea5cede4">isTargetELF</a>, <a href="#abadbfa907a7aadce4c75b1191aed2260">isTargetLinux</a>, <a href="#a3764752b29e761af740311eac0b1021c">isTargetMachO</a> and <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>

</div>
</div>

### TLInfo {#a16ca38e98ae387775c7fda7da2b26d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCTargetLowering llvm::PPCSubtarget::TLInfo</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#a6c9ac5a1dc657c32bc2999b98bcd7a6b">getTargetLowering</a> and <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>

</div>
</div>

### TM {#ae2ea016ce9b29b6f90eb058aedceca4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCTargetMachine&amp; llvm::PPCSubtarget::TM</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#ad1da03c90232fadc79f4c8d041bbce56">getCodeModel</a>, <a href="#ae11f695a5e7b6ec5a3c360ecc426ba45">getTargetMachine</a>, <a href="#ad49c3ce74dc865eec4728be0850a7697">isELFv2ABI</a>, <a href="#af216ae10b12114faf1ddde74d3520cf0">isGVIndirectSymbol</a>, <a href="#a6622b99b3c00a3938d969957312b1b52">isPPC64</a> and <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>

</div>
</div>

### TSInfo {#ae705899524cc9dc65eb8e90be1c342ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const SelectionDAGTargetInfo&gt; llvm::PPCSubtarget::TSInfo</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>.</p>


<p>Referenced by <a href="#ac9d91d08c3f6f73b6043b32e25da222c">getSelectionDAGInfo</a> and <a href="#ae14557250e6afc406b994fd40e8f5f93">PPCSubtarget</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-cpp">PPCSubtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
