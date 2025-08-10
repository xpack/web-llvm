---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/amdgpu/waitcnt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Waitcnt` Struct

<p>Represents the counter values to wait for in an s_waitcnt instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AMDGPU::Waitcnt { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">Target/AMDGPU/Utils/AMDGPUBaseInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05967cfb838bbc4800fc2425c9bad2b2">Waitcnt</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab781b6c8e09b89d8210ea3935b54befb">Waitcnt</a> (unsigned VmCnt, unsigned ExpCnt, unsigned LgkmCnt, unsigned VsCnt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a362cf8dbafb61f64a4c404a7d1f5f343">Waitcnt</a> (unsigned LoadCnt, unsigned ExpCnt, unsigned DsCnt, unsigned StoreCnt, unsigned SampleCnt, unsigned BvhCnt, unsigned KmCnt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf31927fa51c731edb3cd3b2d17a8e3">hasWait</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90bde311904c3b06141ba1202d664ea8">hasWaitExceptStoreCnt</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab58ef3859f03f13623e0cd515dc4f72d">hasWaitStoreCnt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/amdgpu/waitcnt">Waitcnt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc6ef6fb828278d2afdcd60500e888a8">combined</a> (const Waitcnt &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23481ee08f5d965c17f65a68266daacf">LoadCnt</a> = ~0u</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ba828f2b59dbcb07106063c09d66fda">ExpCnt</a> = ~0u</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad454e1f63e52c7f9a7f552fc4b81cb00">DsCnt</a> = ~0u</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53a9bc168d637a1e91ae887ec5a41008">StoreCnt</a> = ~0u</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cc5625916faa7a06a912f2582afe42f">SampleCnt</a> = ~0u</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f86c2a317fac87bd19fd4ea0f51ef14">BvhCnt</a> = ~0u</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b6688e66996dd473b77405dbf8ea017">KmCnt</a> = ~0u</td>
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

<p>Represents the counter values to wait for in an s_waitcnt instruction.</p>


<p>Large values (including the maximum possible integer) can be used to represent "don't care" waits.</p>


<p>Definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Waitcnt() {#a05967cfb838bbc4800fc2425c9bad2b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::Waitcnt::Waitcnt ()</td>
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



<p>Definition at line 976 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Referenced by <a href="#abc6ef6fb828278d2afdcd60500e888a8">combined</a>.</p>

</div>
</div>

### Waitcnt() {#ab781b6c8e09b89d8210ea3935b54befb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::Waitcnt::Waitcnt (unsigned VmCnt, unsigned ExpCnt, unsigned LgkmCnt, unsigned VsCnt)</td>
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



<p>Definition at line 978 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>References <a href="#a4f86c2a317fac87bd19fd4ea0f51ef14">BvhCnt</a>, <a href="#ad454e1f63e52c7f9a7f552fc4b81cb00">DsCnt</a>, <a href="#a0ba828f2b59dbcb07106063c09d66fda">ExpCnt</a>, <a href="#a8b6688e66996dd473b77405dbf8ea017">KmCnt</a>, <a href="#a23481ee08f5d965c17f65a68266daacf">LoadCnt</a>, <a href="#a5cc5625916faa7a06a912f2582afe42f">SampleCnt</a> and <a href="#a53a9bc168d637a1e91ae887ec5a41008">StoreCnt</a>.</p>

</div>
</div>

### Waitcnt() {#a362cf8dbafb61f64a4c404a7d1f5f343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::Waitcnt::Waitcnt (unsigned LoadCnt, unsigned ExpCnt, unsigned DsCnt, unsigned StoreCnt, unsigned SampleCnt, unsigned BvhCnt, unsigned KmCnt)</td>
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



<p>Definition at line 983 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>References <a href="#a4f86c2a317fac87bd19fd4ea0f51ef14">BvhCnt</a>, <a href="#ad454e1f63e52c7f9a7f552fc4b81cb00">DsCnt</a>, <a href="#a0ba828f2b59dbcb07106063c09d66fda">ExpCnt</a>, <a href="#a8b6688e66996dd473b77405dbf8ea017">KmCnt</a>, <a href="#a23481ee08f5d965c17f65a68266daacf">LoadCnt</a>, <a href="#a5cc5625916faa7a06a912f2582afe42f">SampleCnt</a> and <a href="#a53a9bc168d637a1e91ae887ec5a41008">StoreCnt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### combined() {#abc6ef6fb828278d2afdcd60500e888a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Waitcnt llvm::AMDGPU::Waitcnt::combined (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/amdgpu/waitcnt">Waitcnt</a> &amp; Other)</td>
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



<p>Definition at line 997 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>References <a href="#a4f86c2a317fac87bd19fd4ea0f51ef14">BvhCnt</a>, <a href="#ad454e1f63e52c7f9a7f552fc4b81cb00">DsCnt</a>, <a href="#a0ba828f2b59dbcb07106063c09d66fda">ExpCnt</a>, <a href="#a8b6688e66996dd473b77405dbf8ea017">KmCnt</a>, <a href="#a23481ee08f5d965c17f65a68266daacf">LoadCnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a5cc5625916faa7a06a912f2582afe42f">SampleCnt</a>, <a href="#a53a9bc168d637a1e91ae887ec5a41008">StoreCnt</a> and <a href="#a05967cfb838bbc4800fc2425c9bad2b2">Waitcnt</a>.</p>

</div>
</div>

### hasWait() {#a4bf31927fa51c731edb3cd3b2d17a8e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::Waitcnt::hasWait ()</td>
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



<p>Definition at line 988 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>References <a href="#a90bde311904c3b06141ba1202d664ea8">hasWaitExceptStoreCnt</a> and <a href="#a53a9bc168d637a1e91ae887ec5a41008">StoreCnt</a>.</p>

</div>
</div>

### hasWaitExceptStoreCnt() {#a90bde311904c3b06141ba1202d664ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::Waitcnt::hasWaitExceptStoreCnt ()</td>
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



<p>Definition at line 990 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>References <a href="#a4f86c2a317fac87bd19fd4ea0f51ef14">BvhCnt</a>, <a href="#ad454e1f63e52c7f9a7f552fc4b81cb00">DsCnt</a>, <a href="#a0ba828f2b59dbcb07106063c09d66fda">ExpCnt</a>, <a href="#a8b6688e66996dd473b77405dbf8ea017">KmCnt</a>, <a href="#a23481ee08f5d965c17f65a68266daacf">LoadCnt</a> and <a href="#a5cc5625916faa7a06a912f2582afe42f">SampleCnt</a>.</p>


<p>Referenced by <a href="#a4bf31927fa51c731edb3cd3b2d17a8e3">hasWait</a>.</p>

</div>
</div>

### hasWaitStoreCnt() {#ab58ef3859f03f13623e0cd515dc4f72d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::Waitcnt::hasWaitStoreCnt ()</td>
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



<p>Definition at line 995 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Reference <a href="#a53a9bc168d637a1e91ae887ec5a41008">StoreCnt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BvhCnt {#a4f86c2a317fac87bd19fd4ea0f51ef14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::Waitcnt::BvhCnt = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Referenced by <a href="#abc6ef6fb828278d2afdcd60500e888a8">combined</a>, <a href="#a90bde311904c3b06141ba1202d664ea8">hasWaitExceptStoreCnt</a>, <a href="#a362cf8dbafb61f64a4c404a7d1f5f343">Waitcnt</a> and <a href="#ab781b6c8e09b89d8210ea3935b54befb">Waitcnt</a>.</p>

</div>
</div>

### DsCnt {#ad454e1f63e52c7f9a7f552fc4b81cb00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::Waitcnt::DsCnt = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 970 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Referenced by <a href="#abc6ef6fb828278d2afdcd60500e888a8">combined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#acbb695160ff3f9804b7c0fe9d1994c6e">llvm::AMDGPU::decodeLoadcntDscnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8e170f06f15d0b3dcab3ca224d8c0400">llvm::AMDGPU::decodeStorecntDscnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5d4a37c23e1caabf8f64de0e64266f3a">llvm::AMDGPU::decodeWaitcnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a37d9f31b140a3e81750b71e13bc916ac">llvm::AMDGPU::encodeLoadcntDscnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ace8ce10585be6e95cc694ee3b72033ae">llvm::AMDGPU::encodeStorecntDscnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f14260fd47f5c55b3d473291b81a302">llvm::AMDGPU::encodeWaitcnt</a>, <a href="#a90bde311904c3b06141ba1202d664ea8">hasWaitExceptStoreCnt</a>, <a href="#a362cf8dbafb61f64a4c404a7d1f5f343">Waitcnt</a> and <a href="#ab781b6c8e09b89d8210ea3935b54befb">Waitcnt</a>.</p>

</div>
</div>

### ExpCnt {#a0ba828f2b59dbcb07106063c09d66fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::Waitcnt::ExpCnt = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Referenced by <a href="#abc6ef6fb828278d2afdcd60500e888a8">combined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5d4a37c23e1caabf8f64de0e64266f3a">llvm::AMDGPU::decodeWaitcnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f14260fd47f5c55b3d473291b81a302">llvm::AMDGPU::encodeWaitcnt</a>, <a href="#a90bde311904c3b06141ba1202d664ea8">hasWaitExceptStoreCnt</a>, <a href="#a362cf8dbafb61f64a4c404a7d1f5f343">Waitcnt</a> and <a href="#ab781b6c8e09b89d8210ea3935b54befb">Waitcnt</a>.</p>

</div>
</div>

### KmCnt {#a8b6688e66996dd473b77405dbf8ea017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::Waitcnt::KmCnt = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Referenced by <a href="#abc6ef6fb828278d2afdcd60500e888a8">combined</a>, <a href="#a90bde311904c3b06141ba1202d664ea8">hasWaitExceptStoreCnt</a>, <a href="#a362cf8dbafb61f64a4c404a7d1f5f343">Waitcnt</a> and <a href="#ab781b6c8e09b89d8210ea3935b54befb">Waitcnt</a>.</p>

</div>
</div>

### LoadCnt {#a23481ee08f5d965c17f65a68266daacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::Waitcnt::LoadCnt = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Referenced by <a href="#abc6ef6fb828278d2afdcd60500e888a8">combined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#acbb695160ff3f9804b7c0fe9d1994c6e">llvm::AMDGPU::decodeLoadcntDscnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5d4a37c23e1caabf8f64de0e64266f3a">llvm::AMDGPU::decodeWaitcnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a37d9f31b140a3e81750b71e13bc916ac">llvm::AMDGPU::encodeLoadcntDscnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f14260fd47f5c55b3d473291b81a302">llvm::AMDGPU::encodeWaitcnt</a>, <a href="#a90bde311904c3b06141ba1202d664ea8">hasWaitExceptStoreCnt</a>, <a href="#a362cf8dbafb61f64a4c404a7d1f5f343">Waitcnt</a> and <a href="#ab781b6c8e09b89d8210ea3935b54befb">Waitcnt</a>.</p>

</div>
</div>

### SampleCnt {#a5cc5625916faa7a06a912f2582afe42f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::Waitcnt::SampleCnt = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 972 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Referenced by <a href="#abc6ef6fb828278d2afdcd60500e888a8">combined</a>, <a href="#a90bde311904c3b06141ba1202d664ea8">hasWaitExceptStoreCnt</a>, <a href="#a362cf8dbafb61f64a4c404a7d1f5f343">Waitcnt</a> and <a href="#ab781b6c8e09b89d8210ea3935b54befb">Waitcnt</a>.</p>

</div>
</div>

### StoreCnt {#a53a9bc168d637a1e91ae887ec5a41008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::Waitcnt::StoreCnt = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 971 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Referenced by <a href="#abc6ef6fb828278d2afdcd60500e888a8">combined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8e170f06f15d0b3dcab3ca224d8c0400">llvm::AMDGPU::decodeStorecntDscnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ace8ce10585be6e95cc694ee3b72033ae">llvm::AMDGPU::encodeStorecntDscnt</a>, <a href="#a4bf31927fa51c731edb3cd3b2d17a8e3">hasWait</a>, <a href="#ab58ef3859f03f13623e0cd515dc4f72d">hasWaitStoreCnt</a>, <a href="#a362cf8dbafb61f64a4c404a7d1f5f343">Waitcnt</a> and <a href="#ab781b6c8e09b89d8210ea3935b54befb">Waitcnt</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
