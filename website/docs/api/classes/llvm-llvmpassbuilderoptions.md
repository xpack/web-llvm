---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/llvmpassbuilderoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LLVMPassBuilderOptions` Class

<p>Helper struct for holding a set of builder options for LLVMRunPasses. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LLVMPassBuilderOptions { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28965b13e9b1fc24ff44e2ca33d75514">LLVMPassBuilderOptions</a> (bool DebugLogging=false, bool VerifyEach=false, const char *AAPipeline=nullptr, PipelineTuningOptions PTO=PipelineTuningOptions())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ea3a4553fd214d5f560644609a16cf">DebugLogging</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7fc9ee28e83064b527c8f6c77223834">VerifyEach</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d64d159229333878125995b640a6dd">AAPipeline</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pipelinetuningoptions">PipelineTuningOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0535246ac54c7d5fdf620f0b592a52ed">PTO</a></td>
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

<p>Helper struct for holding a set of builder options for LLVMRunPasses.</p>


<p>This structure is used to keep LLVMRunPasses backwards compatible with future versions in case we modify the options the new <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager utilizes.</p>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LLVMPassBuilderOptions() {#a28965b13e9b1fc24ff44e2ca33d75514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LLVMPassBuilderOptions::LLVMPassBuilderOptions (bool DebugLogging=false, bool VerifyEach=false, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * AAPipeline=nullptr, <a href="/web-llvm/docs/api/classes/llvm/pipelinetuningoptions">PipelineTuningOptions</a> PTO=<a href="/web-llvm/docs/api/classes/llvm/pipelinetuningoptions">PipelineTuningOptions</a>())</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="#a97d64d159229333878125995b640a6dd">AAPipeline</a>, <a href="#ad8ea3a4553fd214d5f560644609a16cf">DebugLogging</a>, <a href="#a0535246ac54c7d5fdf620f0b592a52ed">PTO</a> and <a href="#aa7fc9ee28e83064b527c8f6c77223834">VerifyEach</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AAPipeline {#a97d64d159229333878125995b640a6dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::LLVMPassBuilderOptions::AAPipeline</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="#a28965b13e9b1fc24ff44e2ca33d75514">LLVMPassBuilderOptions</a>.</p>

</div>
</div>

### DebugLogging {#ad8ea3a4553fd214d5f560644609a16cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLVMPassBuilderOptions::DebugLogging</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="#a28965b13e9b1fc24ff44e2ca33d75514">LLVMPassBuilderOptions</a>.</p>

</div>
</div>

### PTO {#a0535246ac54c7d5fdf620f0b592a52ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PipelineTuningOptions llvm::LLVMPassBuilderOptions::PTO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="#a28965b13e9b1fc24ff44e2ca33d75514">LLVMPassBuilderOptions</a>.</p>

</div>
</div>

### VerifyEach {#aa7fc9ee28e83064b527c8f6c77223834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLVMPassBuilderOptions::VerifyEach</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="#a28965b13e9b1fc24ff44e2ca33d75514">LLVMPassBuilderOptions</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
