---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/binaryformat/macho-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MachO.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">llvm/TargetParser/ARMTargetParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae86e82720723217878cee426edacb5ce">MachO::CPUSubTypeX86</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2795e9e8f31615e0bd69cc7485c80861">getX86SubType</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35d">MachO::CPUSubTypeARM</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad60ed7d48a4a7dafb34ee44c9554af94">getARMSubType</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac1c361fc17a664c6c8eb2deb666a495a">MachO::CPUSubTypeARM64</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50d443e79e90cfb8e996bb713142c6e6">getARM64SubType</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a912c7d3d71ff10e3710dae142cf2e129">MachO::CPUSubTypePowerPC</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84d6883e3a42d7120d26c5a5611c8b94">getPowerPCSubType</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a923abcc65272bfe81c0e7081c32421">unsupported</a> (const char *Str, const Triple &amp;T)</td>
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

### getARM64SubType() {#a50d443e79e90cfb8e996bb713142c6e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::CPUSubTypeARM64 getARM64SubType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/macho-cpp">MachO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac55ffefe5905580a4f7bad9c73250482a4e2da395b7669ab4b4b61c91d59430a0">llvm::MachO::CPU_SUBTYPE_ARM64_32_V8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac1c361fc17a664c6c8eb2deb666a495aa8520fa7ada41507bd9affc1763435e2e">llvm::MachO::CPU_SUBTYPE_ARM64_ALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac1c361fc17a664c6c8eb2deb666a495aa371e02a5be76919ad4f0176d3c81a223">llvm::MachO::CPU_SUBTYPE_ARM64E</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3f499fbedb1116d9243b169e32f12367">llvm::MachO::getCPUSubType</a>.</p>

</div>
</div>

### getARMSubType() {#ad60ed7d48a4a7dafb34ee44c9554af94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::CPUSubTypeARM getARMSubType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/macho-cpp">MachO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35daff65a2a2e4c45b92bef46ef737af0250">llvm::MachO::CPU_SUBTYPE_ARM_V4T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da9bdef15280a091b727b5777a5d79f406">llvm::MachO::CPU_SUBTYPE_ARM_V5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da561b67be1fb77d9eff6a5a3beaecd95d">llvm::MachO::CPU_SUBTYPE_ARM_V6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da99a7d8c3d13be67ffdbe24f8a0f7cf0c">llvm::MachO::CPU_SUBTYPE_ARM_V6M</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da0c055c23e0811aa0db0d6d53060a5b89">llvm::MachO::CPU_SUBTYPE_ARM_V7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35dac2e49349f0163fe1f71a1ded22e3f49a">llvm::MachO::CPU_SUBTYPE_ARM_V7EM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da924279e3d69d7d0cbdebe029eecc11ed">llvm::MachO::CPU_SUBTYPE_ARM_V7K</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da52697bfd7c14e98a528e53a1fbdea33c">llvm::MachO::CPU_SUBTYPE_ARM_V7M</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35daf84be5758df808a4722cde3519645725">llvm::MachO::CPU_SUBTYPE_ARM_V7S</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a75e18d4bc8fef7e89c1222c6b6cf8638">llvm::ARM::parseArch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3f499fbedb1116d9243b169e32f12367">llvm::MachO::getCPUSubType</a>.</p>

</div>
</div>

### getPowerPCSubType() {#a84d6883e3a42d7120d26c5a5611c8b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::CPUSubTypePowerPC getPowerPCSubType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/macho-cpp">MachO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a912c7d3d71ff10e3710dae142cf2e129abe6e563133c3b815b0bdd18f34f1b699">llvm::MachO::CPU_SUBTYPE_POWERPC_ALL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3f499fbedb1116d9243b169e32f12367">llvm::MachO::getCPUSubType</a>.</p>

</div>
</div>

### getX86SubType() {#a2795e9e8f31615e0bd69cc7485c80861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::CPUSubTypeX86 getX86SubType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/macho-cpp">MachO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae86e82720723217878cee426edacb5cea4560b8aea1445b3cdd6382b7f9d637ae">llvm::MachO::CPU_SUBTYPE_I386_ALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae86e82720723217878cee426edacb5ceaa924bb600517a47108514a58b30e9df1">llvm::MachO::CPU_SUBTYPE_X86_64_ALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae86e82720723217878cee426edacb5cea77d4de2bbc7e17e45a135907d3772e93">llvm::MachO::CPU_SUBTYPE_X86_64_H</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3f499fbedb1116d9243b169e32f12367">llvm::MachO::getCPUSubType</a>.</p>

</div>
</div>

### unsupported() {#a1a923abcc65272bfe81c0e7081c32421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error unsupported (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/macho-cpp">MachO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3f499fbedb1116d9243b169e32f12367">llvm::MachO::getCPUSubType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ada5bfd87ed7d3e85e1447626b2692055">llvm::MachO::getCPUType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ae94b800d0b8c1e3423be89c87d447c9c">llvm::WebAssembly::getLibcallSignature</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
