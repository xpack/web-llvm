---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/nvptx/ptxcvtmode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `PTXCvtMode` Namespace

<p><a href="/web-llvm/docs/api/namespaces/llvm/nvptx/ptxcvtmode">PTXCvtMode</a> - Conversion code enumeration. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::NVPTX::PTXCvtMode { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CvtMode { <a href="#ad81eb7557182862503894d8bc5e8328f">...</a> }</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/nvptx/ptxcvtmode">PTXCvtMode</a> - Conversion code enumeration.</p>

<div class="doxySectionDef">

## Enumerations

### CvtMode {#ad81eb7557182862503894d8bc5e8328f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::NVPTX::PTXCvtMode::CvtMode </td>
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
<td class="doxyEnumItemName">NONE<a id="ad81eb7557182862503894d8bc5e8328fa8cbf1f847ac9629989d7daaa6dc57c66"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RNI<a id="ad81eb7557182862503894d8bc5e8328fa083f763df45b766bd308be4101529bd4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RZI<a id="ad81eb7557182862503894d8bc5e8328faa495048e332a657aa1fd09005ca374e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RMI<a id="ad81eb7557182862503894d8bc5e8328fa5916b6d1eac7f30c7f7f84e2a3f79af6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RPI<a id="ad81eb7557182862503894d8bc5e8328fabed14095422ca68c13ae216fe4edb9c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RN<a id="ad81eb7557182862503894d8bc5e8328fa3075a56e6cfcf4ac3328185fa11201b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RZ<a id="ad81eb7557182862503894d8bc5e8328fadf6cb3d17aeace3749932c7166e349cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RM<a id="ad81eb7557182862503894d8bc5e8328fab649a92948d9ef9d051acb0681fea44a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RP<a id="ad81eb7557182862503894d8bc5e8328fa8b204d090788e956d6011920f4916191"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RNA<a id="ad81eb7557182862503894d8bc5e8328fad96be88264769b164b2cfc0c3a2ad4f0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BASE_MASK<a id="ad81eb7557182862503894d8bc5e8328fa8acdd9ed8bf28d44e7b0716a089c83ce"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FTZ_FLAG<a id="ad81eb7557182862503894d8bc5e8328fa67202a3a62f543ff3715278c8b2501ce"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SAT_FLAG<a id="ad81eb7557182862503894d8bc5e8328faf56ccec2a2d66a2acff262e6a4bbeb92"></a></td>
<td class="doxyEnumItemDescription"> (= 0x20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RELU_FLAG<a id="ad81eb7557182862503894d8bc5e8328fa4aa66cc61939fc9ebdc3d49e2f7a497a"></a></td>
<td class="doxyEnumItemDescription"> (= 0x40)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptx-h">NVPTX.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptx-h">NVPTX.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
