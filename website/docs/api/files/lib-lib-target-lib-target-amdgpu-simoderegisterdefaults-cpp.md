---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SIModeRegisterDefaults.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af58ec68b90bd7529edeafc9ca05aca7d">getModeRegisterRoundMode</a> (uint32_t HWFP32Val, uint32_t HWFP64Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine f32 and f64 rounding modes into a combined rounding mode value. <a href="#af58ec68b90bd7529edeafc9ca05aca7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac31f70f8a38fca2a9f8b20232e632b6c">encodeFltRoundsTable</a> (uint32_t FltRoundsVal, uint32_t HWF32Val, uint32_t HWF64Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a805bb4089e8845b401e15e6a138d93">encodeFltRoundsTableSame</a> (AMDGPUFltRounds FltRoundsMode, uint32_t HWVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abc1e1a833cbcda7dce275641181486d7">AMDGPUFltRounds</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2beed562e030be32fb12895e36af9626">decodeIndexFltRoundConversionTable</a> (uint32_t HWMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa734a3308b9fe688e2b856a5aad64073">encodeFltRoundsToHWTableSame</a> (uint32_t HWVal, uint32_t FltRoundsVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e777f5f6af47fcca1f13c7b02ee6138">encodeFltRoundsToHWTable</a> (uint32_t HWF32Val, uint32_t HWF64Val, uint32_t FltRoundsVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode FLT_ROUNDS into the hardware value where the two rounding modes different and use an extended value. <a href="#a1e777f5f6af47fcca1f13c7b02ee6138">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53a44be984b7e98e5b6f5452b0ded12">decodeFltRoundToHWConversionTable</a> (uint64_t FltRoundToHWConversionTable, uint32_t FltRounds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the hardware rounding mode equivalent of a <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abc1e1a833cbcda7dce275641181486d7">AMDGPUFltRounds</a> value. <a href="#ac53a44be984b7e98e5b6f5452b0ded12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a246d7378266f8664ae9133b8a77ad8d6">decodeFltRoundToHW</a> (uint32_t FltRounds)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94d54c0d54d19b4fa1599ddaae563606">HWTowardZero</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a4acbc6661acdb47237bd5ed7c9b73f3d">FP_ROUND_ROUND_TO_ZERO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad217942210b4e28fdbca838686fbf53d">HWNearestTiesToEven</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a41f16ecef0a587cf75f9be3cce955f46">FP_ROUND_ROUND_TO_NEAREST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eb3c8a001c9fb8a1ff39e922595e5d0">HWTowardPositive</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a3de6b9fc40f27b2963ef551d5e2c0387">FP_ROUND_ROUND_TO_INF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51f70226081167f05a0e75b64c06827c">HWTowardNegative</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#ab9143452ed7db1816eba0c236666b84d">FP_ROUND_ROUND_TO_NEGINF</a></td>
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

### decodeFltRoundToHW() {#a246d7378266f8664ae9133b8a77ad8d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr uint32_t decodeFltRoundToHW (uint32_t FltRounds)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a30a62364beb94ffc4a4f7c72b63f2c62">llvm::AMDGPU::FltRoundToHWConversionTable</a>.</p>

</div>
</div>

### decodeFltRoundToHWConversionTable() {#ac53a44be984b7e98e5b6f5452b0ded12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr uint32_t decodeFltRoundToHWConversionTable (uint64_t FltRoundToHWConversionTable, uint32_t FltRounds)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read the hardware rounding mode equivalent of a <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abc1e1a833cbcda7dce275641181486d7">AMDGPUFltRounds</a> value.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a91dd49bc5d7d7e50ad119bd2503c0f2b">llvm::AMDGPU::ExtendedFltRoundOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a30a62364beb94ffc4a4f7c72b63f2c62">llvm::AMDGPU::FltRoundToHWConversionTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abc1e1a833cbcda7dce275641181486d7adceae66b26cd01122e527c275f20bab4">llvm::AMDGPU::TowardNegative</a>.</p>

</div>
</div>

### decodeIndexFltRoundConversionTable() {#a2beed562e030be32fb12895e36af9626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr AMDGPUFltRounds decodeIndexFltRoundConversionTable (uint32_t HWMode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a91dd49bc5d7d7e50ad119bd2503c0f2b">llvm::AMDGPU::ExtendedFltRoundOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#affdb41b87378347264f7ff1c58150797">llvm::AMDGPU::FltRoundConversionTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abc1e1a833cbcda7dce275641181486d7adceae66b26cd01122e527c275f20bab4">llvm::AMDGPU::TowardNegative</a>.</p>

