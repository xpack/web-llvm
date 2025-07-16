---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/divremmapkey
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DivRemMapKey` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::DivRemMapKey { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">llvm/Transforms/Utils/BypassSlowDivision.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d9a5d933619797b4b5d5f43167b6a5">DivRemMapKey</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8883a209f858a3e5638df82b85959f2">DivRemMapKey</a> (bool InSignedOp, Value *InDividend, Value *InDivisor)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e88c4c4d1b77ff28b1835f58cf56b91">SignedOp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6c09e645fbad704df924a7fa0e16aec">Dividend</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7abf4dfbd44a1d22e5db941bc89a35d4">Divisor</a></td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DivRemMapKey() {#af4d9a5d933619797b4b5d5f43167b6a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DivRemMapKey::DivRemMapKey ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a>.</p>

</div>
</div>

### DivRemMapKey() {#ab8883a209f858a3e5638df82b85959f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DivRemMapKey::DivRemMapKey (bool InSignedOp, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InDividend, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InDivisor)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a>.</p>


<p>References <a href="#af6c09e645fbad704df924a7fa0e16aec">Dividend</a>, <a href="#a7abf4dfbd44a1d22e5db941bc89a35d4">Divisor</a> and <a href="#a9e88c4c4d1b77ff28b1835f58cf56b91">SignedOp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Dividend {#af6c09e645fbad704df924a7fa0e16aec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssertingVH&lt;Value&gt; llvm::DivRemMapKey::Dividend</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a>.</p>


<p>Referenced by <a href="#ab8883a209f858a3e5638df82b85959f2">DivRemMapKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a4d14e865a8adfcbd9b83f2242f1f515/#aa97b0fccb52a52ad74543f32ac05d8df">llvm::DenseMapInfo&lt; DivRemMapKey &gt;::getHashValue</a> and <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a4d14e865a8adfcbd9b83f2242f1f515/#adf0a7c65e10311f073d8c6f8dd0ef5bf">llvm::DenseMapInfo&lt; DivRemMapKey &gt;::isEqual</a>.</p>

</div>
</div>

### Divisor {#a7abf4dfbd44a1d22e5db941bc89a35d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssertingVH&lt;Value&gt; llvm::DivRemMapKey::Divisor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a>.</p>


<p>Referenced by <a href="#ab8883a209f858a3e5638df82b85959f2">DivRemMapKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a4d14e865a8adfcbd9b83f2242f1f515/#aa97b0fccb52a52ad74543f32ac05d8df">llvm::DenseMapInfo&lt; DivRemMapKey &gt;::getHashValue</a> and <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a4d14e865a8adfcbd9b83f2242f1f515/#adf0a7c65e10311f073d8c6f8dd0ef5bf">llvm::DenseMapInfo&lt; DivRemMapKey &gt;::isEqual</a>.</p>

</div>
</div>

### SignedOp {#a9e88c4c4d1b77ff28b1835f58cf56b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DivRemMapKey::SignedOp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a>.</p>


<p>Referenced by <a href="#ab8883a209f858a3e5638df82b85959f2">DivRemMapKey</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a4d14e865a8adfcbd9b83f2242f1f515/#aa97b0fccb52a52ad74543f32ac05d8df">llvm::DenseMapInfo&lt; DivRemMapKey &gt;::getHashValue</a> and <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a4d14e865a8adfcbd9b83f2242f1f515/#adf0a7c65e10311f073d8c6f8dd0ef5bf">llvm::DenseMapInfo&lt; DivRemMapKey &gt;::isEqual</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
