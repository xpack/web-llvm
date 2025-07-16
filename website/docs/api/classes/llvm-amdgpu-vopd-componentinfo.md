---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpu/vopd/componentinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ComponentInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPU::VOPD::ComponentInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">Target/AMDGPU/Utils/AMDGPUBaseInfo.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentlayout">ComponentLayout</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentprops">ComponentProps</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a690225337940c79af87e84a81089ca01">ComponentInfo</a> (const MCInstrDesc &amp;OpDesc, ComponentKind Kind=ComponentKind::SINGLE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbae703ce83d33e441dd00ebe672e340">ComponentInfo</a> (const MCInstrDesc &amp;OpDesc, const ComponentProps &amp;OpXProps)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a140f124623fac75aa4090d7f6ce6c4b3">getIndexInParsedOperands</a> (unsigned CompOprIdx) const</td>
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


<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ComponentInfo() {#a690225337940c79af87e84a81089ca01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::VOPD::ComponentInfo::ComponentInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; OpDesc, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vopd/#a23df9e938f17c2808127d03b7e37f954">ComponentKind</a> Kind=<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vopd/#a23df9e938f17c2808127d03b7e37f954a427e4032429af8594a5884a0d2007ba4">ComponentKind::SINGLE</a>)</td>
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



<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentlayout/#adb8be7174292f0e01011a551255ca154">llvm::AMDGPU::VOPD::ComponentLayout::ComponentLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentprops/#a72806c05ab080c8703b81d6a59af6f8a">llvm::AMDGPU::VOPD::ComponentProps::ComponentProps</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vopd/#a23df9e938f17c2808127d03b7e37f954a427e4032429af8594a5884a0d2007ba4">llvm::AMDGPU::VOPD::SINGLE</a>.</p>

</div>
</div>

### ComponentInfo() {#adbae703ce83d33e441dd00ebe672e340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::VOPD::ComponentInfo::ComponentInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; OpDesc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentprops">ComponentProps</a> &amp; OpXProps)</td>
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



<p>Definition at line 819 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentlayout/#adb8be7174292f0e01011a551255ca154">llvm::AMDGPU::VOPD::ComponentLayout::ComponentLayout</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentprops/#a72806c05ab080c8703b81d6a59af6f8a">llvm::AMDGPU::VOPD::ComponentProps::ComponentProps</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getIndexInParsedOperands() {#a140f124623fac75aa4090d7f6ce6c4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::VOPD::ComponentInfo::getIndexInParsedOperands (unsigned CompOprIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 824 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>, definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vopd/#aaea90d62530ed55360573a3373c684a6a76cb45133a53e6f2778cf2138c2d71fe">llvm::AMDGPU::VOPD::DST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vopd/#aaea90d62530ed55360573a3373c684a6a8e19dc691619a7fc0ba9919e400a0ea2">llvm::AMDGPU::VOPD::DST_NUM</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentprops/#af1c27ddfefc069eb1910f8f1d060a071">llvm::AMDGPU::VOPD::ComponentProps::getCompParsedSrcOperandsNum</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentlayout/#a1dd22e2897acd34109463497938d7f7a">llvm::AMDGPU::VOPD::ComponentLayout::getIndexOfDstInParsedOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentlayout/#aa6540e78ab5d08a184a1497e97031f8f">llvm::AMDGPU::VOPD::ComponentLayout::getIndexOfSrcInParsedOperands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vopd/#aaea90d62530ed55360573a3373c684a6a742e01b153f4debc38a1b1ca1e6db5cd">llvm::AMDGPU::VOPD::MAX_OPR_NUM</a>.</p>

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
