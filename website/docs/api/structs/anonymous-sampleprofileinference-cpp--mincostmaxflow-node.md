---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-sampleprofileinference-cpp-/mincostmaxflow/node
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Node` Struct Reference

<p>A node in a flow network. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Node { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fc3a61782af9679718a42db7766a3f6">Distance</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of the cheapest path from the source to the current node. <a href="#a9fc3a61782af9679718a42db7766a3f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a60829bcc64f93abcae8b8b248b7a75">ParentNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The node preceding the current one in the path. <a href="#a4a60829bcc64f93abcae8b8b248b7a75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf360e91ad49092addde26af0d8e4a97">ParentEdgeIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the edge between ParentNode and the current node. <a href="#abf360e91ad49092addde26af0d8e4a97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcab1ffabfd2e66fe384b8e0fc2d752d">Taken</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An indicator of whether the current node is in a queue. <a href="#abcab1ffabfd2e66fe384b8e0fc2d752d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1935bc1bd15960651703c0cb972620e">FracFlow</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data fields utilized in DAG-augmentation: Fractional flow. <a href="#ae1935bc1bd15960651703c0cb972620e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe1015e8bb0a916b16832267a0c7c25f">IntFlow</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Integral flow. <a href="#abe1015e8bb0a916b16832267a0c7c25f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b57c25fc31d4342377d9f092fc5a8ff">Discovery</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Discovery time. <a href="#a4b57c25fc31d4342377d9f092fc5a8ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac38eb234b965ce405619ec82bbbed86c">Finish</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finish time. <a href="#ac38eb234b965ce405619ec82bbbed86c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70e6f8d2b8d44eafec849b7ef919014">NumCalls</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NumCalls. <a href="#af70e6f8d2b8d44eafec849b7ef919014">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A node in a flow network.</p>

<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Discovery {#a4b57c25fc31d4342377d9f092fc5a8ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Node::Discovery</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Discovery time.</p>

<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Distance {#a9fc3a61782af9679718a42db7766a3f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Node::Distance</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of the cheapest path from the source to the current node.</p>

<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Finish {#ac38eb234b965ce405619ec82bbbed86c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Node::Finish</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finish time.</p>

<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### FracFlow {#ae1935bc1bd15960651703c0cb972620e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Node::FracFlow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Data fields utilized in DAG-augmentation: Fractional flow.</p>

<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### IntFlow {#abe1015e8bb0a916b16832267a0c7c25f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Node::IntFlow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Integral flow.</p>

<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### NumCalls {#af70e6f8d2b8d44eafec849b7ef919014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Node::NumCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NumCalls.</p>

<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### ParentEdgeIndex {#abf360e91ad49092addde26af0d8e4a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Node::ParentEdgeIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the edge between ParentNode and the current node.</p>

<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### ParentNode {#a4a60829bcc64f93abcae8b8b248b7a75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Node::ParentNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The node preceding the current one in the path.</p>

<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Taken {#abcab1ffabfd2e66fe384b8e0fc2d752d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Node::Taken</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An indicator of whether the current node is in a queue.</p>

<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
