---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/simachinefunctioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SIMachineFunctionInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::SIMachineFunctionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">Target/AMDGPU/SIMachineFunctionInfo.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">MachineFunctionInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets should override this in a way that mirrors the implementation of <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">llvm::MachineFunctionInfo</a>. <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a801175ec17220ad7c2f309838f0a50d9">SIMachineFunctionInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a> (const llvm::SIMachineFunctionInfo &amp;, const TargetRegisterInfo &amp;TRI, const llvm::MachineFunction &amp;MF)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4f64140db0e08c5cc8f9d184491692c">~SIMachineFunctionInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8c34767559d35589eac9a47ffbe217d">mappingImpl</a> (yaml::IO &amp;YamlIO) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8888b91100f58ca964bebf56c5f7250a">ExplicitKernArgSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74959e0e9a215d043a54ab005c63d1a0">MaxKernArgAlign</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a016a817ed7bffc76e08a31542f4a02">LDSSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58c4552ea5abaeade68a9eed8f2a2bec">GDSSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ce6322058842a2f550cdece7f45a460">DynLDSAlign</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf97495a98d0664ad5d57a3c99d00e0">IsEntryFunction</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade91b18e31b6fd06c7e00178ae87b860">IsChainFunction</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab940a796f6bef2ca14da9145fd48cbd2">NoSignedZerosFPMath</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a54cebc219a0ce5b9b3b01976f11c91">MemoryBound</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac7d3705f692ab4c299ae91d0573836">WaveLimiter</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18dad3d1a8b82fd293a5af59a4f3138b">HasSpilledSGPRs</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fb0fa814e38acce0fb19fd57fcd7d3c">HasSpilledVGPRs</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a474d30e4754bc67ab1d1e8965549175f">HighBitsOf32BitAddress</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c09f1ebbd201f3dabed263f9247b72b">Occupancy</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee024587ab03348def87a3e3923fd5c9">SpillPhysVGPRS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e7d99cf6836e2e91f35895642a4772b">WWMReservedRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae943f235ffb0ac6224181bc5d3b213">ScratchRSrcReg</a> = "$private_rsrc_reg"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820d8ccceda9b8f7790330579694ef91">FrameOffsetReg</a> = "$fp_reg"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afba5cd76321da56b47ddaf51c4727576">StackPtrOffsetReg</a> = "$sp_reg"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5a050a54628c01ef397d4485baef00b">BytesInStackArgArea</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a219de208b06027b5835065d3daddc914">ReturnsVoid</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/siargumentinfo">SIArgumentInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae201cd41bc4b333606be1bbb656c1333">ArgInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed4fbd12c37494064fe27c4882ff4db">PSInputAddr</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7035afa4e12bf0a99755e4da56adbbf3">PSInputEnable</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ec65506d35ef9a0bff8486d67e5963">MaxMemoryClusterDWords</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#abe41cc313a9e7bcb8b71d428f64fb3a8">DefaultMemoryClusterDWordsLimit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/simode">SIMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade7132a796d315b462bdc59fb10d3a99">Mode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/frameindex">FrameIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b0a37d098278019f07649dc270bb02">ScavengeFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc4e12fe2a000305ad25837db0d188f5">VGPRForAGPRCopy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11b88b42beff3cee85a89eb7e5d3dfd3">SGPRForEXECCopy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8567716d726b82e9ea28bdf407454514">LongBranchReservedReg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfffa2c248385b2fec7ee03ba4d052ae">HasInitWholeWave</a> = false</td>
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


