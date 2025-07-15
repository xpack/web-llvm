---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/flowjump
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FlowJump` Struct Reference

<p>A wrapper of a jump between two basic blocks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::FlowJump { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">llvm/Transforms/Utils/SampleProfileInference.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9c91a5ea45940cfaa166511aadd2eb2">Source</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa017ffa5be8016e6feb941ceae7c89cc">Target</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdd34566a25bab9890d87c9de6e7e8b0">Weight</a> {0}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491b58e7abf9b59f256a3c66443a1ad5">HasUnknownWeight</a> {<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a061ed8974c636291de7f7cf5c76e4660">IsUnlikely</a> {false}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba9bc6e5c52dfa0898860eeadbbef59b">Flow</a> {0}</td>
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

<p>A wrapper of a jump between two basic blocks.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Flow {#aba9bc6e5c52dfa0898860eeadbbef59b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::FlowJump::Flow {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af962cc3b6565966cbc3d5c1289f31a11">llvm::applyFlowInference</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#ae9165b166eac58ea95367c58bf55795e">anonymous{SampleProfileInference.cpp}::extractWeights</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a320367d9f3ed81fea8f6979ae8e5a4ad">anonymous{SampleProfileInference.cpp}::verifyOutput</a>.</p>

</div>
</div>

### HasUnknownWeight {#a491b58e7abf9b59f256a3c66443a1ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FlowJump::HasUnknownWeight {<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a1ce5cbe1af8289db9c7121774c7ea192">anonymous{SampleProfileInference.cpp}::assignJumpCosts</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a0b9100215c2494cda0d4aa638c2fff7b">anonymous{SampleProfileInference.cpp}::verifyInput</a>.</p>

</div>
</div>

### IsUnlikely {#a061ed8974c636291de7f7cf5c76e4660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FlowJump::IsUnlikely {false}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a1ce5cbe1af8289db9c7121774c7ea192">anonymous{SampleProfileInference.cpp}::assignJumpCosts</a>.</p>

</div>
</div>

### Source {#ae9c91a5ea45940cfaa166511aadd2eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::FlowJump::Source</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a1ce5cbe1af8289db9c7121774c7ea192">anonymous{SampleProfileInference.cpp}::assignJumpCosts</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#ae9165b166eac58ea95367c58bf55795e">anonymous{SampleProfileInference.cpp}::extractWeights</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a46dd2e73fdb4a5c9bf2af4a8fa968bd1">anonymous{SampleProfileInference.cpp}::initializeNetwork</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a320367d9f3ed81fea8f6979ae8e5a4ad">anonymous{SampleProfileInference.cpp}::verifyOutput</a>.</p>

</div>
</div>

### Target {#aa017ffa5be8016e6feb941ceae7c89cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::FlowJump::Target</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a1ce5cbe1af8289db9c7121774c7ea192">anonymous{SampleProfileInference.cpp}::assignJumpCosts</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#ae9165b166eac58ea95367c58bf55795e">anonymous{SampleProfileInference.cpp}::extractWeights</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a46dd2e73fdb4a5c9bf2af4a8fa968bd1">anonymous{SampleProfileInference.cpp}::initializeNetwork</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a0b9100215c2494cda0d4aa638c2fff7b">anonymous{SampleProfileInference.cpp}::verifyInput</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a320367d9f3ed81fea8f6979ae8e5a4ad">anonymous{SampleProfileInference.cpp}::verifyOutput</a>.</p>

</div>
</div>

### Weight {#acdd34566a25bab9890d87c9de6e7e8b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::FlowJump::Weight {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af962cc3b6565966cbc3d5c1289f31a11">llvm::applyFlowInference</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a1ce5cbe1af8289db9c7121774c7ea192">anonymous{SampleProfileInference.cpp}::assignJumpCosts</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#ae9165b166eac58ea95367c58bf55795e">anonymous{SampleProfileInference.cpp}::extractWeights</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a46dd2e73fdb4a5c9bf2af4a8fa968bd1">anonymous{SampleProfileInference.cpp}::initializeNetwork</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a0b9100215c2494cda0d4aa638c2fff7b">anonymous{SampleProfileInference.cpp}::verifyInput</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
