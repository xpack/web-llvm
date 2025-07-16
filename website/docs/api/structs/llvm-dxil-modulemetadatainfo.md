---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dxil/modulemetadatainfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ModuleMetadataInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::dxil::ModuleMetadataInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">llvm/Analysis/DXILMetadataAnalysis.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89522dcd8c7e60779d4d260b48f921d6">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a62d160380d89f3f82498f97b8d3a72">DXILVersion</a> {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72d75f84e6099e4c6bb067bfd824286d">ShaderModelVersion</a> {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324">Triple::EnvironmentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bad270d95b4ab28934581322924b837">ShaderProfile</a> {<a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a6c32bcd90dff79307baf3147697ae1d3">Triple::UnknownEnvironment</a>}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc9afd91bef9017b2e5b78eaf16f0d6a">ValidatorVersion</a> {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties">EntryProperties</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff85239033e722633887ccf83cd0f6ce">EntryPropertyVec</a> {}</td>
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


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">DXILMetadataAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### print() {#a89522dcd8c7e60779d4d260b48f921d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleMetadataInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">DXILMetadataAnalysis.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp">DXILMetadataAnalysis.cpp</a>.</p>


<p>References <a href="#a4a62d160380d89f3f82498f97b8d3a72">DXILVersion</a>, <a href="#aff85239033e722633887ccf83cd0f6ce">EntryPropertyVec</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#abb703efa7aa5bddf5875fe8f2517e787">llvm::Triple::getEnvironmentTypeName</a>, <a href="#a72d75f84e6099e4c6bb067bfd824286d">ShaderModelVersion</a>, <a href="#a6bad270d95b4ab28934581322924b837">ShaderProfile</a> and <a href="#afc9afd91bef9017b2e5b78eaf16f0d6a">ValidatorVersion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DXILVersion {#a4a62d160380d89f3f82498f97b8d3a72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple llvm::dxil::ModuleMetadataInfo::DXILVersion {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">DXILMetadataAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp/#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a28b9ee98753ce0b4d46a48966e2b681f">emitDXILVersionTupleMD</a> and <a href="#a89522dcd8c7e60779d4d260b48f921d6">print</a>.</p>

</div>
</div>

### EntryPropertyVec {#aff85239033e722633887ccf83cd0f6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;EntryProperties&gt; llvm::dxil::ModuleMetadataInfo::EntryPropertyVec {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">DXILMetadataAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp/#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a>, <a href="#a89522dcd8c7e60779d4d260b48f921d6">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>.</p>

</div>
</div>

### ShaderModelVersion {#a72d75f84e6099e4c6bb067bfd824286d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple llvm::dxil::ModuleMetadataInfo::ShaderModelVersion {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">DXILMetadataAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp/#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#aff40ddd6d0fc8a142d051bce619c2dee">emitShaderModelVersionMD</a> and <a href="#a89522dcd8c7e60779d4d260b48f921d6">print</a>.</p>

</div>
</div>

### ShaderProfile {#a6bad270d95b4ab28934581322924b837}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::EnvironmentType llvm::dxil::ModuleMetadataInfo::ShaderProfile {<a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a6c32bcd90dff79307baf3147697ae1d3">Triple::UnknownEnvironment</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">DXILMetadataAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp/#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#aff40ddd6d0fc8a142d051bce619c2dee">emitShaderModelVersionMD</a>, <a href="#a89522dcd8c7e60779d4d260b48f921d6">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>.</p>

</div>
</div>

### ValidatorVersion {#afc9afd91bef9017b2e5b78eaf16f0d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple llvm::dxil::ModuleMetadataInfo::ValidatorVersion {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">DXILMetadataAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp/#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a56e0b5e985245544c7a37011c9e19805">emitValidatorVersionMD</a>, <a href="#a89522dcd8c7e60779d4d260b48f921d6">print</a> and <a href="/web-llvm/docs/api/classes/anonymous-dxilprepare-cpp-/dxilpreparemodule/#a6bcc20d3d2e7ec05e259efe87ba8fd0c">anonymous{DXILPrepare.cpp}::DXILPrepareModule::runOnModule</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">DXILMetadataAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp">DXILMetadataAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