</div>
</div>

### encodeFltRoundsTable() {#ac31f70f8a38fca2a9f8b20232e632b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr uint64_t encodeFltRoundsTable (uint32_t FltRoundsVal, uint32_t HWF32Val, uint32_t HWF64Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a91dd49bc5d7d7e50ad119bd2503c0f2b">llvm::AMDGPU::ExtendedFltRoundOffset</a>, <a href="#af58ec68b90bd7529edeafc9ca05aca7d">getModeRegisterRoundMode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abc1e1a833cbcda7dce275641181486d7adceae66b26cd01122e527c275f20bab4">llvm::AMDGPU::TowardNegative</a>.</p>


<p>Referenced by <a href="#a5a805bb4089e8845b401e15e6a138d93">encodeFltRoundsTableSame</a>.</p>

</div>
</div>

### encodeFltRoundsTableSame() {#a5a805bb4089e8845b401e15e6a138d93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr uint64_t encodeFltRoundsTableSame (<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abc1e1a833cbcda7dce275641181486d7">AMDGPUFltRounds</a> FltRoundsMode, uint32_t HWVal)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>


<p>Reference <a href="#ac31f70f8a38fca2a9f8b20232e632b6c">encodeFltRoundsTable</a>.</p>

</div>
</div>

### encodeFltRoundsToHWTable() {#a1e777f5f6af47fcca1f13c7b02ee6138}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr uint64_t encodeFltRoundsToHWTable (uint32_t HWF32Val, uint32_t HWF64Val, uint32_t FltRoundsVal)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decode FLT_ROUNDS into the hardware value where the two rounding modes different and use an extended value.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a91dd49bc5d7d7e50ad119bd2503c0f2b">llvm::AMDGPU::ExtendedFltRoundOffset</a>, <a href="#af58ec68b90bd7529edeafc9ca05aca7d">getModeRegisterRoundMode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abc1e1a833cbcda7dce275641181486d7adceae66b26cd01122e527c275f20bab4">llvm::AMDGPU::TowardNegative</a>.</p>

</div>
</div>

### encodeFltRoundsToHWTableSame() {#aa734a3308b9fe688e2b856a5aad64073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr uint64_t encodeFltRoundsToHWTableSame (uint32_t HWVal, uint32_t FltRoundsVal)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a91dd49bc5d7d7e50ad119bd2503c0f2b">llvm::AMDGPU::ExtendedFltRoundOffset</a>, <a href="#af58ec68b90bd7529edeafc9ca05aca7d">getModeRegisterRoundMode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abc1e1a833cbcda7dce275641181486d7adceae66b26cd01122e527c275f20bab4">llvm::AMDGPU::TowardNegative</a>.</p>

</div>
</div>

### getModeRegisterRoundMode() {#af58ec68b90bd7529edeafc9ca05aca7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr uint32_t getModeRegisterRoundMode (uint32_t HWFP32Val, uint32_t HWFP64Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine f32 and f64 rounding modes into a combined rounding mode value.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af50a4d5a0883514dc033497a59d1a83d">llvm::AMDGPU::F32FltRoundOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a68537a8a519fbda96c4a5f4c163ac5a5">llvm::AMDGPU::F64FltRoundOffset</a>.</p>


<p>Referenced by <a href="#ac31f70f8a38fca2a9f8b20232e632b6c">encodeFltRoundsTable</a>, <a href="#a1e777f5f6af47fcca1f13c7b02ee6138">encodeFltRoundsToHWTable</a> and <a href="#aa734a3308b9fe688e2b856a5aad64073">encodeFltRoundsToHWTableSame</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### HWNearestTiesToEven {#ad217942210b4e28fdbca838686fbf53d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t HWNearestTiesToEven = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a41f16ecef0a587cf75f9be3cce955f46">FP_ROUND_ROUND_TO_NEAREST</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>

</div>
</div>

### HWTowardNegative {#a51f70226081167f05a0e75b64c06827c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t HWTowardNegative = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#ab9143452ed7db1816eba0c236666b84d">FP_ROUND_ROUND_TO_NEGINF</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>

</div>
</div>

### HWTowardPositive {#a6eb3c8a001c9fb8a1ff39e922595e5d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t HWTowardPositive = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a3de6b9fc40f27b2963ef551d5e2c0387">FP_ROUND_ROUND_TO_INF</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>

</div>
</div>

### HWTowardZero {#a94d54c0d54d19b4fa1599ddaae563606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t HWTowardZero = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a4acbc6661acdb47237bd5ed7c9b73f3d">FP_ROUND_ROUND_TO_ZERO</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