<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIMachineFunctionInfo() {#a801175ec17220ad7c2f309838f0a50d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::SIMachineFunctionInfo::SIMachineFunctionInfo ()</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### SIMachineFunctionInfo() {#a80f6630b845109786f0840f4b15737f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::SIMachineFunctionInfo::SIMachineFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo">llvm::SIMachineFunctionInfo</a> &amp; MFI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">llvm::MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>, definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp">SIMachineFunctionInfo.cpp</a>.</p>


<p>References <a href="#ae201cd41bc4b333606be1bbb656c1333">ArgInfo</a>, <a href="#af5a050a54628c01ef397d4485baef00b">BytesInStackArgArea</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a7bc60d756c70f47b2a9a048c5b4cefa5">convertArgumentInfo</a>, <a href="#a2ce6322058842a2f550cdece7f45a460">DynLDSAlign</a>, <a href="#a8888b91100f58ca964bebf56c5f7250a">ExplicitKernArgSize</a>, <a href="#a820d8ccceda9b8f7790330579694ef91">FrameOffsetReg</a>, <a href="#a58c4552ea5abaeade68a9eed8f2a2bec">GDSSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a21318dc0d2ad096d488aa3bfe4248c68">llvm::SIMachineFunctionInfo::getLongBranchReservedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#acefddad7e2601c9f8f1649158d67ccd7">llvm::SIMachineFunctionInfo::getOptionalScavengeFI</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a62da22e6fbef4231a8fb45ae9aaf147c">llvm::SIMachineFunctionInfo::getSGPRForEXECCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a3b1d94e812bf12f6a4fc4c15f5ba7dbd">llvm::SIMachineFunctionInfo::getSGPRSpillPhysVGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a7f30f9a28894281de1c9f3d039eaa75f">llvm::SIMachineFunctionInfo::getVGPRForAGPRCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ac90363de2bb9275d5c5939845d1cd5f6">llvm::SIMachineFunctionInfo::getWWMReservedRegs</a>, <a href="#adfffa2c248385b2fec7ee03ba4d052ae">HasInitWholeWave</a>, <a href="#a18dad3d1a8b82fd293a5af59a4f3138b">HasSpilledSGPRs</a>, <a href="#a0fb0fa814e38acce0fb19fd57fcd7d3c">HasSpilledVGPRs</a>, <a href="#a474d30e4754bc67ab1d1e8965549175f">HighBitsOf32BitAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="#abcf97495a98d0664ad5d57a3c99d00e0">IsEntryFunction</a>, <a href="#a8a016a817ed7bffc76e08a31542f4a02">LDSSize</a>, <a href="#a8567716d726b82e9ea28bdf407454514">LongBranchReservedReg</a>, <a href="#a74959e0e9a215d043a54ab005c63d1a0">MaxKernArgAlign</a>, <a href="#a06ec65506d35ef9a0bff8486d67e5963">MaxMemoryClusterDWords</a>, <a href="#a5a54cebc219a0ce5b9b3b01976f11c91">MemoryBound</a>, <a href="#ade7132a796d315b462bdc59fb10d3a99">Mode</a>, <a href="#ab940a796f6bef2ca14da9145fd48cbd2">NoSignedZerosFPMath</a>, <a href="#a6c09f1ebbd201f3dabed263f9247b72b">Occupancy</a>, <a href="#a8ed4fbd12c37494064fe27c4882ff4db">PSInputAddr</a>, <a href="#a7035afa4e12bf0a99755e4da56adbbf3">PSInputEnable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#ac18edb1d91090c7614b8fcd4dc45d532">regToString</a>, <a href="#a219de208b06027b5835065d3daddc914">ReturnsVoid</a>, <a href="#af3b0a37d098278019f07649dc270bb02">ScavengeFI</a>, <a href="#afae943f235ffb0ac6224181bc5d3b213">ScratchRSrcReg</a>, <a href="#a11b88b42beff3cee85a89eb7e5d3dfd3">SGPRForEXECCopy</a>, <a href="#aee024587ab03348def87a3e3923fd5c9">SpillPhysVGPRS</a>, <a href="#afba5cd76321da56b47ddaf51c4727576">StackPtrOffsetReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="#adc4e12fe2a000305ad25837db0d188f5">VGPRForAGPRCopy</a>, <a href="#a8ac7d3705f692ab4c299ae91d0573836">WaveLimiter</a> and <a href="#a2e7d99cf6836e2e91f35895642a4772b">WWMReservedRegs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SIMachineFunctionInfo() {#ab4f64140db0e08c5cc8f9d184491692c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::SIMachineFunctionInfo::~SIMachineFunctionInfo ()</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### mappingImpl() {#aa8c34767559d35589eac9a47ffbe217d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void yaml::SIMachineFunctionInfo::mappingImpl (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">yaml::IO</a> &amp; YamlIO)</td>
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



<p>Declaration at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>, definition at line 737 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp">SIMachineFunctionInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ArgInfo {#ae201cd41bc4b333606be1bbb656c1333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;SIArgumentInfo&gt; llvm::yaml::SIMachineFunctionInfo::ArgInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### BytesInStackArgArea {#af5a050a54628c01ef397d4485baef00b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::SIMachineFunctionInfo::BytesInStackArgArea = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### DynLDSAlign {#a2ce6322058842a2f550cdece7f45a460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::yaml::SIMachineFunctionInfo::DynLDSAlign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### ExplicitKernArgSize {#a8888b91100f58ca964bebf56c5f7250a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::yaml::SIMachineFunctionInfo::ExplicitKernArgSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### FrameOffsetReg {#a820d8ccceda9b8f7790330579694ef91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringValue llvm::yaml::SIMachineFunctionInfo::FrameOffsetReg = "$fp_reg"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### GDSSize {#a58c4552ea5abaeade68a9eed8f2a2bec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::yaml::SIMachineFunctionInfo::GDSSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### HasInitWholeWave {#adfffa2c248385b2fec7ee03ba4d052ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::SIMachineFunctionInfo::HasInitWholeWave = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### HasSpilledSGPRs {#a18dad3d1a8b82fd293a5af59a4f3138b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::SIMachineFunctionInfo::HasSpilledSGPRs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### HasSpilledVGPRs {#a0fb0fa814e38acce0fb19fd57fcd7d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::SIMachineFunctionInfo::HasSpilledVGPRs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### HighBitsOf32BitAddress {#a474d30e4754bc67ab1d1e8965549175f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::yaml::SIMachineFunctionInfo::HighBitsOf32BitAddress = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### IsChainFunction {#ade91b18e31b6fd06c7e00178ae87b860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::SIMachineFunctionInfo::IsChainFunction = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>.</p>

</div>
</div>

### IsEntryFunction {#abcf97495a98d0664ad5d57a3c99d00e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::SIMachineFunctionInfo::IsEntryFunction = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### LDSSize {#a8a016a817ed7bffc76e08a31542f4a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::yaml::SIMachineFunctionInfo::LDSSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### LongBranchReservedReg {#a8567716d726b82e9ea28bdf407454514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringValue llvm::yaml::SIMachineFunctionInfo::LongBranchReservedReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### MaxKernArgAlign {#a74959e0e9a215d043a54ab005c63d1a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::yaml::SIMachineFunctionInfo::MaxKernArgAlign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### MaxMemoryClusterDWords {#a06ec65506d35ef9a0bff8486d67e5963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::SIMachineFunctionInfo::MaxMemoryClusterDWords = <a href="/web-llvm/docs/api/namespaces/llvm/#abe41cc313a9e7bcb8b71d428f64fb3a8">DefaultMemoryClusterDWordsLimit</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### MemoryBound {#a5a54cebc219a0ce5b9b3b01976f11c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::SIMachineFunctionInfo::MemoryBound = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### Mode {#ade7132a796d315b462bdc59fb10d3a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIMode llvm::yaml::SIMachineFunctionInfo::Mode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### NoSignedZerosFPMath {#ab940a796f6bef2ca14da9145fd48cbd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::SIMachineFunctionInfo::NoSignedZerosFPMath = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### Occupancy {#a6c09f1ebbd201f3dabed263f9247b72b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::SIMachineFunctionInfo::Occupancy = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### PSInputAddr {#a8ed4fbd12c37494064fe27c4882ff4db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::SIMachineFunctionInfo::PSInputAddr = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### PSInputEnable {#a7035afa4e12bf0a99755e4da56adbbf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::SIMachineFunctionInfo::PSInputEnable = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### ReturnsVoid {#a219de208b06027b5835065d3daddc914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::SIMachineFunctionInfo::ReturnsVoid = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### ScavengeFI {#af3b0a37d098278019f07649dc270bb02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;FrameIndex&gt; llvm::yaml::SIMachineFunctionInfo::ScavengeFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### ScratchRSrcReg {#afae943f235ffb0ac6224181bc5d3b213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringValue llvm::yaml::SIMachineFunctionInfo::ScratchRSrcReg = "$private_rsrc_reg"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### SGPRForEXECCopy {#a11b88b42beff3cee85a89eb7e5d3dfd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringValue llvm::yaml::SIMachineFunctionInfo::SGPRForEXECCopy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### SpillPhysVGPRS {#aee024587ab03348def87a3e3923fd5c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StringValue, 2&gt; llvm::yaml::SIMachineFunctionInfo::SpillPhysVGPRS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### StackPtrOffsetReg {#afba5cd76321da56b47ddaf51c4727576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringValue llvm::yaml::SIMachineFunctionInfo::StackPtrOffsetReg = "$sp_reg"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### VGPRForAGPRCopy {#adc4e12fe2a000305ad25837db0d188f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringValue llvm::yaml::SIMachineFunctionInfo::VGPRForAGPRCopy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### WaveLimiter {#a8ac7d3705f692ab4c299ae91d0573836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::SIMachineFunctionInfo::WaveLimiter = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

### WWMReservedRegs {#a2e7d99cf6836e2e91f35895642a4772b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StringValue&gt; llvm::yaml::SIMachineFunctionInfo::WWMReservedRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#a80f6630b845109786f0840f4b15737f9">SIMachineFunctionInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp">SIMachineFunctionInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
