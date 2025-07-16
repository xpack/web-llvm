---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sgprspillbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SGPRSpillBuilder` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::SGPRSpillBuilder { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35d6d8a3367d6ef42ec184b84213ea52">SGPRSpillBuilder</a> (const SIRegisterInfo &amp;TRI, const SIInstrInfo &amp;TII, bool IsWave32, MachineBasicBlock::iterator MI, int Index, RegScavenger *RS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a> (const SIRegisterInfo &amp;TRI, const SIInstrInfo &amp;TII, bool IsWave32, MachineBasicBlock::iterator MI, Register Reg, bool IsKill, int Index, RegScavenger *RS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/pervgprdata">PerVGPRData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954666a1d726bbc08a503d36255d694a">getPerVGPRData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7c906625fab2baf872e16248962b859">prepare</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa86a4d647e79dbdeb3d2d43ec301abcd">readWriteTmpVGPR</a> (unsigned Offset, bool IsLoad)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1181ec84c08b8b5aa563db567163a48a">setMI</a> (MachineBasicBlock *NewMBB, MachineBasicBlock::iterator NewMI)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addf4f1853b616359f0800e0792b75e40">SuperReg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa29651d0ae788b6421aaf620050ee9fc">MI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13301cdc7cdfed3dd8f993e0f1b9d359">SplitParts</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a43f1a8fe6945949f7ebaeec8bf9a7">NumSubRegs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f912e4c6f99e1bf50c66ee8fb26ed2a">IsKill</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bcb85b82e6330375b977191fef41e2b">DL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f41f0ca74f2026ead9ed683f10e6b3">TmpVGPR</a> = AMDGPU::NoRegister</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e4b5821346b3350405938b27005449e">TmpVGPRIndex</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14a8c1a800cbdea3d1f0815817a73241">TmpVGPRLive</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae16d5edd44c63fa9b686e5b94b931eb4">SavedExecReg</a> = AMDGPU::NoRegister</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e90539a43522b18b79c504b88d0de69">Index</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff46ff3cb1f469b01f6171c8134934ca">EltSize</a> = 4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56a1d04bcd3219469b87445ae2df358d">RS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad83a7a6b291c68ccc27722290777f333">MBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad37a50e8e31fa920654f835564ec022a">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo">SIMachineFunctionInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aec2625932d694fc229189a21239233">MFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae46fbdc9694bcc2a7e842fbebea72d74">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20f270fc26f8636134d81b8f297d505">TRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dad77acf1d0d82ccf87ce2f27d4ea26">IsWave32</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa489971d1ac1b2f41d39d0d736f79266">ExecReg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f42bfbae88439434bea393b10aaf453">MovOpc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a780ff1cb44df81c9895eb346779f6413">NotOpc</a></td>
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


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SGPRSpillBuilder() {#a35d6d8a3367d6ef42ec184b84213ea52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SGPRSpillBuilder::SGPRSpillBuilder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> &amp; TII, bool IsWave32, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, int Index, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="#a7e90539a43522b18b79c504b88d0de69">Index</a>, <a href="#a3dad77acf1d0d82ccf87ce2f27d4ea26">IsWave32</a>, <a href="#aa29651d0ae788b6421aaf620050ee9fc">MI</a>, <a href="#a56a1d04bcd3219469b87445ae2df358d">RS</a>, <a href="#a35d6d8a3367d6ef42ec184b84213ea52">SGPRSpillBuilder</a>, <a href="#ae46fbdc9694bcc2a7e842fbebea72d74">TII</a> and <a href="#ab20f270fc26f8636134d81b8f297d505">TRI</a>.</p>


<p>Referenced by <a href="#a35d6d8a3367d6ef42ec184b84213ea52">SGPRSpillBuilder</a>.</p>

</div>
</div>

### SGPRSpillBuilder() {#a4a1143f3929f3258aebb54b4bef12082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SGPRSpillBuilder::SGPRSpillBuilder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> &amp; TII, bool IsWave32, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, bool IsKill, int Index, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6bcb85b82e6330375b977191fef41e2b">DL</a>, <a href="#aff46ff3cb1f469b01f6171c8134934ca">EltSize</a>, <a href="#aa489971d1ac1b2f41d39d0d736f79266">ExecReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstrbundle-cpp/#af44c9b089359803924e0b92bea3b6d03">getDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="#a7e90539a43522b18b79c504b88d0de69">Index</a>, <a href="#a4f912e4c6f99e1bf50c66ee8fb26ed2a">IsKill</a>, <a href="#a3dad77acf1d0d82ccf87ce2f27d4ea26">IsWave32</a>, <a href="#ad83a7a6b291c68ccc27722290777f333">MBB</a>, <a href="#ad37a50e8e31fa920654f835564ec022a">MF</a>, <a href="#a1aec2625932d694fc229189a21239233">MFI</a>, <a href="#aa29651d0ae788b6421aaf620050ee9fc">MI</a>, <a href="#a4f42bfbae88439434bea393b10aaf453">MovOpc</a>, <a href="#a780ff1cb44df81c9895eb346779f6413">NotOpc</a>, <a href="#ac7a43f1a8fe6945949f7ebaeec8bf9a7">NumSubRegs</a>, <a href="#a56a1d04bcd3219469b87445ae2df358d">RS</a>, <a href="#a13301cdc7cdfed3dd8f993e0f1b9d359">SplitParts</a>, <a href="#addf4f1853b616359f0800e0792b75e40">SuperReg</a>, <a href="#ae46fbdc9694bcc2a7e842fbebea72d74">TII</a> and <a href="#ab20f270fc26f8636134d81b8f297d505">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPerVGPRData() {#a954666a1d726bbc08a503d36255d694a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerVGPRData llvm::SGPRSpillBuilder::getPerVGPRData ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a3dad77acf1d0d82ccf87ce2f27d4ea26">IsWave32</a> and <a href="#ac7a43f1a8fe6945949f7ebaeec8bf9a7">NumSubRegs</a>.</p>


<p>Referenced by <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### prepare() {#ac7c906625fab2baf872e16248962b859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SGPRSpillBuilder::prepare ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a6bcb85b82e6330375b977191fef41e2b">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a3d3173a10a3471dbb8834bf4933607f6">emitUnsupportedError</a>, <a href="#aa489971d1ac1b2f41d39d0d736f79266">ExecReg</a>, <a href="#a954666a1d726bbc08a503d36255d694a">getPerVGPRData</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="#a3dad77acf1d0d82ccf87ce2f27d4ea26">IsWave32</a>, <a href="#ad83a7a6b291c68ccc27722290777f333">MBB</a>, <a href="#ad37a50e8e31fa920654f835564ec022a">MF</a>, <a href="#a1aec2625932d694fc229189a21239233">MFI</a>, <a href="#aa29651d0ae788b6421aaf620050ee9fc">MI</a>, <a href="#a4f42bfbae88439434bea393b10aaf453">MovOpc</a>, <a href="#a780ff1cb44df81c9895eb346779f6413">NotOpc</a>, <a href="#a56a1d04bcd3219469b87445ae2df358d">RS</a>, <a href="#ae16d5edd44c63fa9b686e5b94b931eb4">SavedExecReg</a>, <a href="#addf4f1853b616359f0800e0792b75e40">SuperReg</a>, <a href="#ae46fbdc9694bcc2a7e842fbebea72d74">TII</a>, <a href="#a25f41f0ca74f2026ead9ed683f10e6b3">TmpVGPR</a>, <a href="#a9e4b5821346b3350405938b27005449e">TmpVGPRIndex</a>, <a href="#a14a8c1a800cbdea3d1f0815817a73241">TmpVGPRLive</a>, <a href="#ab20f270fc26f8636134d81b8f297d505">TRI</a> and <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/pervgprdata/#a2c6d1db9de20d6d2d9378168616e69e7">llvm::SGPRSpillBuilder::PerVGPRData::VGPRLanes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### readWriteTmpVGPR() {#aa86a4d647e79dbdeb3d2d43ec301abcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SGPRSpillBuilder::readWriteTmpVGPR (unsigned Offset, bool IsLoad)</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a6bcb85b82e6330375b977191fef41e2b">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a3d3173a10a3471dbb8834bf4933607f6">emitUnsupportedError</a>, <a href="#aa489971d1ac1b2f41d39d0d736f79266">ExecReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#a7e90539a43522b18b79c504b88d0de69">Index</a>, <a href="#ad83a7a6b291c68ccc27722290777f333">MBB</a>, <a href="#ad37a50e8e31fa920654f835564ec022a">MF</a>, <a href="#aa29651d0ae788b6421aaf620050ee9fc">MI</a>, <a href="#a780ff1cb44df81c9895eb346779f6413">NotOpc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a56a1d04bcd3219469b87445ae2df358d">RS</a>, <a href="#ae16d5edd44c63fa9b686e5b94b931eb4">SavedExecReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a61a42c85bd86c6ca4554e27d33c3f798">llvm::MachineOperand::setIsDead</a>, <a href="#ae46fbdc9694bcc2a7e842fbebea72d74">TII</a> and <a href="#ab20f270fc26f8636134d81b8f297d505">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### restore() {#a941b8646dc54e403a97acfb1ee56d774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SGPRSpillBuilder::restore ()</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a6bcb85b82e6330375b977191fef41e2b">DL</a>, <a href="#aa489971d1ac1b2f41d39d0d736f79266">ExecReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5acff74dc04327bef6824ecb2e3648d0f0">llvm::RegState::ImplicitKill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="#ad83a7a6b291c68ccc27722290777f333">MBB</a>, <a href="#aa29651d0ae788b6421aaf620050ee9fc">MI</a>, <a href="#a4f42bfbae88439434bea393b10aaf453">MovOpc</a>, <a href="#a780ff1cb44df81c9895eb346779f6413">NotOpc</a>, <a href="#a56a1d04bcd3219469b87445ae2df358d">RS</a>, <a href="#ae16d5edd44c63fa9b686e5b94b931eb4">SavedExecReg</a>, <a href="#ae46fbdc9694bcc2a7e842fbebea72d74">TII</a>, <a href="#a25f41f0ca74f2026ead9ed683f10e6b3">TmpVGPR</a>, <a href="#a9e4b5821346b3350405938b27005449e">TmpVGPRIndex</a>, <a href="#a14a8c1a800cbdea3d1f0815817a73241">TmpVGPRLive</a> and <a href="#ab20f270fc26f8636134d81b8f297d505">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### setMI() {#a1181ec84c08b8b5aa563db567163a48a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SGPRSpillBuilder::setMI (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> NewMI)</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad83a7a6b291c68ccc27722290777f333">MBB</a>, <a href="#ad37a50e8e31fa920654f835564ec022a">MF</a> and <a href="#aa29651d0ae788b6421aaf620050ee9fc">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DL {#a6bcb85b82e6330375b977191fef41e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc&amp; llvm::SGPRSpillBuilder::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aee68072e1038a895a2998d78395db856">llvm::SIRegisterInfo::buildVGPRSpillLoadStore</a>, <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#aa86a4d647e79dbdeb3d2d43ec301abcd">readWriteTmpVGPR</a>, <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### EltSize {#aff46ff3cb1f469b01f6171c8134934ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SGPRSpillBuilder::EltSize = 4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aee68072e1038a895a2998d78395db856">llvm::SIRegisterInfo::buildVGPRSpillLoadStore</a> and <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>.</p>

</div>
</div>

### ExecReg {#aa489971d1ac1b2f41d39d0d736f79266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SGPRSpillBuilder::ExecReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#aa86a4d647e79dbdeb3d2d43ec301abcd">readWriteTmpVGPR</a>, <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a> and <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>.</p>

</div>
</div>

### Index {#a7e90539a43522b18b79c504b88d0de69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SGPRSpillBuilder::Index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#aa86a4d647e79dbdeb3d2d43ec301abcd">readWriteTmpVGPR</a>, <a href="#a35d6d8a3367d6ef42ec184b84213ea52">SGPRSpillBuilder</a> and <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>.</p>

</div>
</div>

### IsKill {#a4f912e4c6f99e1bf50c66ee8fb26ed2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SGPRSpillBuilder::IsKill</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### IsWave32 {#a3dad77acf1d0d82ccf87ce2f27d4ea26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SGPRSpillBuilder::IsWave32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#a954666a1d726bbc08a503d36255d694a">getPerVGPRData</a>, <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#a35d6d8a3367d6ef42ec184b84213ea52">SGPRSpillBuilder</a> and <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>.</p>

</div>
</div>

### MBB {#ad83a7a6b291c68ccc27722290777f333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::SGPRSpillBuilder::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aee68072e1038a895a2998d78395db856">llvm::SIRegisterInfo::buildVGPRSpillLoadStore</a>, <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#aa86a4d647e79dbdeb3d2d43ec301abcd">readWriteTmpVGPR</a>, <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="#a1181ec84c08b8b5aa563db567163a48a">setMI</a>, <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### MF {#ad37a50e8e31fa920654f835564ec022a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::SGPRSpillBuilder::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aee68072e1038a895a2998d78395db856">llvm::SIRegisterInfo::buildVGPRSpillLoadStore</a>, <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#aa86a4d647e79dbdeb3d2d43ec301abcd">readWriteTmpVGPR</a>, <a href="#a1181ec84c08b8b5aa563db567163a48a">setMI</a> and <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>.</p>

</div>
</div>

### MFI {#a1aec2625932d694fc229189a21239233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIMachineFunctionInfo&amp; llvm::SGPRSpillBuilder::MFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aee68072e1038a895a2998d78395db856">llvm::SIRegisterInfo::buildVGPRSpillLoadStore</a>, <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### MI {#aa29651d0ae788b6421aaf620050ee9fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::SGPRSpillBuilder::MI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aee68072e1038a895a2998d78395db856">llvm::SIRegisterInfo::buildVGPRSpillLoadStore</a>, <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#aa86a4d647e79dbdeb3d2d43ec301abcd">readWriteTmpVGPR</a>, <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a>, <a href="#a1181ec84c08b8b5aa563db567163a48a">setMI</a>, <a href="#a35d6d8a3367d6ef42ec184b84213ea52">SGPRSpillBuilder</a> and <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>.</p>

</div>
</div>

### MovOpc {#a4f42bfbae88439434bea393b10aaf453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SGPRSpillBuilder::MovOpc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a> and <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>.</p>

</div>
</div>

### NotOpc {#a780ff1cb44df81c9895eb346779f6413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SGPRSpillBuilder::NotOpc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#aa86a4d647e79dbdeb3d2d43ec301abcd">readWriteTmpVGPR</a>, <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a> and <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>.</p>

</div>
</div>

### NumSubRegs {#ac7a43f1a8fe6945949f7ebaeec8bf9a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SGPRSpillBuilder::NumSubRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#a954666a1d726bbc08a503d36255d694a">getPerVGPRData</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### RS {#a56a1d04bcd3219469b87445ae2df358d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegScavenger* llvm::SGPRSpillBuilder::RS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aee68072e1038a895a2998d78395db856">llvm::SIRegisterInfo::buildVGPRSpillLoadStore</a>, <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#aa86a4d647e79dbdeb3d2d43ec301abcd">readWriteTmpVGPR</a>, <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a>, <a href="#a35d6d8a3367d6ef42ec184b84213ea52">SGPRSpillBuilder</a> and <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>.</p>

</div>
</div>

### SavedExecReg {#ae16d5edd44c63fa9b686e5b94b931eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SGPRSpillBuilder::SavedExecReg = AMDGPU::NoRegister</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#aa86a4d647e79dbdeb3d2d43ec301abcd">readWriteTmpVGPR</a> and <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a>.</p>

</div>
</div>

### SplitParts {#a13301cdc7cdfed3dd8f993e0f1b9d359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;int16_t&gt; llvm::SGPRSpillBuilder::SplitParts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### SuperReg {#addf4f1853b616359f0800e0792b75e40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SGPRSpillBuilder::SuperReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### TII {#ae46fbdc9694bcc2a7e842fbebea72d74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo&amp; llvm::SGPRSpillBuilder::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#aa86a4d647e79dbdeb3d2d43ec301abcd">readWriteTmpVGPR</a>, <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="#a35d6d8a3367d6ef42ec184b84213ea52">SGPRSpillBuilder</a>, <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### TmpVGPR {#a25f41f0ca74f2026ead9ed683f10e6b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SGPRSpillBuilder::TmpVGPR = AMDGPU::NoRegister</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aee68072e1038a895a2998d78395db856">llvm::SIRegisterInfo::buildVGPRSpillLoadStore</a>, <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### TmpVGPRIndex {#a9e4b5821346b3350405938b27005449e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SGPRSpillBuilder::TmpVGPRIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#ac7c906625fab2baf872e16248962b859">prepare</a> and <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a>.</p>

</div>
</div>

### TmpVGPRLive {#a14a8c1a800cbdea3d1f0815817a73241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SGPRSpillBuilder::TmpVGPRLive = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#ac7c906625fab2baf872e16248962b859">prepare</a> and <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a>.</p>

</div>
</div>

### TRI {#ab20f270fc26f8636134d81b8f297d505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIRegisterInfo&amp; llvm::SGPRSpillBuilder::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#ac7c906625fab2baf872e16248962b859">prepare</a>, <a href="#aa86a4d647e79dbdeb3d2d43ec301abcd">readWriteTmpVGPR</a>, <a href="#a941b8646dc54e403a97acfb1ee56d774">restore</a>, <a href="#a35d6d8a3367d6ef42ec184b84213ea52">SGPRSpillBuilder</a> and <a href="#a4a1143f3929f3258aebb54b4bef12082">SGPRSpillBuilder</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp">SIRegisterInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
