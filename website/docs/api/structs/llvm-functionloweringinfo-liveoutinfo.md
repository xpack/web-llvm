---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/functionloweringinfo/liveoutinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LiveOutInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::FunctionLoweringInfo::LiveOutInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">llvm/CodeGen/FunctionLoweringInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeab085bec726d772b2654028eb61fa05">LiveOutInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a651904591143e71c02a94dca2659fc8e">NumSignBits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45db7e23083b4babe630353f2e2a2510">IsValid</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac49dfd777da8c8caee8f3d6370ef14ea">Known</a> = 1</td>
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


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LiveOutInfo() {#aeab085bec726d772b2654028eb61fa05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FunctionLoweringInfo::LiveOutInfo::LiveOutInfo ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>References <a href="#a45db7e23083b4babe630353f2e2a2510">IsValid</a>, <a href="#a651904591143e71c02a94dca2659fc8e">NumSignBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsValid {#a45db7e23083b4babe630353f2e2a2510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FunctionLoweringInfo::LiveOutInfo::IsValid</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a60dfda975fe4068ff59554303033a9a3">llvm::FunctionLoweringInfo::GetLiveOutRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a53ba73377df4268433b190a98516ce8d">llvm::FunctionLoweringInfo::GetLiveOutRegInfo</a> and <a href="#aeab085bec726d772b2654028eb61fa05">LiveOutInfo</a>.</p>

</div>
</div>

### Known {#ac49dfd777da8c8caee8f3d6370ef14ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::FunctionLoweringInfo::LiveOutInfo::Known = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a5afb7d50f639285c9ef082439615915e">llvm::FunctionLoweringInfo::AddLiveOutRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#ad782fe84b36a1c379ac9f1ac367706e1">llvm::RegsForValue::getCopyFromRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a53ba73377df4268433b190a98516ce8d">llvm::FunctionLoweringInfo::GetLiveOutRegInfo</a>.</p>

</div>
</div>

### NumSignBits {#a651904591143e71c02a94dca2659fc8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FunctionLoweringInfo::LiveOutInfo::NumSignBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a5afb7d50f639285c9ef082439615915e">llvm::FunctionLoweringInfo::AddLiveOutRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#ad782fe84b36a1c379ac9f1ac367706e1">llvm::RegsForValue::getCopyFromRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a53ba73377df4268433b190a98516ce8d">llvm::FunctionLoweringInfo::GetLiveOutRegInfo</a> and <a href="#aeab085bec726d772b2654028eb61fa05">LiveOutInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
