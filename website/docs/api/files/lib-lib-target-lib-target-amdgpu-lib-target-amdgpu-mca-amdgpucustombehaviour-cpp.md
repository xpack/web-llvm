---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AMDGPUCustomBehaviour.cpp` File Reference

<p>This file implements methods from the <a href="/web-llvm/docs/api/classes/llvm/mca/amdgpucustombehaviour">AMDGPUCustomBehaviour</a> class. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-h">MCTargetDesc/AMDGPUMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/targetinfo/amdgputargetinfo-h">TargetInfo/AMDGPUTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">Utils/AMDGPUBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">llvm/Support/WithColor.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/mca">mca</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour">CustomBehaviour</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8157b157d30d4f760ae7b7f9dc1a52fb">createAMDGPUCustomBehaviour</a> (const MCSubtargetInfo &amp;STI, const mca::SourceMgr &amp;SrcMgr, const MCInstrInfo &amp;MCII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess">InstrPostProcess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea398d70514f9cdd43c734647d7a549b">createAMDGPUInstrPostProcess</a> (const MCSubtargetInfo &amp;STI, const MCInstrInfo &amp;MCII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abff2d688ab31b2b868abd61f30ff08d6">LLVMInitializeAMDGPUTargetMCA</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extern function to initialize the targets for the <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> backend. <a href="#abff2d688ab31b2b868abd61f30ff08d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This file implements methods from the <a href="/web-llvm/docs/api/classes/llvm/mca/amdgpucustombehaviour">AMDGPUCustomBehaviour</a> class.</p>

<div class="doxySectionDef">

## Functions

### createAMDGPUCustomBehaviour() {#a8157b157d30d4f760ae7b7f9dc1a52fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CustomBehaviour * createAMDGPUCustomBehaviour (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">mca::SourceMgr</a> &amp; SrcMgr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a5f3f23062c5d5636bee27c54f4a407f0">llvm::SrcMgr</a>.</p>


<p>Referenced by <a href="#abff2d688ab31b2b868abd61f30ff08d6">LLVMInitializeAMDGPUTargetMCA</a>.</p>

</div>
</div>

### createAMDGPUInstrPostProcess() {#aea398d70514f9cdd43c734647d7a549b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrPostProcess * createAMDGPUInstrPostProcess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>


<p>Referenced by <a href="#abff2d688ab31b2b868abd61f30ff08d6">LLVMInitializeAMDGPUTargetMCA</a>.</p>

</div>
</div>

### LLVMInitializeAMDGPUTargetMCA() {#abff2d688ab31b2b868abd61f30ff08d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeAMDGPUTargetMCA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extern function to initialize the targets for the <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> backend.</p>

<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>


<p>References <a href="#a8157b157d30d4f760ae7b7f9dc1a52fb">createAMDGPUCustomBehaviour</a>, <a href="#aea398d70514f9cdd43c734647d7a549b">createAMDGPUInstrPostProcess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa4a596c65b215aae8d1ae5da8d1b63fc">llvm::getTheGCNTarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4e0b76a071cfed9f150bc6680ddd9081">llvm::getTheR600Target</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#aedf9544809dabd3df6e329f3d79dbc31">llvm::TargetRegistry::RegisterCustomBehaviour</a> and <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a82742d6cae420864af2a90eaee015b8d">llvm::TargetRegistry::RegisterInstrPostProcess</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
