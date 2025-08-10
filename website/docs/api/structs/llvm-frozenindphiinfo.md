---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/frozenindphiinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FrozenIndPHIInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::FrozenIndPHIInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4017a23d0c01e196f9b218ab2997b0cb">FrozenIndPHIInfo</a> (PHINode *PHI, BinaryOperator *StepInst)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511a0ae78b1ee64d7dd1e50b37ec4f45">operator==</a> (const FrozenIndPHIInfo &amp;Other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/freezeinst">FreezeInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a559a6f14a5c117b9daa238c14ab0a97c">FI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5caa6aa9933c075c3ca6f3ab4c6bffdb">PHI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6115caef7bb47530b16946f394f8f2f0">StepInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b4cbcf98913290545a5efa7f92e8610">StepValIdx</a> = 0</td>
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


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/canonicalizefreezeinloops-cpp">CanonicalizeFreezeInLoops.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FrozenIndPHIInfo() {#a4017a23d0c01e196f9b218ab2997b0cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FrozenIndPHIInfo::FrozenIndPHIInfo (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PHI, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * StepInst)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/canonicalizefreezeinloops-cpp">CanonicalizeFreezeInLoops.cpp</a>.</p>


<p>References <a href="#a5caa6aa9933c075c3ca6f3ab4c6bffdb">PHI</a> and <a href="#a6115caef7bb47530b16946f394f8f2f0">StepInst</a>.</p>


<p>Referenced by <a href="#a511a0ae78b1ee64d7dd1e50b37ec4f45">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a511a0ae78b1ee64d7dd1e50b37ec4f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FrozenIndPHIInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/frozenindphiinfo">FrozenIndPHIInfo</a> &amp; Other)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/canonicalizefreezeinloops-cpp">CanonicalizeFreezeInLoops.cpp</a>.</p>


<p>References <a href="#a559a6f14a5c117b9daa238c14ab0a97c">FI</a>, <a href="#a4017a23d0c01e196f9b218ab2997b0cb">FrozenIndPHIInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FI {#a559a6f14a5c117b9daa238c14ab0a97c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FreezeInst* llvm::FrozenIndPHIInfo::FI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/canonicalizefreezeinloops-cpp">CanonicalizeFreezeInLoops.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2d0489b7ff465b00b1924bf0f5134b07/#a429bb641b9336d41162bc2135d68b4bf">llvm::DenseMapInfo&lt; FrozenIndPHIInfo &gt;::getHashValue</a> and <a href="#a511a0ae78b1ee64d7dd1e50b37ec4f45">operator==</a>.</p>

</div>
</div>

### PHI {#a5caa6aa9933c075c3ca6f3ab4c6bffdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode* llvm::FrozenIndPHIInfo::PHI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/canonicalizefreezeinloops-cpp">CanonicalizeFreezeInLoops.cpp</a>.</p>


<p>Referenced by <a href="#a4017a23d0c01e196f9b218ab2997b0cb">FrozenIndPHIInfo</a>.</p>

</div>
</div>

### StepInst {#a6115caef7bb47530b16946f394f8f2f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator* llvm::FrozenIndPHIInfo::StepInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/canonicalizefreezeinloops-cpp">CanonicalizeFreezeInLoops.cpp</a>.</p>


<p>Referenced by <a href="#a4017a23d0c01e196f9b218ab2997b0cb">FrozenIndPHIInfo</a>.</p>

</div>
</div>

### StepValIdx {#a9b4cbcf98913290545a5efa7f92e8610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FrozenIndPHIInfo::StepValIdx = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/canonicalizefreezeinloops-cpp">CanonicalizeFreezeInLoops.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/canonicalizefreezeinloops-cpp">CanonicalizeFreezeInLoops.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
