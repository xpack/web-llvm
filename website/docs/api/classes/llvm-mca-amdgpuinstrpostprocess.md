---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/amdgpuinstrpostprocess
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AMDGPUInstrPostProcess` Class



## Declaration

<div class="doxyDeclaration">
class llvm::mca::AMDGPUInstrPostProcess { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">Target/AMDGPU/MCA/AMDGPUCustomBehaviour.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess">InstrPostProcess</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class which can be overriden by targets to modify the <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">mca::Instruction</a> objects before the pipeline starts. <a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7024ca4abee75c7e7cab15b1237fdcca">AMDGPUInstrPostProcess</a> (const MCSubtargetInfo &amp;STI, const MCInstrInfo &amp;MCII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1422cb317b1b52dd65aad9216d6c2ee">~AMDGPUInstrPostProcess</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a3192dc22bc884155c604947d12e7a7">postProcessInstruction</a> (std::unique_ptr&lt; Instruction &gt; &amp;Inst, const MCInst &amp;MCI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method can be overriden by targets to modify the <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">mca::Instruction</a> object after it has been lowered from the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#a1a3192dc22bc884155c604947d12e7a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb63babca3c00ea493c62a36241e4271">processWaitCnt</a> (std::unique_ptr&lt; Instruction &gt; &amp;Inst, const MCInst &amp;MCI)</td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUInstrPostProcess() {#a7024ca4abee75c7e7cab15b1237fdcca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::AMDGPUInstrPostProcess::AMDGPUInstrPostProcess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess/#ad0c98ba2801809b09e24b4c270abcc85">llvm::mca::InstrPostProcess::InstrPostProcess</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess/#aac08030fd3e230d4d35e745849ecd789">llvm::mca::InstrPostProcess::MCII</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess/#a7c4d4cfb0828cb3ed1f40e38b1ca3c2a">llvm::mca::InstrPostProcess::STI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AMDGPUInstrPostProcess() {#aa1422cb317b1b52dd65aad9216d6c2ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::AMDGPUInstrPostProcess::~AMDGPUInstrPostProcess ()</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### postProcessInstruction() {#a1a3192dc22bc884155c604947d12e7a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::AMDGPUInstrPostProcess::postProcessInstruction (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">Instruction</a> &gt; &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCI)</td>
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

<p>This method can be overriden by targets to modify the <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">mca::Instruction</a> object after it has been lowered from the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<p>This is generally a less disruptive alternative to modifying the scheduling model.</p>


<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### processWaitCnt() {#adb63babca3c00ea493c62a36241e4271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::AMDGPUInstrPostProcess::processWaitCnt (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">Instruction</a> &gt; &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
