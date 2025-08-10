---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/scalarizerpassoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ScalarizerPassOptions` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::ScalarizerPassOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/scalarizer-h">llvm/Transforms/Scalar/Scalarizer.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85071425f6006c3a95d13f46fb6f762b">ScalarizeMinBits</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instruct the scalarizer pass to attempt to keep values of a minimum number of bits. <a href="#a85071425f6006c3a95d13f46fb6f762b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe7d64467d2813441304eb8989b4e8f">ScalarizeVariableInsertExtract</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow the scalarizer pass to scalarize insertelement/extractelement with variable index. <a href="#afbe7d64467d2813441304eb8989b4e8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c426bfd7bd7c6fd835516dc4b3d5616">ScalarizeLoadStore</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow the scalarizer pass to scalarize loads and store. <a href="#a2c426bfd7bd7c6fd835516dc4b3d5616">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/scalarizer-h">Scalarizer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### ScalarizeLoadStore {#a2c426bfd7bd7c6fd835516dc4b3d5616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScalarizerPassOptions::ScalarizeLoadStore = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow the scalarizer pass to scalarize loads and store.</p>


<p>This is disabled by default because having separate loads and stores makes it more likely that the -combiner-alias-analysis limits will be reached.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/scalarizer-h">Scalarizer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/directxpassconfig/#a49845b47cd7ea53506680a7419f38f16">DirectXPassConfig::addCodeGenPrepare</a>.</p>

</div>
</div>

### ScalarizeMinBits {#a85071425f6006c3a95d13f46fb6f762b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScalarizerPassOptions::ScalarizeMinBits = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Instruct the scalarizer pass to attempt to keep values of a minimum number of bits.</p>


<p>Split vectors larger than this size into fragments, where each fragment is either a vector no larger than this size or a scalar.</p>


<p>Instructions with operands or results of different sizes that would be split into a different number of fragments are currently left as-is.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/scalarizer-h">Scalarizer.h</a>.</p>

</div>
</div>

### ScalarizeVariableInsertExtract {#afbe7d64467d2813441304eb8989b4e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScalarizerPassOptions::ScalarizeVariableInsertExtract = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow the scalarizer pass to scalarize insertelement/extractelement with variable index.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/scalarizer-h">Scalarizer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/scalarizer-h">Scalarizer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
