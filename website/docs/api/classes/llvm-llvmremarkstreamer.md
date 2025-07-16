---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/llvmremarkstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LLVMRemarkStreamer` Class Reference

<p>Streamer for LLVM remarks which has logic for dealing with <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> objects. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LLVMRemarkStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmremarkstreamer-h">llvm/IR/LLVMRemarkStreamer.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2bbd53e39040f6af4a2a0508a3f3e8a">LLVMRemarkStreamer</a> (remarks::RemarkStreamer &amp;RS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8676fe8d06d8d0bd1c4d3db2107769">emit</a> (const DiagnosticInfoOptimizationBase &amp;Diag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a diagnostic through the streamer. <a href="#afb8676fe8d06d8d0bd1c4d3db2107769">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/remark">remarks::Remark</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a52bafa66c1dd5c5746378dd387bd38">toRemark</a> (const DiagnosticInfoOptimizationBase &amp;Diag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert diagnostics into remark objects. <a href="#a2a52bafa66c1dd5c5746378dd387bd38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/remarks/remarkstreamer">remarks::RemarkStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fe0690c223db44e4eed3748dcad0385">RS</a></td>
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

<p>Streamer for LLVM remarks which has logic for dealing with <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> objects.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmremarkstreamer-h">LLVMRemarkStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LLVMRemarkStreamer() {#ab2bbd53e39040f6af4a2a0508a3f3e8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LLVMRemarkStreamer::LLVMRemarkStreamer (<a href="/web-llvm/docs/api/classes/llvm/remarks/remarkstreamer">remarks::RemarkStreamer</a> &amp; RS)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmremarkstreamer-h">LLVMRemarkStreamer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#afb8676fe8d06d8d0bd1c4d3db2107769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMRemarkStreamer::emit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase">DiagnosticInfoOptimizationBase</a> &amp; Diag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a diagnostic through the streamer.</p>

<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmremarkstreamer-h">LLVMRemarkStreamer.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmremarkstreamer-cpp">LLVMRemarkStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a51e48dc15ff1e5851f1ac88b2f959ff3">llvm::DiagnosticInfoOptimizationBase::getPassName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### toRemark() {#a2a52bafa66c1dd5c5746378dd387bd38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">remarks::Remark LLVMRemarkStreamer::toRemark (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase">DiagnosticInfoOptimizationBase</a> &amp; Diag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert diagnostics into remark objects.</p>


<p>LLVM Diagnostic -&gt; Remark.</p>


<p>The lifetime of the members of the result is bound to the lifetime of the LLVM diagnostics.</p>


<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmremarkstreamer-h">LLVMRemarkStreamer.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmremarkstreamer-cpp">LLVMRemarkStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### RS {#a6fe0690c223db44e4eed3748dcad0385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">remarks::RemarkStreamer&amp; llvm::LLVMRemarkStreamer::RS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmremarkstreamer-h">LLVMRemarkStreamer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmremarkstreamer-h">LLVMRemarkStreamer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/llvmremarkstreamer-cpp">LLVMRemarkStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
