---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-x86targetparser-cpp-/featureinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FeatureInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{X86TargetParser.cpp}::FeatureInfo { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb4c489f3b7136becc840b8e2916008">getName</a> (bool WithPlus=false) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88852cd2778c29b4f1bcfb50fe08d3d4">NameWithPlus</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86targetparser-cpp-/#a7a59864044a6193b1f7e46d549d03f8e">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d1d7e021ca7b96d43471a6aa399dc87">ImpliedFeatures</a></td>
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


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getName() {#a8bb4c489f3b7136becc840b8e2916008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{X86TargetParser.cpp}::FeatureInfo::getName (bool WithPlus=false)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a88852cd2778c29b4f1bcfb50fe08d3d4">NameWithPlus</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a9a64d327c5a0be28d5936e30ff02709a">llvm::X86::getFeaturesForCPU</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a506819ac2ff216f44dd9674f2bebd80b">llvm::X86::updateImpliedFeatures</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ImpliedFeatures {#a0d1d7e021ca7b96d43471a6aa399dc87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset anonymous{X86TargetParser.cpp}::FeatureInfo::ImpliedFeatures</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>

</div>
</div>

### NameWithPlus {#a88852cd2778c29b4f1bcfb50fe08d3d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral anonymous{X86TargetParser.cpp}::FeatureInfo::NameWithPlus</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>Referenced by <a href="#a8bb4c489f3b7136becc840b8e2916008">getName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
