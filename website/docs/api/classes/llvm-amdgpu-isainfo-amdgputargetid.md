---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpu/isainfo/amdgputargetid
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUTargetID` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPU::IsaInfo::AMDGPUTargetID { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">Target/AMDGPU/Utils/AMDGPUBaseInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a620c903fbe109239c38c7fc8ac7b6298">AMDGPUTargetID</a> (const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae1a20e466e1a2e56641237d465703ab">~AMDGPUTargetID</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a885bd668f35ea0b9e00d44499495c0fc">isXnackSupported</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b48c1bcb9047175b400ab0ffbce82a2">isXnackOnOrAny</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a89e9df7855466fdc29af6d00e199e1">isXnackOnOrOff</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6">TargetIDSetting</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25bbe697f6fdd4ee71f4897eaa8f2c65">getXnackSetting</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d038a6d4bc8f7cf81bf9e4c979b392f">setXnackSetting</a> (TargetIDSetting NewXnackSetting)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets xnack setting to <span class="doxyComputerOutput">NewXnackSetting</span>. <a href="#a0d038a6d4bc8f7cf81bf9e4c979b392f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0681188640dae9768253d31f52971acb">isSramEccSupported</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fa82fad8bfe176fce6445cb67742af2">isSramEccOnOrAny</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7dd54506a10298ec49300c5cd1f3dfc">isSramEccOnOrOff</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6">TargetIDSetting</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecd3f3ccd0bc04187c08fd2e1bbc9924">getSramEccSetting</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f2b7fbd9fbac3e931acc40904639e1">setSramEccSetting</a> (TargetIDSetting NewSramEccSetting)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets sramecc setting to <span class="doxyComputerOutput">NewSramEccSetting</span>. <a href="#ac9f2b7fbd9fbac3e931acc40904639e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b8980d20ebca6171b8139f4dadc3eb">setTargetIDFromFeaturesString</a> (StringRef FS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab792d0c32d4c9a7998c0ba8885693ff">setTargetIDFromTargetIDStream</a> (StringRef TargetID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9ec355054ee6400df6ba242dd3cb032">toString</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a180dd010ebe90cd8d06622c8ee94cbd0">STI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6">TargetIDSetting</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a944587e1a119cb6613e2ae519407c70b">XnackSetting</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6">TargetIDSetting</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce6d759efa0f4763d27806032a8c372">SramEccSetting</a></td>
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


<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUTargetID() {#a620c903fbe109239c38c7fc8ac7b6298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::IsaInfo::AMDGPUTargetID::AMDGPUTargetID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>, definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6aed36a1ef76a59ee3f15180e0441188ad">llvm::AMDGPU::IsaInfo::Any</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6ab4080bdf74febf04d578ff105cce9d3f">llvm::AMDGPU::IsaInfo::Unsupported</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AMDGPUTargetID() {#aae1a20e466e1a2e56641237d465703ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::IsaInfo::AMDGPUTargetID::~AMDGPUTargetID ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getSramEccSetting() {#aecd3f3ccd0bc04187c08fd2e1bbc9924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetIDSetting llvm::AMDGPU::IsaInfo::AMDGPUTargetID::getSramEccSetting ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The current sramecc <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6">TargetIDSetting</a>, possible options are "Unsupported", "Any", "Off", and "On".</p></dd>
</dl>


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Referenced by <a href="#ad7dd54506a10298ec49300c5cd1f3dfc">isSramEccOnOrOff</a> and <a href="#ae9ec355054ee6400df6ba242dd3cb032">toString</a>.</p>

</div>
</div>

### getXnackSetting() {#a25bbe697f6fdd4ee71f4897eaa8f2c65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetIDSetting llvm::AMDGPU::IsaInfo::AMDGPUTargetID::getXnackSetting ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The current xnack <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6">TargetIDSetting</a>, possible options are "Unsupported", "Any", "Off", and "On".</p></dd>
</dl>


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Referenced by <a href="#a7a89e9df7855466fdc29af6d00e199e1">isXnackOnOrOff</a> and <a href="#ae9ec355054ee6400df6ba242dd3cb032">toString</a>.</p>

</div>
</div>

### isSramEccOnOrAny() {#a1fa82fad8bfe176fce6445cb67742af2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::IsaInfo::AMDGPUTargetID::isSramEccOnOrAny ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the current sramecc setting is "On" or "Any".</p></dd>
</dl>


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6aed36a1ef76a59ee3f15180e0441188ad">llvm::AMDGPU::IsaInfo::Any</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6a521c36a31c2762741cf0f8890cbe05e3">llvm::AMDGPU::IsaInfo::On</a>.</p>

</div>
</div>

### isSramEccOnOrOff() {#ad7dd54506a10298ec49300c5cd1f3dfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::IsaInfo::AMDGPUTargetID::isSramEccOnOrOff ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if current sramecc setting is "On" or "Off", false otherwise.</p></dd>
</dl>


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>References <a href="#aecd3f3ccd0bc04187c08fd2e1bbc9924">getSramEccSetting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6ad15305d7a4e34e02489c74a5ef542f36">llvm::AMDGPU::IsaInfo::Off</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6a521c36a31c2762741cf0f8890cbe05e3">llvm::AMDGPU::IsaInfo::On</a>.</p>

</div>
</div>

### isSramEccSupported() {#a0681188640dae9768253d31f52971acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::IsaInfo::AMDGPUTargetID::isSramEccSupported ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the current sramecc setting is not "Unsupported".</p></dd>
</dl>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6ab4080bdf74febf04d578ff105cce9d3f">llvm::AMDGPU::IsaInfo::Unsupported</a>.</p>


<p>Referenced by <a href="#a08b8980d20ebca6171b8139f4dadc3eb">setTargetIDFromFeaturesString</a>.</p>

</div>
</div>

### isXnackOnOrAny() {#a5b48c1bcb9047175b400ab0ffbce82a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::IsaInfo::AMDGPUTargetID::isXnackOnOrAny ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the current xnack setting is "On" or "Any".</p></dd>
</dl>


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6aed36a1ef76a59ee3f15180e0441188ad">llvm::AMDGPU::IsaInfo::Any</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6a521c36a31c2762741cf0f8890cbe05e3">llvm::AMDGPU::IsaInfo::On</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### isXnackOnOrOff() {#a7a89e9df7855466fdc29af6d00e199e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::IsaInfo::AMDGPUTargetID::isXnackOnOrOff ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if current xnack setting is "On" or "Off", false otherwise.</p></dd>
</dl>


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>References <a href="#a25bbe697f6fdd4ee71f4897eaa8f2c65">getXnackSetting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6ad15305d7a4e34e02489c74a5ef542f36">llvm::AMDGPU::IsaInfo::Off</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6a521c36a31c2762741cf0f8890cbe05e3">llvm::AMDGPU::IsaInfo::On</a>.</p>

</div>
</div>

### isXnackSupported() {#a885bd668f35ea0b9e00d44499495c0fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::IsaInfo::AMDGPUTargetID::isXnackSupported ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the current xnack setting is not "Unsupported".</p></dd>
</dl>


<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6ab4080bdf74febf04d578ff105cce9d3f">llvm::AMDGPU::IsaInfo::Unsupported</a>.</p>


<p>Referenced by <a href="#a08b8980d20ebca6171b8139f4dadc3eb">setTargetIDFromFeaturesString</a>.</p>

</div>
</div>

### setSramEccSetting() {#ac9f2b7fbd9fbac3e931acc40904639e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::IsaInfo::AMDGPUTargetID::setSramEccSetting (<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6">TargetIDSetting</a> NewSramEccSetting)</td>
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

<p>Sets sramecc setting to <span class="doxyComputerOutput">NewSramEccSetting</span>.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>

</div>
</div>

### setTargetIDFromFeaturesString() {#a08b8980d20ebca6171b8139f4dadc3eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::IsaInfo::AMDGPUTargetID::setTargetIDFromFeaturesString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>, definition at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a39a9e8ebdc3fdfb710357fdb5e724abe">llvm::SubtargetFeatures::getFeatures</a>, <a href="#a0681188640dae9768253d31f52971acb">isSramEccSupported</a>, <a href="#a885bd668f35ea0b9e00d44499495c0fc">isXnackSupported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6ad15305d7a4e34e02489c74a5ef542f36">llvm::AMDGPU::IsaInfo::Off</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6a521c36a31c2762741cf0f8890cbe05e3">llvm::AMDGPU::IsaInfo::On</a>.</p>

</div>
</div>

### setTargetIDFromTargetIDStream() {#aab792d0c32d4c9a7998c0ba8885693ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::IsaInfo::AMDGPUTargetID::setTargetIDFromTargetIDStream (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TargetID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>, definition at line 883 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a89316777d66cdd03ab0b656968165c68">llvm::AMDGPU::IsaInfo::getTargetIDSettingFromFeatureString</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>

</div>
</div>

### setXnackSetting() {#a0d038a6d4bc8f7cf81bf9e4c979b392f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::IsaInfo::AMDGPUTargetID::setXnackSetting (<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6">TargetIDSetting</a> NewXnackSetting)</td>
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

<p>Sets xnack setting to <span class="doxyComputerOutput">NewXnackSetting</span>.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>

</div>
</div>

### toString() {#ae9ec355054ee6400df6ba242dd3cb032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::AMDGPU::IsaInfo::AMDGPUTargetID::toString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>String representation of an object.</p></dd>
</dl>


<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>, definition at line 895 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0a0dddcf03f8f66f7c13558b3c81d845">llvm::Triple::AMDHSA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a>, <a href="#aecd3f3ccd0bc04187c08fd2e1bbc9924">getSramEccSetting</a>, <a href="#a25bbe697f6fdd4ee71f4897eaa8f2c65">getXnackSetting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6ad15305d7a4e34e02489c74a5ef542f36">llvm::AMDGPU::IsaInfo::Off</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ab6e8b39aa26af871d8ede5fa8c791ee6a521c36a31c2762741cf0f8890cbe05e3">llvm::AMDGPU::IsaInfo::On</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a935ca0164610567e453bd629e5f6da0e">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitTargetID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SramEccSetting {#a7ce6d759efa0f4763d27806032a8c372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetIDSetting llvm::AMDGPU::IsaInfo::AMDGPUTargetID::SramEccSetting</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>

</div>
</div>

### STI {#a180dd010ebe90cd8d06622c8ee94cbd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo&amp; llvm::AMDGPU::IsaInfo::AMDGPUTargetID::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>

</div>
</div>

### XnackSetting {#a944587e1a119cb6613e2ae519407c70b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetIDSetting llvm::AMDGPU::IsaInfo::AMDGPUTargetID::XnackSetting</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
