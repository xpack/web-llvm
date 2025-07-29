---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bpfunctionnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BPFunctionNode` Class

<p>A function with a set of utility nodes where it is beneficial to order two functions close together if they have similar utility nodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BPFunctionNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">llvm/Support/BalancedPartitioning.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a152ce8289fd156a7a4acb2290ab8b45f">IDT</a> = uint64_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e0da99ae04b612397724a441f041714">UtilityNodeT</a> = uint32_t</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13337538b4b19d8e504c511d16edca29">BalancedPartitioning</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51e428b87deebd0dfd3d56c44435b3c4">BPFunctionNodeTest_Basic_Test</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9babb03b7a623acac3809b34db16a90">BalancedPartitioningTest_Basic_Test</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d85488b58190dee280929c69af9d239">BalancedPartitioningTest_Large_Test</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac68b19fae66e542a9dfe197d318a17">BPFunctionNode</a> (IDT Id, ArrayRef&lt; UtilityNodeT &gt; UtilityNodes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af784c54782fa5138513c227e0fbc578d">dump</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a152ce8289fd156a7a4acb2290ab8b45f">IDT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d90e99c1d3fa2cb1f6d0ba9884e208b">Id</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this node. <a href="#a3d90e99c1d3fa2cb1f6d0ba9884e208b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a8e0da99ae04b612397724a441f041714">UtilityNodeT</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa42fe685455d68a6deb4ea09a49223c3">UtilityNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of utility nodes associated with this node. <a href="#aa42fe685455d68a6deb4ea09a49223c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfa3c93a4041cd593659754e88a4d553">Bucket</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The bucket assigned by balanced partitioning. <a href="#abfa3c93a4041cd593659754e88a4d553">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac5fb398d66fde523b07210e516ce0a0">InputOrderIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the input order of the FunctionNodes. <a href="#aac5fb398d66fde523b07210e516ce0a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A function with a set of utility nodes where it is beneficial to order two functions close together if they have similar utility nodes.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### IDT {#a152ce8289fd156a7a4acb2290ab8b45f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BPFunctionNode::IDT =  uint64_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

### UtilityNodeT {#a8e0da99ae04b612397724a441f041714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BPFunctionNode::UtilityNodeT =  uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### BalancedPartitioning {#a13337538b4b19d8e504c511d16edca29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/balancedpartitioning">BalancedPartitioning</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<p>Reference <a href="#a13337538b4b19d8e504c511d16edca29">BalancedPartitioning</a>.</p>


<p>Referenced by <a href="#a13337538b4b19d8e504c511d16edca29">BalancedPartitioning</a>.</p>

</div>
</div>

### BalancedPartitioningTest\_Basic\_Test {#ab9babb03b7a623acac3809b34db16a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class BalancedPartitioningTest_Basic_Test</td>
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


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<p>Reference <a href="#ab9babb03b7a623acac3809b34db16a90">BalancedPartitioningTest_Basic_Test</a>.</p>


<p>Referenced by <a href="#ab9babb03b7a623acac3809b34db16a90">BalancedPartitioningTest_Basic_Test</a>.</p>

</div>
</div>

### BalancedPartitioningTest\_Large\_Test {#a7d85488b58190dee280929c69af9d239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class BalancedPartitioningTest_Large_Test</td>
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


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<p>Reference <a href="#a7d85488b58190dee280929c69af9d239">BalancedPartitioningTest_Large_Test</a>.</p>


<p>Referenced by <a href="#a7d85488b58190dee280929c69af9d239">BalancedPartitioningTest_Large_Test</a>.</p>

</div>
</div>

### BPFunctionNodeTest\_Basic\_Test {#a51e428b87deebd0dfd3d56c44435b3c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class BPFunctionNodeTest_Basic_Test</td>
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


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<p>Reference <a href="#a51e428b87deebd0dfd3d56c44435b3c4">BPFunctionNodeTest_Basic_Test</a>.</p>


<p>Referenced by <a href="#a51e428b87deebd0dfd3d56c44435b3c4">BPFunctionNodeTest_Basic_Test</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BPFunctionNode() {#a5ac68b19fae66e542a9dfe197d318a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BPFunctionNode::BPFunctionNode (<a href="#a152ce8289fd156a7a4acb2290ab8b45f">IDT</a> Id, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#a8e0da99ae04b612397724a441f041714">UtilityNodeT</a> &gt; UtilityNodes)</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">UtilityNodes</td>
<td class="doxyParamItemDescription"><p>the set of utility nodes (must be unique'd)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<p>References <a href="#a3d90e99c1d3fa2cb1f6d0ba9884e208b">Id</a> and <a href="#aa42fe685455d68a6deb4ea09a49223c3">UtilityNodes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#af784c54782fa5138513c227e0fbc578d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFunctionNode::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a>.</p>


<p>References <a href="#abfa3c93a4041cd593659754e88a4d553">Bucket</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#a3d90e99c1d3fa2cb1f6d0ba9884e208b">Id</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#aa42fe685455d68a6deb4ea09a49223c3">UtilityNodes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Id {#a3d90e99c1d3fa2cb1f6d0ba9884e208b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IDT llvm::BPFunctionNode::Id</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this node.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<p>Referenced by <a href="#a5ac68b19fae66e542a9dfe197d318a17">BPFunctionNode</a> and <a href="#af784c54782fa5138513c227e0fbc578d">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Bucket {#abfa3c93a4041cd593659754e88a4d553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::BPFunctionNode::Bucket</td>
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

<p>The bucket assigned by balanced partitioning.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<p>Referenced by <a href="#af784c54782fa5138513c227e0fbc578d">dump</a>.</p>

</div>
</div>

### InputOrderIndex {#aac5fb398d66fde523b07210e516ce0a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BPFunctionNode::InputOrderIndex = 0</td>
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

<p>The index of the input order of the FunctionNodes.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

### UtilityNodes {#aa42fe685455d68a6deb4ea09a49223c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;UtilityNodeT, 4&gt; llvm::BPFunctionNode::UtilityNodes</td>
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

<p>The list of utility nodes associated with this node.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<p>Referenced by <a href="#a5ac68b19fae66e542a9dfe197d318a17">BPFunctionNode</a> and <a href="#af784c54782fa5138513c227e0fbc578d">dump</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/balancedpartitioning-cpp">BalancedPartitioning.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
