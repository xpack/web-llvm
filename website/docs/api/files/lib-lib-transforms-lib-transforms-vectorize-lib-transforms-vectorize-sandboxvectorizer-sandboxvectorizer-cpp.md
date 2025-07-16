---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/sandboxvectorizer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SandboxVectorizer.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/sandboxvectorizer-h">llvm/Transforms/Vectorize/SandboxVectorizer/SandboxVectorizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">llvm/SandboxIR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/sandboxvectorizerpassbuilder-h">llvm/Transforms/Vectorize/SandboxVectorizer/SandboxVectorizerPassBuilder.h</a>"
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae68ed4d18c004fbcd250a94aac2266cd">PrintPassPipeline</a>("sbvec-print-pass-pipeline", cl::init(false), cl::Hidden, cl::desc("Prints the pass pipeline and returns."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c20c547e1dabfbbf083363dd0204b82">DefaultPipelineMagicStr</a> = "*"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A magic string for the default pass pipeline. <a href="#a7c20c547e1dabfbbf083363dd0204b82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056f5999afaf125035426c3d2cd1d172">UserDefinedPassPipeline</a>("sbvec-passes", cl::init(DefaultPipelineMagicStr), cl::Hidden, cl::desc("Comma-separated list of vectorizer passes. If not set " "we run the predefined pipeline."))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a274654b7f5932cae6a71a113322481be">SV_NAME</a>&nbsp;&nbsp;&nbsp;"sandbox-vectorizer"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;<a href="#a274654b7f5932cae6a71a113322481be">SV_NAME</a></td>
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

## Variables

### DefaultPipelineMagicStr {#a7c20c547e1dabfbbf083363dd0204b82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* DefaultPipelineMagicStr = "*"</td>
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

<p>A magic string for the default pass pipeline.</p>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/sandboxvectorizer-cpp">SandboxVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxvectorizerpass/#ae97d039e6b45730ff7a132e723b925e1">llvm::SandboxVectorizerPass::SandboxVectorizerPass</a>.</p>

</div>
</div>

### PrintPassPipeline {#ae68ed4d18c004fbcd250a94aac2266cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintPassPipeline("sbvec-print-pass-pipeline", cl::init(false), cl::Hidden, cl::desc("Prints the pass pipeline and returns."))</td>
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



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/sandboxvectorizer-cpp">SandboxVectorizer.cpp</a>.</p>

</div>
</div>

### UserDefinedPassPipeline {#a056f5999afaf125035426c3d2cd1d172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; UserDefinedPassPipeline("sbvec-passes", cl::init(DefaultPipelineMagicStr), cl::Hidden, cl::desc("Comma-separated list of vectorizer passes. If not set " "we run the predefined pipeline."))</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/sandboxvectorizer-cpp">SandboxVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxvectorizerpass/#ae97d039e6b45730ff7a132e723b925e1">llvm::SandboxVectorizerPass::SandboxVectorizerPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;<a href="#a274654b7f5932cae6a71a113322481be">SV_NAME</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/sandboxvectorizer-cpp">SandboxVectorizer.cpp</a>.</p>

</div>
</div>

### SV\_NAME {#a274654b7f5932cae6a71a113322481be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SV_NAME&nbsp;&nbsp;&nbsp;"sandbox-vectorizer"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/sandboxvectorizer-cpp">SandboxVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
