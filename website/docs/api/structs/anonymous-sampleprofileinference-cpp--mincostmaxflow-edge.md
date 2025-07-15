---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-sampleprofileinference-cpp-/mincostmaxflow/edge
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Edge` Struct Reference

<p>An edge in a flow network. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Edge { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af13b445a0ebf1fdef55e5a26b48c5488">Cost</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of the edge. <a href="#af13b445a0ebf1fdef55e5a26b48c5488">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb62c30093b1cc9a7710cb95591faeb4">Capacity</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The capacity of the edge. <a href="#aeb62c30093b1cc9a7710cb95591faeb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aa67329a8fa27aa3cbb06211ec40d66">Flow</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current flow on the edge. <a href="#a8aa67329a8fa27aa3cbb06211ec40d66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a425c161afe9f9b13a0312ba91498d3ac">Dst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The destination node of the edge. <a href="#a425c161afe9f9b13a0312ba91498d3ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a992cf2c7dfa208f91ed9a703cb585aea">RevEdgeIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the reverse edge between Dst and the current node. <a href="#a992cf2c7dfa208f91ed9a703cb585aea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8090a5b7ea7f888d45e9bbf08b045f95">OnShortestPath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data fields utilized in DAG-augmentation: Whether the edge is currently on a shortest path from Source to <a href="/web-llvm/docs/api/classes/llvm/target">Target</a>. <a href="#a8090a5b7ea7f888d45e9bbf08b045f95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a0caebd77e9c905d5adc6eaa0df9d6">AugmentedFlow</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extra flow along the edge. <a href="#ac2a0caebd77e9c905d5adc6eaa0df9d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An edge in a flow network.</p>

<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### AugmentedFlow {#ac2a0caebd77e9c905d5adc6eaa0df9d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Edge::AugmentedFlow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extra flow along the edge.</p>

<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Capacity {#aeb62c30093b1cc9a7710cb95591faeb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Edge::Capacity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The capacity of the edge.</p>

<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Cost {#af13b445a0ebf1fdef55e5a26b48c5488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Edge::Cost</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of the edge.</p>

<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Dst {#a425c161afe9f9b13a0312ba91498d3ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Edge::Dst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The destination node of the edge.</p>

<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### Flow {#a8aa67329a8fa27aa3cbb06211ec40d66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Edge::Flow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current flow on the edge.</p>

<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### OnShortestPath {#a8090a5b7ea7f888d45e9bbf08b045f95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Edge::OnShortestPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Data fields utilized in DAG-augmentation: Whether the edge is currently on a shortest path from Source to <a href="/web-llvm/docs/api/classes/llvm/target">Target</a>.</p>

<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

</div>
</div>

### RevEdgeIndex {#a992cf2c7dfa208f91ed9a703cb585aea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::Edge::RevEdgeIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the reverse edge between Dst and the current node.</p>

<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>

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
