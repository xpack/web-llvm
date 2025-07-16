---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/featurebitarray
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FeatureBitArray` Class Reference

<p>Class used to store the subtarget bits in the tables created by tablegen. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FeatureBitArray { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">llvm/TargetParser/SubtargetFeature.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Container class for subtarget features. <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affce0efa9230570ce4a0790c6555aa18">FeatureBitArray</a> (const std::array&lt; uint64_t, MAX_SUBTARGET_WORDS &gt; &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4a0360586ccc1be7d8ec4e824778e1a">getAsBitset</a> () const</td>
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

<p>Class used to store the subtarget bits in the tables created by tablegen.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FeatureBitArray() {#affce0efa9230570ce4a0790c6555aa18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FeatureBitArray::FeatureBitArray (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::array&lt; uint64_t, <a href="/web-llvm/docs/api/namespaces/llvm/#aba72d8ae24eb61078096f50ae780bd30">MAX_SUBTARGET_WORDS</a> &gt; &amp; B)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a0e07d5143362d63a8202333029b280e8">llvm::FeatureBitset::FeatureBitset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAsBitset() {#ac4a0360586ccc1be7d8ec4e824778e1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FeatureBitset &amp; llvm::FeatureBitArray::getAsBitset ()</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a0e07d5143362d63a8202333029b280e8">llvm::FeatureBitset::FeatureBitset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#a00ea531f15b6ca7bac68acbd9e89082d">ApplyFeatureFlag</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuremoveincompatiblefunctions-cpp-/amdgpuremoveincompatiblefunctions/#a9910118e4db5bb56e348017ba1460553">anonymous{AMDGPURemoveIncompatibleFunctions.cpp}::AMDGPURemoveIncompatibleFunctions::checkFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#aedfa5e387d929b78090c06db5e0965e2">getFeatures</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a2624192c54a92722351fa791af3e862d">llvm::MCSubtargetInfo::ToggleFeature</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
