---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targettransforminfo/vplegalization
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VPLegalization` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::TargetTransformInfo::VPLegalization { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VPTransform { <a href="#abf988827c40fdf90a1e08a8e2cddea0d">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8751b629c47f25dc1b3859fbe1d5945">VPLegalization</a> (VPTransform EVLParamStrategy, VPTransform OpStrategy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fbed0c5e7548b5ea557657b56109ddf">shouldDoNothing</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abf988827c40fdf90a1e08a8e2cddea0d">VPTransform</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94e1d5306640457b340c5d5045fc3532">EVLParamStrategy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abf988827c40fdf90a1e08a8e2cddea0d">VPTransform</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a077db45fab76ac717888ddd702b6f9bf">OpStrategy</a></td>
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


<p>Definition at line 1833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### VPTransform {#abf988827c40fdf90a1e08a8e2cddea0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetTransformInfo::VPLegalization::VPTransform </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Legal<a id="abf988827c40fdf90a1e08a8e2cddea0da9e7fcc009995c1a76735da3700665aaa"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Discard<a id="abf988827c40fdf90a1e08a8e2cddea0dad89a9e5c9cb303fe1dedf3a40d899015"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Convert<a id="abf988827c40fdf90a1e08a8e2cddea0da2a58508bab01c3fba0c3c912ed82e89d"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1834 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VPLegalization() {#ae8751b629c47f25dc1b3859fbe1d5945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetTransformInfo::VPLegalization::VPLegalization (<a href="#abf988827c40fdf90a1e08a8e2cddea0d">VPTransform</a> EVLParamStrategy, <a href="#abf988827c40fdf90a1e08a8e2cddea0d">VPTransform</a> OpStrategy)</td>
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



<p>Definition at line 1858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>References <a href="#a94e1d5306640457b340c5d5045fc3532">EVLParamStrategy</a> and <a href="#a077db45fab76ac717888ddd702b6f9bf">OpStrategy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### shouldDoNothing() {#a8fbed0c5e7548b5ea557657b56109ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetTransformInfo::VPLegalization::shouldDoNothing ()</td>
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



<p>Definition at line 1855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>References <a href="#a94e1d5306640457b340c5d5045fc3532">EVLParamStrategy</a>, <a href="#abf988827c40fdf90a1e08a8e2cddea0da9e7fcc009995c1a76735da3700665aaa">Legal</a> and <a href="#a077db45fab76ac717888ddd702b6f9bf">OpStrategy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### EVLParamStrategy {#a94e1d5306640457b340c5d5045fc3532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPTransform llvm::TargetTransformInfo::VPLegalization::EVLParamStrategy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-expandvectorpredication-cpp-/#aedba47828740c9315142ae92e6e901ae">anonymous{ExpandVectorPredication.cpp}::sanitizeStrategy</a>, <a href="#a8fbed0c5e7548b5ea557657b56109ddf">shouldDoNothing</a> and <a href="#ae8751b629c47f25dc1b3859fbe1d5945">VPLegalization</a>.</p>

</div>
</div>

### OpStrategy {#a077db45fab76ac717888ddd702b6f9bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPTransform llvm::TargetTransformInfo::VPLegalization::OpStrategy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-expandvectorpredication-cpp-/#aedba47828740c9315142ae92e6e901ae">anonymous{ExpandVectorPredication.cpp}::sanitizeStrategy</a>, <a href="#a8fbed0c5e7548b5ea557657b56109ddf">shouldDoNothing</a> and <a href="#ae8751b629c47f25dc1b3859fbe1d5945">VPLegalization</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
