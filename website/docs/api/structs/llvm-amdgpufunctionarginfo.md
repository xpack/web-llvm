---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/amdgpufunctionarginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AMDGPUFunctionArgInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::AMDGPUFunctionArgInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">Target/AMDGPU/AMDGPUArgumentUsageInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PreloadedValue { <a href="#a0e789059bf7f286b7f6bc75b43aac98b">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> (PreloadedValue Value) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15c9948424096818cda93327de8345a8">PrivateSegmentBuffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8d1371d868ed5faaea7710aced1eff">DispatchPtr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf94e49aaa7a9c033bb73e45f3d491c2">QueuePtr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0303f30b08e804220730feac44a5880">KernargSegmentPtr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42381ce8015f81db8cf591030d5e5863">DispatchID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade04e61f515d6522a4f300c88bea66d6">FlatScratchInit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3efcfd6546ab809d0d133983190eaff8">PrivateSegmentSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9202294e9cdcac74422aabd2c041c1e9">LDSKernelId</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd191e63ef0aa2a01dd831061eef82ce">WorkGroupIDX</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a161c5fd1ec307e6a2ee486cb085d2fbf">WorkGroupIDY</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21dd05fd0635d96f9ec6aeb2581cfc50">WorkGroupIDZ</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6918593b5d70a5a1779e27e3bb6ad20c">WorkGroupInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62ee299b4c716abdc806cd12ff8cd007">PrivateSegmentWaveByteOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4367370c92803e2cf72ee3bc26f97520">ImplicitArgPtr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae747b1bb20161699442a10c32d1c83fc">ImplicitBufferPtr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada579eecd637ec5006a3bd6528b4bcc5">WorkItemIDX</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89c7432158b2f308f29bd9d024990df0">WorkItemIDY</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2845dd7c699ffbb46fc6e809ffd2e4">WorkItemIDZ</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; int, <a href="/web-llvm/docs/api/structs/llvm/kernargpreloaddescriptor">KernArgPreloadDescriptor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e8511077fed4363dbb6c5c903755ef8">PreloadKernArgs</a> {}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc1267566eec79cac38172a2baa1dea">FirstKernArgPreloadReg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo">AMDGPUFunctionArgInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a> ()</td>
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


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### PreloadedValue {#a0e789059bf7f286b7f6bc75b43aac98b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPUFunctionArgInfo::PreloadedValue </td>
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
<td class="doxyEnumItemName">PRIVATE_SEGMENT_BUFFER<a id="a0e789059bf7f286b7f6bc75b43aac98ba990374da2e8488b7c90d6240e1ae4221"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DISPATCH_PTR<a id="a0e789059bf7f286b7f6bc75b43aac98bac637a232c5c5f79fa806ae4958a1ff2a"></a></td>
<td class="doxyEnumItemDescription"> (=  1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QUEUE_PTR<a id="a0e789059bf7f286b7f6bc75b43aac98ba32b5333e2f708d7eeb05c12e415b8fd4"></a></td>
<td class="doxyEnumItemDescription"> (=  2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KERNARG_SEGMENT_PTR<a id="a0e789059bf7f286b7f6bc75b43aac98baf32f3fd30ae548866dc7e45092dd90b9"></a></td>
<td class="doxyEnumItemDescription"> (=  3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DISPATCH_ID<a id="a0e789059bf7f286b7f6bc75b43aac98bab51517a3febb0cdc35645334784ff805"></a></td>
<td class="doxyEnumItemDescription"> (=  4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLAT_SCRATCH_INIT<a id="a0e789059bf7f286b7f6bc75b43aac98ba7b4ae3d31a869dd6e77c67f6dc699af6"></a></td>
<td class="doxyEnumItemDescription"> (=  5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDS_KERNEL_ID<a id="a0e789059bf7f286b7f6bc75b43aac98ba20d047732dd4b74606c9c63280727fa3"></a></td>
<td class="doxyEnumItemDescription"> (=  6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WORKGROUP_ID_X<a id="a0e789059bf7f286b7f6bc75b43aac98bac8cd3961f0697f74c890c302ff8cd370"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WORKGROUP_ID_Y<a id="a0e789059bf7f286b7f6bc75b43aac98ba9df85a25300bb504ac893643b387629b"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WORKGROUP_ID_Z<a id="a0e789059bf7f286b7f6bc75b43aac98baf438f1c55b41dc280fcc1d3455a5c741"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRIVATE_SEGMENT_WAVE_BYTE_OFFSET<a id="a0e789059bf7f286b7f6bc75b43aac98ba7f015ffded1a159136f6691743e7aaaa"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IMPLICIT_BUFFER_PTR<a id="a0e789059bf7f286b7f6bc75b43aac98bacc30be6da6e4621e76201b6ee1b7d2ac"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IMPLICIT_ARG_PTR<a id="a0e789059bf7f286b7f6bc75b43aac98ba42b0ab73a3671c39fa2798ffe9e80747"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRIVATE_SEGMENT_SIZE<a id="a0e789059bf7f286b7f6bc75b43aac98baf6cba89e1686dfa5ed96cbe24af65116"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WORKITEM_ID_X<a id="a0e789059bf7f286b7f6bc75b43aac98baed4ee8d30a77bb954964f9910e8cdcb6"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WORKITEM_ID_Y<a id="a0e789059bf7f286b7f6bc75b43aac98ba99b2fc1acb49563d2e3ad89278385103"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WORKITEM_ID_Z<a id="a0e789059bf7f286b7f6bc75b43aac98baeefc8c0370c3704fada7f546da0b6086"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_VGPR_VALUE<a id="a0e789059bf7f286b7f6bc75b43aac98ba448b1e94c57e20239995c2e4dacea852"></a></td>
<td class="doxyEnumItemDescription"> (= WORKITEM_ID_X)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPreloadedValue() {#a9ccdd07da05e067c1e31356005bb39b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; const ArgDescriptor *, const TargetRegisterClass *, LLT &gt; AMDGPUFunctionArgInfo::getPreloadedValue (<a href="#a0e789059bf7f286b7f6bc75b43aac98b">PreloadedValue</a> Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-cpp">AMDGPUArgumentUsageInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aa6d3112da64eecbdbb50aacb5f8251e8">llvm::AMDGPUAS::CONSTANT_ADDRESS</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98bab51517a3febb0cdc35645334784ff805">DISPATCH_ID</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98bac637a232c5c5f79fa806ae4958a1ff2a">DISPATCH_PTR</a>, <a href="#a42381ce8015f81db8cf591030d5e5863">DispatchID</a>, <a href="#ade8d1371d868ed5faaea7710aced1eff">DispatchPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98ba7b4ae3d31a869dd6e77c67f6dc699af6">FLAT_SCRATCH_INIT</a>, <a href="#ade04e61f515d6522a4f300c88bea66d6">FlatScratchInit</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98ba42b0ab73a3671c39fa2798ffe9e80747">IMPLICIT_ARG_PTR</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98bacc30be6da6e4621e76201b6ee1b7d2ac">IMPLICIT_BUFFER_PTR</a>, <a href="#a4367370c92803e2cf72ee3bc26f97520">ImplicitArgPtr</a>, <a href="#ae747b1bb20161699442a10c32d1c83fc">ImplicitBufferPtr</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98baf32f3fd30ae548866dc7e45092dd90b9">KERNARG_SEGMENT_PTR</a>, <a href="#ab0303f30b08e804220730feac44a5880">KernargSegmentPtr</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98ba20d047732dd4b74606c9c63280727fa3">LDS_KERNEL_ID</a>, <a href="#a9202294e9cdcac74422aabd2c041c1e9">LDSKernelId</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98ba990374da2e8488b7c90d6240e1ae4221">PRIVATE_SEGMENT_BUFFER</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98baf6cba89e1686dfa5ed96cbe24af65116">PRIVATE_SEGMENT_SIZE</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98ba7f015ffded1a159136f6691743e7aaaa">PRIVATE_SEGMENT_WAVE_BYTE_OFFSET</a>, <a href="#a15c9948424096818cda93327de8345a8">PrivateSegmentBuffer</a>, <a href="#a3efcfd6546ab809d0d133983190eaff8">PrivateSegmentSize</a>, <a href="#a62ee299b4c716abdc806cd12ff8cd007">PrivateSegmentWaveByteOffset</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98ba32b5333e2f708d7eeb05c12e415b8fd4">QUEUE_PTR</a>, <a href="#aaf94e49aaa7a9c033bb73e45f3d491c2">QueuePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98bac8cd3961f0697f74c890c302ff8cd370">WORKGROUP_ID_X</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98ba9df85a25300bb504ac893643b387629b">WORKGROUP_ID_Y</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98baf438f1c55b41dc280fcc1d3455a5c741">WORKGROUP_ID_Z</a>, <a href="#afd191e63ef0aa2a01dd831061eef82ce">WorkGroupIDX</a>, <a href="#a161c5fd1ec307e6a2ee486cb085d2fbf">WorkGroupIDY</a>, <a href="#a21dd05fd0635d96f9ec6aeb2581cfc50">WorkGroupIDZ</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98baed4ee8d30a77bb954964f9910e8cdcb6">WORKITEM_ID_X</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98ba99b2fc1acb49563d2e3ad89278385103">WORKITEM_ID_Y</a>, <a href="#a0e789059bf7f286b7f6bc75b43aac98baeefc8c0370c3704fada7f546da0b6086">WORKITEM_ID_Z</a>, <a href="#ada579eecd637ec5006a3bd6528b4bcc5">WorkItemIDX</a>, <a href="#a89c7432158b2f308f29bd9d024990df0">WorkItemIDY</a> and <a href="#a6a2845dd7c699ffbb46fc6e809ffd2e4">WorkItemIDZ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DispatchID {#a42381ce8015f81db8cf591030d5e5863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::DispatchID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a>, <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### DispatchPtr {#ade8d1371d868ed5faaea7710aced1eff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::DispatchPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a>, <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### FirstKernArgPreloadReg {#aebc1267566eec79cac38172a2baa1dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::AMDGPUFunctionArgInfo::FirstKernArgPreloadReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>

</div>
</div>

### FlatScratchInit {#ade04e61f515d6522a4f300c88bea66d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::FlatScratchInit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### ImplicitArgPtr {#a4367370c92803e2cf72ee3bc26f97520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::ImplicitArgPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a>, <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### ImplicitBufferPtr {#ae747b1bb20161699442a10c32d1c83fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::ImplicitBufferPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### KernargSegmentPtr {#ab0303f30b08e804220730feac44a5880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::KernargSegmentPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### LDSKernelId {#a9202294e9cdcac74422aabd2c041c1e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::LDSKernelId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a>, <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### PreloadKernArgs {#a4e8511077fed4363dbb6c5c903755ef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;int, KernArgPreloadDescriptor&gt; llvm::AMDGPUFunctionArgInfo::PreloadKernArgs {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>

</div>
</div>

### PrivateSegmentBuffer {#a15c9948424096818cda93327de8345a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::PrivateSegmentBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a>, <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### PrivateSegmentSize {#a3efcfd6546ab809d0d133983190eaff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::PrivateSegmentSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### PrivateSegmentWaveByteOffset {#a62ee299b4c716abdc806cd12ff8cd007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::PrivateSegmentWaveByteOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### QueuePtr {#aaf94e49aaa7a9c033bb73e45f3d491c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::QueuePtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a>, <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### WorkGroupIDX {#afd191e63ef0aa2a01dd831061eef82ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::WorkGroupIDX</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a>, <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### WorkGroupIDY {#a161c5fd1ec307e6a2ee486cb085d2fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::WorkGroupIDY</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a>, <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### WorkGroupIDZ {#a21dd05fd0635d96f9ec6aeb2581cfc50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::WorkGroupIDZ</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a>, <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### WorkGroupInfo {#a6918593b5d70a5a1779e27e3bb6ad20c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::WorkGroupInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### WorkItemIDX {#ada579eecd637ec5006a3bd6528b4bcc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::WorkItemIDX</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a>, <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>.</p>

</div>
</div>

### WorkItemIDY {#a89c7432158b2f308f29bd9d024990df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::WorkItemIDY</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a>, <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>.</p>

</div>
</div>

### WorkItemIDZ {#a6a2845dd7c699ffbb46fc6e809ffd2e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::AMDGPUFunctionArgInfo::WorkItemIDZ</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#a69667e25bd46f756ca2b9efab35508eb">fixedABILayout</a>, <a href="#a9ccdd07da05e067c1e31356005bb39b0">getPreloadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fixedABILayout() {#a69667e25bd46f756ca2b9efab35508eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUFunctionArgInfo AMDGPUFunctionArgInfo::fixedABILayout ()</td>
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



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-cpp">AMDGPUArgumentUsageInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/argdescriptor/#ab80da72ac9122b5c4e4a0a2cfaa25d9e">llvm::ArgDescriptor::createRegister</a>, <a href="#a42381ce8015f81db8cf591030d5e5863">DispatchID</a>, <a href="#ade8d1371d868ed5faaea7710aced1eff">DispatchPtr</a>, <a href="#a4367370c92803e2cf72ee3bc26f97520">ImplicitArgPtr</a>, <a href="#a9202294e9cdcac74422aabd2c041c1e9">LDSKernelId</a>, <a href="#a15c9948424096818cda93327de8345a8">PrivateSegmentBuffer</a>, <a href="#aaf94e49aaa7a9c033bb73e45f3d491c2">QueuePtr</a>, <a href="#afd191e63ef0aa2a01dd831061eef82ce">WorkGroupIDX</a>, <a href="#a161c5fd1ec307e6a2ee486cb085d2fbf">WorkGroupIDY</a>, <a href="#a21dd05fd0635d96f9ec6aeb2581cfc50">WorkGroupIDZ</a>, <a href="#ada579eecd637ec5006a3bd6528b4bcc5">WorkItemIDX</a>, <a href="#a89c7432158b2f308f29bd9d024990df0">WorkItemIDY</a> and <a href="#a6a2845dd7c699ffbb46fc6e809ffd2e4">WorkItemIDZ</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-cpp">AMDGPUArgumentUsageInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
