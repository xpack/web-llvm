---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{AMDGPULowerKernelAttributes.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{AMDGPULowerKernelAttributes.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelattributes-cpp-/amdgpulowerkernelattributes">AMDGPULowerKernelAttributes</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DispatchPackedOffsets { <a href="#af445065482fe4ec1995fb5ad2986b48e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ImplicitArgOffsets { <a href="#ae65db8fb30d545b846afe720bc1dcd9b">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacdc4383087b03e687cc89e6a14147c7">getBasePtrIntrinsic</a> (Module &amp;M, bool IsV5OrAbove)</td>
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

## Enumerations

### DispatchPackedOffsets {#af445065482fe4ec1995fb5ad2986b48e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AMDGPULowerKernelAttributes.cpp}::DispatchPackedOffsets </td>
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
<td class="doxyEnumItemName">WORKGROUP_SIZE_X<a id="af445065482fe4ec1995fb5ad2986b48ea3fc0d24956fed035916c3731b0a97b3f"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WORKGROUP_SIZE_Y<a id="af445065482fe4ec1995fb5ad2986b48ea7c79e4df993a0a2393ca9304182c1454"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WORKGROUP_SIZE_Z<a id="af445065482fe4ec1995fb5ad2986b48eaacdd008a0965560c2fd4c292f92b02e1"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GRID_SIZE_X<a id="af445065482fe4ec1995fb5ad2986b48ea48f2b7dc8c27fc49568d9a634fce124c"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GRID_SIZE_Y<a id="af445065482fe4ec1995fb5ad2986b48eabab0e2301d5826c28d78bfa7760796f6"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GRID_SIZE_Z<a id="af445065482fe4ec1995fb5ad2986b48ea1ea8d13231aaf2f47426d98e6db17321"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp">AMDGPULowerKernelAttributes.cpp</a>.</p>

</div>
</div>

### ImplicitArgOffsets {#ae65db8fb30d545b846afe720bc1dcd9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AMDGPULowerKernelAttributes.cpp}::ImplicitArgOffsets </td>
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
<td class="doxyEnumItemName">HIDDEN_BLOCK_COUNT_X<a id="ae65db8fb30d545b846afe720bc1dcd9bacc7438cd63022de438a96822be793983"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_BLOCK_COUNT_Y<a id="ae65db8fb30d545b846afe720bc1dcd9bae319b2f467b2ce736c795b2ace3d126f"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_BLOCK_COUNT_Z<a id="ae65db8fb30d545b846afe720bc1dcd9ba1a930fa809a646dcaad33a6a91b26b86"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_GROUP_SIZE_X<a id="ae65db8fb30d545b846afe720bc1dcd9badea09ba09d91c85ca362087393e4b8fd"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_GROUP_SIZE_Y<a id="ae65db8fb30d545b846afe720bc1dcd9baf5e564c25639ead86aba226347136041"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_GROUP_SIZE_Z<a id="ae65db8fb30d545b846afe720bc1dcd9ba59b88527f863a49db296c65d4d0dfd86"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_REMAINDER_X<a id="ae65db8fb30d545b846afe720bc1dcd9ba31e088641f60fbf2c764c57aae43bf3c"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_REMAINDER_Y<a id="ae65db8fb30d545b846afe720bc1dcd9ba5b1ad5d4228b81d5b1fa3d23eb62c2a6"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HIDDEN_REMAINDER_Z<a id="ae65db8fb30d545b846afe720bc1dcd9ba326729f29d6b5999f8393ff767020cd7"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp">AMDGPULowerKernelAttributes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getBasePtrIntrinsic() {#aacdc4383087b03e687cc89e6a14147c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * anonymous{AMDGPULowerKernelAttributes.cpp}::getBasePtrIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, bool IsV5OrAbove)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp">AMDGPULowerKernelAttributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aa1731508126b77035ab3ba9d71d5374b">llvm::Intrinsic::getDeclarationIfExists</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelattributes-cpp-/amdgpulowerkernelattributes/#aaf10937fb0ffaa2b0bfa200597266f2e">anonymous{AMDGPULowerKernelAttributes.cpp}::AMDGPULowerKernelAttributes::runOnModule</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp">AMDGPULowerKernelAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
