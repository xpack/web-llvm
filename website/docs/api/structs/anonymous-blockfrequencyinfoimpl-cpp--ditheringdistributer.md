---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-blockfrequencyinfoimpl-cpp-/ditheringdistributer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DitheringDistributer` Struct Reference

<p>Dithering mass distributer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{BlockFrequencyInfoImpl.cpp}::DitheringDistributer { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09b288abbf093b5ee513ce99b8921c72">DitheringDistributer</a> (Distribution &amp;Dist, const BlockMass &amp;Mass)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf138cba5a790381de6f4356e4f4386e">takeMass</a> (uint32_t Weight)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6c0133daebcc1cc43d268690dd76ebd">RemWeight</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515a4de69fa4a07d16c0692e3cef1207">RemMass</a></td>
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

<p>Dithering mass distributer.</p>


<p>This class splits up a single mass into portions by weight, dithering to spread out error. No mass is lost. The dithering precision depends on the precision of the product of <em><a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a></em> and <em><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></em>.</p>


<p>The distribution algorithm follows.</p>


<ol class="doxyList" type="1">
<li>Initialize by saving the sum of the weights in <em>RemWeight</em> and the mass to distribute in <em>RemMass</em>.</li>
<li>For each portion:

<ol class="doxyList" type="1">
<li>Construct a branch probability, P, as the portion's weight divided by the current value of <em>RemWeight</em>.</li>
<li>Calculate the portion's mass as <em>RemMass</em> times P.</li>
<li>Update <em>RemWeight</em> and <em>RemMass</em> at each portion by subtracting the current portion's weight and mass.</li>
</ol></li>
</ol>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DitheringDistributer() {#a09b288abbf093b5ee513ce99b8921c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DitheringDistributer::DitheringDistributer (<a href="/web-llvm/docs/api/namespaces/anonymous-blockfrequencyinfoimpl-cpp-/#a03c5183992b1c37a3db46deb244a3b72">Distribution</a> &amp; Dist, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a> &amp; Mass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/distribution/#ac24f62f9ac4bff8273ed15798ea650e8">llvm::BlockFrequencyInfoImplBase::Distribution::normalize</a>, <a href="#a515a4de69fa4a07d16c0692e3cef1207">RemMass</a>, <a href="#ae6c0133daebcc1cc43d268690dd76ebd">RemWeight</a> and <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/distribution/#aaf226952008495c98bd9d9652b25cfd8">llvm::BlockFrequencyInfoImplBase::Distribution::Total</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### takeMass() {#abf138cba5a790381de6f4356e4f4386e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockMass DitheringDistributer::takeMass (uint32_t Weight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a515a4de69fa4a07d16c0692e3cef1207">RemMass</a> and <a href="#ae6c0133daebcc1cc43d268690dd76ebd">RemWeight</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### RemMass {#a515a4de69fa4a07d16c0692e3cef1207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockMass anonymous{BlockFrequencyInfoImpl.cpp}::DitheringDistributer::RemMass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<p>Referenced by <a href="#a09b288abbf093b5ee513ce99b8921c72">DitheringDistributer</a> and <a href="#abf138cba5a790381de6f4356e4f4386e">takeMass</a>.</p>

</div>
</div>

### RemWeight {#ae6c0133daebcc1cc43d268690dd76ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{BlockFrequencyInfoImpl.cpp}::DitheringDistributer::RemWeight</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<p>Referenced by <a href="#a09b288abbf093b5ee513ce99b8921c72">DitheringDistributer</a> and <a href="#abf138cba5a790381de6f4356e4f4386e">takeMass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
