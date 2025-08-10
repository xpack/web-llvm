---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-targetparser-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{TargetParser.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{TargetParser.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-targetparser-cpp-/gpuinfo">GPUInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-targetparser-cpp-/gpuinfo">GPUInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb029bce98099dc3aa7b90d708e77d0">getArchEntry</a> (AMDGPU::GPUKind AK, ArrayRef&lt; GPUInfo &gt; Table)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/structs/anonymous-targetparser-cpp-/gpuinfo">GPUInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a1fdb4bf9af7ba68c5b264d87f5b1db">R600GPUs</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/structs/anonymous-targetparser-cpp-/gpuinfo">GPUInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a151d37c9a187c5ae3d1a2f38678befbb">AMDGCNGPUs</a>[]</td>
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

## Functions

### getArchEntry() {#a1cb029bce98099dc3aa7b90d708e77d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GPUInfo * anonymous{TargetParser.cpp}::getArchEntry (<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0">AMDGPU::GPUKind</a> AK, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-targetparser-cpp-/gpuinfo">GPUInfo</a> &gt; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/targetparser-cpp">TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab3ce256a44f1bb0818f863e4838e5cb1a2248e99dd6bf2c1aa7f1a8daf45cd5eb">llvm::AMDGPU::FEATURE_NONE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/anonymous-targetparser-cpp-/gpuinfo/#a90146edfb118f503718c78ea350bc19d">anonymous{TargetParser.cpp}::GPUInfo::Kind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abffe571058efed5bc48a2eecaf9eb8df">llvm::AMDGPU::getArchAttrAMDGCN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae5aa1b472c4fc8f27abc78861ad7e5a7">llvm::AMDGPU::getArchAttrR600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abdda436b916531b2103dbcc64325c1b9">llvm::AMDGPU::getArchNameAMDGCN</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a00f426afe94474a8c7933eaa97f1db71">llvm::AMDGPU::getArchNameR600</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AMDGCNGPUs {#a151d37c9a187c5ae3d1a2f38678befbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GPUInfo anonymous{TargetParser.cpp}::AMDGCNGPUs[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/targetparser-cpp">TargetParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7af9698ef8e2fd0bdcafe8c664c52e9e">llvm::AMDGPU::fillValidArchListAMDGCN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abffe571058efed5bc48a2eecaf9eb8df">llvm::AMDGPU::getArchAttrAMDGCN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#abdda436b916531b2103dbcc64325c1b9">llvm::AMDGPU::getArchNameAMDGCN</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a98ac623b540c21285a2307f08fe7d237">llvm::AMDGPU::parseArchAMDGCN</a>.</p>

</div>
</div>

### R600GPUs {#a6a1fdb4bf9af7ba68c5b264d87f5b1db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GPUInfo anonymous{TargetParser.cpp}::R600GPUs[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {{"r600"},    {"r600"},    GK_R600,    FEATURE_NONE },
  {{"rv630"},   {"r600"},    GK_R600,    FEATURE_NONE },
  {{"rv635"},   {"r600"},    GK_R600,    FEATURE_NONE },
  {{"r630"},    {"r630"},    GK_R630,    FEATURE_NONE },
  {{"rs780"},   {"rs880"},   GK_RS880,   FEATURE_NONE },
  {{"rs880"},   {"rs880"},   GK_RS880,   FEATURE_NONE },
  {{"rv610"},   {"rs880"},   GK_RS880,   FEATURE_NONE },
  {{"rv620"},   {"rs880"},   GK_RS880,   FEATURE_NONE },
  {{"rv670"},   {"rv670"},   GK_RV670,   FEATURE_NONE },
  {{"rv710"},   {"rv710"},   GK_RV710,   FEATURE_NONE },
  {{"rv730"},   {"rv730"},   GK_RV730,   FEATURE_NONE },
  {{"rv740"},   {"rv770"},   GK_RV770,   FEATURE_NONE },
  {{"rv770"},   {"rv770"},   GK_RV770,   FEATURE_NONE },
  {{"cedar"},   {"cedar"},   GK_CEDAR,   FEATURE_NONE },
  {{"palm"},    {"cedar"},   GK_CEDAR,   FEATURE_NONE },
  {{"cypress"}, {"cypress"}, GK_CYPRESS, FEATURE_FMA  },
  {{"hemlock"}, {"cypress"}, GK_CYPRESS, FEATURE_FMA  },
  {{"juniper"}, {"juniper"}, GK_JUNIPER, FEATURE_NONE },
  {{"redwood"}, {"redwood"}, GK_REDWOOD, FEATURE_NONE },
  {{"sumo"},    {"sumo"},    GK_SUMO,    FEATURE_NONE },
  {{"sumo2"},   {"sumo"},    GK_SUMO,    FEATURE_NONE },
  {{"barts"},   {"barts"},   GK_BARTS,   FEATURE_NONE },
  {{"caicos"},  {"caicos"},  GK_CAICOS,  FEATURE_NONE },
  {{"aruba"},   {"cayman"},  GK_CAYMAN,  FEATURE_FMA  },
  {{"cayman"},  {"cayman"},  GK_CAYMAN,  FEATURE_FMA  },
  {{"turks"},   {"turks"},   GK_TURKS,   FEATURE_NONE }
}
</div>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/targetparser-cpp">TargetParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a1dacc9c15858a08654e406335cfeb803">llvm::AMDGPU::fillValidArchListR600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae5aa1b472c4fc8f27abc78861ad7e5a7">llvm::AMDGPU::getArchAttrR600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a00f426afe94474a8c7933eaa97f1db71">llvm::AMDGPU::getArchNameR600</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af396b64f51fe3f71f771dcf36a46dfbc">llvm::AMDGPU::parseArchR600</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/targetparser/targetparser-cpp">TargetParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
