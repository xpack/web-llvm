---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/dxilmetadataanalysis-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DXILMetadataAnalysis.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">llvm/Analysis/DXILMetadataAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo">ModuleMetadataInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a> (Module &amp;M)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"dxil-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuannotateuniformvalues-cpp/#a3cd36c33be3dfbc64aa6da755a47e6b1">metadata</a>-analysis"</td>
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

### collectMetadataInfo() {#ab109200c3fd91dd6bf0176734ad64b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleMetadataInfo collectMetadataInfo (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp">DXILMetadataAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo/#a4a62d160380d89f3f82498f97b8d3a72">llvm::dxil::ModuleMetadataInfo::DXILVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo/#aff85239033e722633887ccf83cd0f6ce">llvm::dxil::ModuleMetadataInfo::EntryPropertyVec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#aa24b566603d206b0e74bf63daf521078">llvm::NamedMDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties/#ade0e0b49d3f1bf9679cf66b2f9735fa7">llvm::dxil::EntryProperties::NumThreadsX</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties/#a98a4f2999870589f7178bb38c9f154c3">llvm::dxil::EntryProperties::NumThreadsY</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties/#a2e0923085a5fa269be7f889ebfd77519">llvm::dxil::EntryProperties::NumThreadsZ</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo/#a72d75f84e6099e4c6bb067bfd824286d">llvm::dxil::ModuleMetadataInfo::ShaderModelVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo/#a6bad270d95b4ab28934581322924b837">llvm::dxil::ModuleMetadataInfo::ShaderProfile</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties/#a8f7e5382c4c1f46067fd94da29fcf7ec">llvm::dxil::EntryProperties::ShaderStage</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo/#afc9afd91bef9017b2e5b78eaf16f0d6a">llvm::dxil::ModuleMetadataInfo::ValidatorVersion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxilmetadataanalysis/#a494a52305b8212849f76af9c26dd291f">llvm::DXILMetadataAnalysis::run</a> and <a href="/web-llvm/docs/api/classes/llvm/dxilmetadataanalysiswrapperpass/#aad12caa09b25a010f5f07a09cccc45b4">llvm::DXILMetadataAnalysisWrapperPass::runOnModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"dxil-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuannotateuniformvalues-cpp/#a3cd36c33be3dfbc64aa6da755a47e6b1">metadata</a>-analysis"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp">DXILMetadataAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
