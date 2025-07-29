---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/llvmremarkstreamer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LLVMRemarkStreamer.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmremarkstreamer-h">llvm/IR/LLVMRemarkStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstreamer-h">llvm/Remarks/RemarkStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">llvm/Support/ToolOutputFile.h</a>"
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527f">remarks::Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae34205a960e475815868e75e38be32fd">toRemarkType</a> (enum DiagnosticKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594">DiagnosticKind</a> -&gt; <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527f">remarks::Type</a>. <a href="#ae34205a960e475815868e75e38be32fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklocation">remarks::RemarkLocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ba93e66512ebb2bba32798b1b7fac8">toRemarkLocation</a> (const DiagnosticLocation &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> -&gt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklocation">remarks::RemarkLocation</a>. <a href="#ab3ba93e66512ebb2bba32798b1b7fac8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### toRemarkLocation() {#ab3ba93e66512ebb2bba32798b1b7fac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; remarks::RemarkLocation &gt; toRemarkLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; DL)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> -&gt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklocation">remarks::RemarkLocation</a>.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmremarkstreamer-cpp">LLVMRemarkStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### toRemarkType() {#ae34205a960e475815868e75e38be32fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">remarks::Type toRemarkType (enum <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594">DiagnosticKind</a> Kind)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594">DiagnosticKind</a> -&gt; <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527f">remarks::Type</a>.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmremarkstreamer-cpp">LLVMRemarkStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fa739e6d2a73723ec7b1919fa5a51f9b07">llvm::remarks::Analysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fa0b3099ea02e918671e4f2f122c3cbb22">llvm::remarks::AnalysisAliasing</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fa23628109ba8dd4d9e96c506db0738e77">llvm::remarks::AnalysisFPCommute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a4b4e6d81022a14f72a9d207cde6e2cb1">llvm::DK_MachineOptimizationRemark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a7dd37b39b11727c3cb52146531813b30">llvm::DK_MachineOptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594aa12ba73e439ce4c158fccc1abf0746d1">llvm::DK_MachineOptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594ace7ad9247977f7e4294af002136bf5bb">llvm::DK_OptimizationFailure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a959ff2a8ed63f995237f5a1c77db0df6">llvm::DK_OptimizationRemark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a27ed101669b84c58dbf9363fe96bdf64">llvm::DK_OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a330a17a4ee40b2e3030ee04bbd2d35b2">llvm::DK_OptimizationRemarkAnalysisAliasing</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594af5a6b58a3000390a8900fc50b35711ed">llvm::DK_OptimizationRemarkAnalysisFPCommute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a60172d67189a80dd366981444c7e6fe9">llvm::DK_OptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fae139a585510a502bbf1841cf589f5086">llvm::remarks::Failure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527faca9e83a6c347b2bdf7f00ef202a331ad">llvm::remarks::Missed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527faa0d0628f6b4e4d78d2ffef4d4d1c4b15">llvm::remarks::Passed</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aeb5853e98ae4d9ab7cb002879736527fa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::remarks::Unknown</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
