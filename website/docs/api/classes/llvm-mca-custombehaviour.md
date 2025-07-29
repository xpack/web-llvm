---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/custombehaviour
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CustomBehaviour` Class

<p>Class which can be overriden by targets to enforce instruction dependencies and behaviours that aren't expressed well enough within the scheduling model for mca to automatically simulate them properly. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::mca::CustomBehaviour { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/custombehaviour-h">llvm/MCA/CustomBehaviour.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/amdgpucustombehaviour">AMDGPUCustomBehaviour</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9c2ca3f16c7d9d1c6cd4a20269ba729">CustomBehaviour</a> (const MCSubtargetInfo &amp;STI, const mca::SourceMgr &amp;SrcMgr, const MCInstrInfo &amp;MCII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62666ccd5a13e55da4d4b03c80a4c75f">~CustomBehaviour</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1733693fc63741279331007c38453223">checkCustomHazard</a> (ArrayRef&lt; InstRef &gt; IssuedInst, const InstRef &amp;IR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Before the llvm-mca pipeline dispatches an instruction, it first checks for any register or resource dependencies / hazards. <a href="#a1733693fc63741279331007c38453223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/view">View</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9342f37242dde1bc862f0441a82fd5e">getStartViews</a> (llvm::MCInstPrinter &amp;IP, llvm::ArrayRef&lt; llvm::MCInst &gt; Insts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a vector of Views that will be added before all other Views. <a href="#ad9342f37242dde1bc862f0441a82fd5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/view">View</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d04044329947a112b3194db8b15a49e">getPostInstrInfoViews</a> (llvm::MCInstPrinter &amp;IP, llvm::ArrayRef&lt; llvm::MCInst &gt; Insts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a vector of Views that will be added after the InstructionInfoView. <a href="#a6d04044329947a112b3194db8b15a49e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/view">View</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a73f42bda40682efac9f25123e4e8bd">getEndViews</a> (llvm::MCInstPrinter &amp;IP, llvm::ArrayRef&lt; llvm::MCInst &gt; Insts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a vector of Views that will be added after all other Views. <a href="#a0a73f42bda40682efac9f25123e4e8bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f327d1084786084e10242b9868cdf74">STI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">mca::SourceMgr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a818762e038ef7ffa0d5c2bc9822961c5">SrcMgr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15a50057bc7184990fc2b2885321821b">MCII</a></td>
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

<p>Class which can be overriden by targets to enforce instruction dependencies and behaviours that aren't expressed well enough within the scheduling model for mca to automatically simulate them properly.</p>


<p>If you implement this class for your target, make sure to also implement a target specific <a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess">InstrPostProcess</a> class as well.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/custombehaviour-h">CustomBehaviour.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CustomBehaviour() {#ad9c2ca3f16c7d9d1c6cd4a20269ba729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::CustomBehaviour::CustomBehaviour (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">mca::SourceMgr</a> &amp; SrcMgr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/custombehaviour-h">CustomBehaviour.h</a>.</p>


<p>References <a href="#a15a50057bc7184990fc2b2885321821b">MCII</a>, <a href="#a818762e038ef7ffa0d5c2bc9822961c5">SrcMgr</a> and <a href="#a8f327d1084786084e10242b9868cdf74">STI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/amdgpucustombehaviour/#a8c616a0039f36b38c197da02e179797b">llvm::mca::AMDGPUCustomBehaviour::AMDGPUCustomBehaviour</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CustomBehaviour() {#a62666ccd5a13e55da4d4b03c80a4c75f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::CustomBehaviour::~CustomBehaviour ()</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/custombehaviour-h">CustomBehaviour.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### checkCustomHazard() {#a1733693fc63741279331007c38453223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::CustomBehaviour::checkCustomHazard (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; IssuedInst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
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

<p>Before the llvm-mca pipeline dispatches an instruction, it first checks for any register or resource dependencies / hazards.</p>


<p>If it doesn't find any, this method will be invoked to determine if there are any custom hazards that the instruction needs to wait for. The return value of this method is the number of cycles that the instruction needs to wait for. It's safe to underestimate the number of cycles to wait for since these checks will be invoked again before the intruction gets dispatched. However, it's not safe (accurate) to overestimate the number of cycles to wait for since the instruction will wait for AT LEAST that number of cycles before attempting to be dispatched again.</p>


<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/custombehaviour-h">CustomBehaviour.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/custombehaviour-cpp">CustomBehaviour.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>

</div>
</div>

### getEndViews() {#a0a73f42bda40682efac9f25123e4e8bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::unique_ptr&lt; View &gt; &gt; llvm::mca::CustomBehaviour::getEndViews (<a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">llvm::MCInstPrinter</a> &amp; IP, <a href="/web-llvm/docs/api/classes/llvm/arrayref">llvm::ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinst">llvm::MCInst</a> &gt; Insts)</td>
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

<p>Return a vector of Views that will be added after all other Views.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/custombehaviour-h">CustomBehaviour.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/custombehaviour-cpp">CustomBehaviour.cpp</a>.</p>

</div>
</div>

### getPostInstrInfoViews() {#a6d04044329947a112b3194db8b15a49e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::unique_ptr&lt; View &gt; &gt; llvm::mca::CustomBehaviour::getPostInstrInfoViews (<a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">llvm::MCInstPrinter</a> &amp; IP, <a href="/web-llvm/docs/api/classes/llvm/arrayref">llvm::ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinst">llvm::MCInst</a> &gt; Insts)</td>
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

<p>Return a vector of Views that will be added after the InstructionInfoView.</p>

<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/custombehaviour-h">CustomBehaviour.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/custombehaviour-cpp">CustomBehaviour.cpp</a>.</p>

</div>
</div>

### getStartViews() {#ad9342f37242dde1bc862f0441a82fd5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::unique_ptr&lt; View &gt; &gt; llvm::mca::CustomBehaviour::getStartViews (<a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">llvm::MCInstPrinter</a> &amp; IP, <a href="/web-llvm/docs/api/classes/llvm/arrayref">llvm::ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinst">llvm::MCInst</a> &gt; Insts)</td>
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

<p>Return a vector of Views that will be added before all other Views.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/custombehaviour-h">CustomBehaviour.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/custombehaviour-cpp">CustomBehaviour.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### MCII {#a15a50057bc7184990fc2b2885321821b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrInfo&amp; llvm::mca::CustomBehaviour::MCII</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/custombehaviour-h">CustomBehaviour.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/amdgpucustombehaviour/#a8c616a0039f36b38c197da02e179797b">llvm::mca::AMDGPUCustomBehaviour::AMDGPUCustomBehaviour</a> and <a href="#ad9c2ca3f16c7d9d1c6cd4a20269ba729">CustomBehaviour</a>.</p>

</div>
</div>

### SrcMgr {#a818762e038ef7ffa0d5c2bc9822961c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const mca::SourceMgr&amp; llvm::mca::CustomBehaviour::SrcMgr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/custombehaviour-h">CustomBehaviour.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/amdgpucustombehaviour/#a8c616a0039f36b38c197da02e179797b">llvm::mca::AMDGPUCustomBehaviour::AMDGPUCustomBehaviour</a> and <a href="#ad9c2ca3f16c7d9d1c6cd4a20269ba729">CustomBehaviour</a>.</p>

</div>
</div>

### STI {#a8f327d1084786084e10242b9868cdf74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo&amp; llvm::mca::CustomBehaviour::STI</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/custombehaviour-h">CustomBehaviour.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/amdgpucustombehaviour/#a8c616a0039f36b38c197da02e179797b">llvm::mca::AMDGPUCustomBehaviour::AMDGPUCustomBehaviour</a> and <a href="#ad9c2ca3f16c7d9d1c6cd4a20269ba729">CustomBehaviour</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/custombehaviour-h">CustomBehaviour.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mca/custombehaviour-cpp">CustomBehaviour.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
