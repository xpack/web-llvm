---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DXILTranslateMetadata.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-h">DXILTranslateMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceanalysis-h">DXILResourceAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilshaderflags-h">DXILShaderFlags.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directx-h">DirectX.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilmetadataanalysis-h">llvm/Analysis/DXILMetadataAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">llvm/Analysis/DXILResource.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticprinter-h">llvm/IR/DiagnosticPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/versiontuple-h">llvm/Support/VersionTuple.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;cstdint&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-">anonymous{DXILTranslateMetadata.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dxiltranslatemetadata-cpp-/diagnosticinfotranslatemd">DiagnosticInfoTranslateMD</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A simple Wrapper DiagnosticInfo that generates Module-level diagnostic for TranslateMetadata pass. <a href="/web-llvm/docs/api/classes/anonymous-dxiltranslatemetadata-cpp-/diagnosticinfotranslatemd/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dxiltranslatemetadata-cpp-/dxiltranslatemetadatalegacy">DXILTranslateMetadataLegacy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a> (Module &amp;M, DXILBindingMap &amp;DBM, DXILResourceTypeMap &amp;DRTM, const dxil::Resources &amp;MDResources)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadb42b9dfc2f8444a3ba9835db06f974">getShortShaderStage</a> (Triple::EnvironmentType Env)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0c29ccbe6f065d87e38e21d3eb9f747">getShaderStage</a> (Triple::EnvironmentType Env)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ed0896d98a0b530d38c48bdd0985e00">getTagValueAsMetadata</a> (EntryPropsTag Tag, uint64_t Value, LLVMContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a529578790bc8de8b220cef2ca6becef1">getEntryPropAsMetadata</a> (const EntryProperties &amp;EP, uint64_t EntryShaderFlags, const Triple::EnvironmentType ShaderProfile)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcb7e087ebdb7b3e360160af660827c7">constructEntryMetadata</a> (const Function *EntryFn, MDTuple *Signatures, MDNode *Resources, MDTuple *Properties, LLVMContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd3a382f7ecb233b53ad4e1b44db01e3">emitEntryMD</a> (const EntryProperties &amp;EP, MDTuple *Signatures, MDNode *MDResources, const uint64_t EntryShaderFlags, const Triple::EnvironmentType ShaderProfile)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56e0b5e985245544c7a37011c9e19805">emitValidatorVersionMD</a> (Module &amp;M, const ModuleMetadataInfo &amp;MMDI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff40ddd6d0fc8a142d051bce619c2dee">emitShaderModelVersionMD</a> (Module &amp;M, const ModuleMetadataInfo &amp;MMDI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b9ee98753ce0b4d46a48966e2b681f">emitDXILVersionTupleMD</a> (Module &amp;M, const ModuleMetadataInfo &amp;MMDI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b4f1fd2e48e328abe9d5ed440df222">emitTopLevelLibraryNode</a> (Module &amp;M, MDNode *RMD, uint64_t ShaderFlags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab10b653a914cecca232400be7a563633">translateBranchMetadata</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a> (Module &amp;M, DXILBindingMap &amp;DBM, DXILResourceTypeMap &amp;DRTM, const Resources &amp;MDResources, const ModuleShaderFlags &amp;ShaderFlags, const ModuleMetadataInfo &amp;MMDI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90d937bdea112bd5a0265434e6385967">INITIALIZE_PASS_BEGIN</a> (DXILTranslateMetadataLegacy, "dxil-translate-metadata", "DXIL Translate Metadata", false, false) INITIALIZE_PASS_END(DXILTranslateMetadataLegacy</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">dxil translate</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f3832d0c0d6fb4604dcf32295798d6">metadata</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">dxil translate DXIL Translate</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b689be9525270658579553e0adfec1">Metadata</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">dxil translate DXIL Translate</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae57a548989a5304d4541c26388cab8d5">false</a></td>
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

### constructEntryMetadata() {#adcb7e087ebdb7b3e360160af660827c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDTuple * constructEntryMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * EntryFn, <a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a> * Signatures, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Resources, <a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a> * Properties, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a8efadc1e398432637936757b43272daa">Signatures</a>.</p>


<p>Referenced by <a href="#acd3a382f7ecb233b53ad4e1b44db01e3">emitEntryMD</a> and <a href="#a62b4f1fd2e48e328abe9d5ed440df222">emitTopLevelLibraryNode</a>.</p>

</div>
</div>

### emitDXILVersionTupleMD() {#a28b9ee98753ce0b4d46a48966e2b681f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitDXILVersionTupleMD (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo">ModuleMetadataInfo</a> &amp; MMDI)</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#ae917c72e5b8e15491cd0dbdd44d818f2">llvm::NamedMDNode::addOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo/#a4a62d160380d89f3f82498f97b8d3a72">llvm::dxil::ModuleMetadataInfo::DXILVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a56a72b8793b8e0df7217c9b19a83320b">llvm::VersionTuple::getMajor</a> and <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#af16679f141c8a480a1e6dcc0b8bcf5de">llvm::VersionTuple::getMinor</a>.</p>


<p>Referenced by <a href="#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>.</p>

</div>
</div>

### emitEntryMD() {#acd3a382f7ecb233b53ad4e1b44db01e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDTuple * emitEntryMD (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties">EntryProperties</a> &amp; EP, <a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a> * Signatures, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MDResources, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t EntryShaderFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324">Triple::EnvironmentType</a> ShaderProfile)</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>References <a href="#adcb7e087ebdb7b3e360160af660827c7">constructEntryMetadata</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties/#a0e98ab83d32b6f2687b3ce63fb198009">llvm::dxil::EntryProperties::Entry</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="#a529578790bc8de8b220cef2ca6becef1">getEntryPropAsMetadata</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a8efadc1e398432637936757b43272daa">Signatures</a>.</p>


<p>Referenced by <a href="#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>.</p>

</div>
</div>

### emitResourceMetadata() {#a75f9b9721a2718d692fd3805c713f2ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedMDNode * emitResourceMetadata (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/dxilbindingmap">DXILBindingMap</a> &amp; DBM, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcetypemap">DXILResourceTypeMap</a> &amp; DRTM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dxil/resources">dxil::Resources</a> &amp; MDResources)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#ae917c72e5b8e15491cd0dbdd44d818f2">llvm::NamedMDNode::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilbindingmap/#a09b441646cb8c12800c253403d6c5f21">llvm::DXILBindingMap::cbuffers</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilbindingmap/#a6e54b766c239100a4742f07c8edf440a">llvm::DXILBindingMap::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resources/#af3c0f21d561d7cb2b2b9858f1b8744ae">llvm::dxil::Resources::hasCBuffers</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resources/#a87bafd9a99b84743b04303b76e1763eb">llvm::dxil::Resources::hasUAVs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilbindingmap/#a821ddc9c4832dcfc6c066490fc2400c9">llvm::DXILBindingMap::samplers</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilbindingmap/#a7794c7fbe171e5c70d604343647e9436">llvm::DXILBindingMap::srvs</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilbindingmap/#ad2aff0b0669895df82de56ea93641d40">llvm::DXILBindingMap::uavs</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resources/#ad7d5b4cdb8c489feec505196bcb942db">llvm::dxil::Resources::writeCBuffers</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/resources/#a31b258c14fec4519676f1ca9c51516ad">llvm::dxil::Resources::writeUAVs</a>.</p>


<p>Referenced by <a href="#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>.</p>

</div>
</div>

### emitShaderModelVersionMD() {#aff40ddd6d0fc8a142d051bce619c2dee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitShaderModelVersionMD (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo">ModuleMetadataInfo</a> &amp; MMDI)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#ae917c72e5b8e15491cd0dbdd44d818f2">llvm::NamedMDNode::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a56a72b8793b8e0df7217c9b19a83320b">llvm::VersionTuple::getMajor</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#af16679f141c8a480a1e6dcc0b8bcf5de">llvm::VersionTuple::getMinor</a>, <a href="#aadb42b9dfc2f8444a3ba9835db06f974">getShortShaderStage</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo/#a72d75f84e6099e4c6bb067bfd824286d">llvm::dxil::ModuleMetadataInfo::ShaderModelVersion</a> and <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo/#a6bad270d95b4ab28934581322924b837">llvm::dxil::ModuleMetadataInfo::ShaderProfile</a>.</p>


<p>Referenced by <a href="#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>.</p>

</div>
</div>

### emitTopLevelLibraryNode() {#a62b4f1fd2e48e328abe9d5ed440df222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDTuple * emitTopLevelLibraryNode (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * RMD, uint64_t ShaderFlags)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="#adcb7e087ebdb7b3e360160af660827c7">constructEntryMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="#a7ed0896d98a0b530d38c48bdd0985e00">getTagValueAsMetadata</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580a9070f5809548d43abb03bf9a5307ddbc">anonymous{DXILTranslateMetadata.cpp}::ShaderFlags</a>.</p>


<p>Referenced by <a href="#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>.</p>

</div>
</div>

### emitValidatorVersionMD() {#a56e0b5e985245544c7a37011c9e19805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitValidatorVersionMD (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo">ModuleMetadataInfo</a> &amp; MMDI)</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#ae917c72e5b8e15491cd0dbdd44d818f2">llvm::NamedMDNode::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#ad2c0af191fb0d4aff661994b0d234e40">llvm::NamedMDNode::clearOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#ad07e5841d788dc29bdda972b3f92be6b">llvm::VersionTuple::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a56a72b8793b8e0df7217c9b19a83320b">llvm::VersionTuple::getMajor</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#af16679f141c8a480a1e6dcc0b8bcf5de">llvm::VersionTuple::getMinor</a> and <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo/#afc9afd91bef9017b2e5b78eaf16f0d6a">llvm::dxil::ModuleMetadataInfo::ValidatorVersion</a>.</p>


<p>Referenced by <a href="#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>.</p>

</div>
</div>

### getEntryPropAsMetadata() {#a529578790bc8de8b220cef2ca6becef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDTuple * getEntryPropAsMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties">EntryProperties</a> &amp; EP, uint64_t EntryShaderFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324">Triple::EnvironmentType</a> ShaderProfile)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a35a7d7865588f76c4f300fb1f07ee1bc">llvm::Triple::Compute</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties/#a0e98ab83d32b6f2687b3ce63fb198009">llvm::dxil::EntryProperties::Entry</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="#ad0c29ccbe6f065d87e38e21d3eb9f747">getShaderStage</a>, <a href="#a7ed0896d98a0b530d38c48bdd0985e00">getTagValueAsMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a38ed328b8551b06c5a133e54867110bf">llvm::Triple::Library</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580a97b726142463c564db260b0b7a67c584">anonymous{DXILTranslateMetadata.cpp}::NumThreads</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties/#ade0e0b49d3f1bf9679cf66b2f9735fa7">llvm::dxil::EntryProperties::NumThreadsX</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties/#a98a4f2999870589f7178bb38c9f154c3">llvm::dxil::EntryProperties::NumThreadsY</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties/#a2e0923085a5fa269be7f889ebfd77519">llvm::dxil::EntryProperties::NumThreadsZ</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580a9070f5809548d43abb03bf9a5307ddbc">anonymous{DXILTranslateMetadata.cpp}::ShaderFlags</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580ab5cdda8a27ae9e95e3a4da9277d83656">anonymous{DXILTranslateMetadata.cpp}::ShaderKind</a> and <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties/#a8f7e5382c4c1f46067fd94da29fcf7ec">llvm::dxil::EntryProperties::ShaderStage</a>.</p>


<p>Referenced by <a href="#acd3a382f7ecb233b53ad4e1b44db01e3">emitEntryMD</a>.</p>

</div>
</div>

### getShaderStage() {#ad0c29ccbe6f065d87e38e21d3eb9f747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t getShaderStage (<a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324">Triple::EnvironmentType</a> Env)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a4bd403d91c4535171833f92e0ce36137">llvm::Triple::Pixel</a>.</p>


<p>Referenced by <a href="#a529578790bc8de8b220cef2ca6becef1">getEntryPropAsMetadata</a>.</p>

</div>
</div>

### getShortShaderStage() {#aadb42b9dfc2f8444a3ba9835db06f974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getShortShaderStage (<a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324">Triple::EnvironmentType</a> Env)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ab926bec66aeb0288525973f203bcb94a">llvm::Triple::Amplification</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a35a7d7865588f76c4f300fb1f07ee1bc">llvm::Triple::Compute</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a9250a1f506b7407b838bf0b494f9cd33">llvm::Triple::Domain</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ade3aad57a34a47654ebeee1a2d4ab960">llvm::Triple::Geometry</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ac8bc9b9934c75b722dcdde3b705c0a51">llvm::Triple::Hull</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a38ed328b8551b06c5a133e54867110bf">llvm::Triple::Library</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324aa1a97c079fbb80fcd9ab0f5fa24f3025">llvm::Triple::Mesh</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a4bd403d91c4535171833f92e0ce36137">llvm::Triple::Pixel</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a71b983b2a1bf8a46c5ac7d21de26fb4a">llvm::Triple::Vertex</a>.</p>


<p>Referenced by <a href="#aff40ddd6d0fc8a142d051bce619c2dee">emitShaderModelVersionMD</a> and <a href="#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>.</p>

</div>
</div>

### getTagValueAsMetadata() {#a7ed0896d98a0b530d38c48bdd0985e00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Metadata * &gt; getTagValueAsMetadata (EntryPropsTag Tag, uint64_t Value, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580a3956aea621637d679b7152ac37f36749">anonymous{DXILTranslateMetadata.cpp}::ASStateTag</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580ab187dbbda584b10126dc88fb9358ba2a">anonymous{DXILTranslateMetadata.cpp}::AutoBindingSpace</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580a1a253d4f691a44ceb94d4af389109622">anonymous{DXILTranslateMetadata.cpp}::DSState</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580aafe857990dc1f9c49cd83d68f880e0f6">anonymous{DXILTranslateMetadata.cpp}::EntryRootSig</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580a694fb9cd3119cd48eb400da7e98ac93d">anonymous{DXILTranslateMetadata.cpp}::GSState</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580a872d18f1e7a0c9ff08eeabb4ec4b806d">anonymous{DXILTranslateMetadata.cpp}::HSState</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580a531b340912f794120fe622da81f66506">anonymous{DXILTranslateMetadata.cpp}::MSState</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580a97b726142463c564db260b0b7a67c584">anonymous{DXILTranslateMetadata.cpp}::NumThreads</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580a74de82d30260210d73ad1688595d7ea3">anonymous{DXILTranslateMetadata.cpp}::RayAttribSize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580aa27a45591bd55648a0db5ff232ffbb1c">anonymous{DXILTranslateMetadata.cpp}::RayPayloadSize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580a9070f5809548d43abb03bf9a5307ddbc">anonymous{DXILTranslateMetadata.cpp}::ShaderFlags</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580ab5cdda8a27ae9e95e3a4da9277d83656">anonymous{DXILTranslateMetadata.cpp}::ShaderKind</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dxiltranslatemetadata-cpp-/#a727514c8260cb30e2d8c17e735a46580a0236ab2f9f473646afbfef7c104a4cf9">anonymous{DXILTranslateMetadata.cpp}::WaveSize</a>.</p>


<p>Referenced by <a href="#a62b4f1fd2e48e328abe9d5ed440df222">emitTopLevelLibraryNode</a> and <a href="#a529578790bc8de8b220cef2ca6becef1">getEntryPropAsMetadata</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a90d937bdea112bd5a0265434e6385967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (DXILTranslateMetadataLegacy, "dxil-translate-metadata", "DXIL Translate Metadata", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### translateBranchMetadata() {#ab10b653a914cecca232400be7a563633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void translateBranchMetadata (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a3c8d885c5746db440058fc8a285126b2">llvm::MDBuilder::createConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a7939b917f71d9664707d8ec51da88418">llvm::MDBuilder::createString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9247a212ea89acc9573fa7e7f557eaba">llvm::Instruction::setMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxiltranslatemetadata/#a11fd26b2f007c308546f237ba5918bc5">llvm::DXILTranslateMetadata::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-dxiltranslatemetadata-cpp-/dxiltranslatemetadatalegacy/#a697fcfe76ef1dfd679fa0c9400f89a03">anonymous{DXILTranslateMetadata.cpp}::DXILTranslateMetadataLegacy::runOnModule</a>.</p>

</div>
</div>

### translateMetadata() {#a52ad1f2fa223473029d3b3535029d7e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void translateMetadata (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/dxilbindingmap">DXILBindingMap</a> &amp; DBM, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcetypemap">DXILResourceTypeMap</a> &amp; DRTM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dxil/resources">Resources</a> &amp; MDResources, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxil/moduleshaderflags">ModuleShaderFlags</a> &amp; ShaderFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo">ModuleMetadataInfo</a> &amp; MMDI)</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#ae917c72e5b8e15491cd0dbdd44d818f2">llvm::NamedMDNode::addOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiltranslatemetadata-cpp-/diagnosticinfotranslatemd/#ae7955808c28e0adbac3500b4638239f3">anonymous{DXILTranslateMetadata.cpp}::DiagnosticInfoTranslateMD::DiagnosticInfoTranslateMD</a>, <a href="#a28b9ee98753ce0b4d46a48966e2b681f">emitDXILVersionTupleMD</a>, <a href="#acd3a382f7ecb233b53ad4e1b44db01e3">emitEntryMD</a>, <a href="#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a>, <a href="#aff40ddd6d0fc8a142d051bce619c2dee">emitShaderModelVersionMD</a>, <a href="#a62b4f1fd2e48e328abe9d5ed440df222">emitTopLevelLibraryNode</a>, <a href="#a56e0b5e985245544c7a37011c9e19805">emitValidatorVersionMD</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties/#a0e98ab83d32b6f2687b3ce63fb198009">llvm::dxil::EntryProperties::Entry</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo/#aff85239033e722633887ccf83cd0f6ce">llvm::dxil::ModuleMetadataInfo::EntryPropertyVec</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#abb703efa7aa5bddf5875fe8f2517e787">llvm::Triple::getEnvironmentTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#aa24b566603d206b0e74bf63daf521078">llvm::NamedMDNode::getOperand</a>, <a href="#aadb42b9dfc2f8444a3ba9835db06f974">getShortShaderStage</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a38ed328b8551b06c5a133e54867110bf">llvm::Triple::Library</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo/#a6bad270d95b4ab28934581322924b837">llvm::dxil::ModuleMetadataInfo::ShaderProfile</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/entryproperties/#a8f7e5382c4c1f46067fd94da29fcf7ec">llvm::dxil::EntryProperties::ShaderStage</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a8efadc1e398432637936757b43272daa">Signatures</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxiltranslatemetadata/#a11fd26b2f007c308546f237ba5918bc5">llvm::DXILTranslateMetadata::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-dxiltranslatemetadata-cpp-/dxiltranslatemetadatalegacy/#a697fcfe76ef1dfd679fa0c9400f89a03">anonymous{DXILTranslateMetadata.cpp}::DXILTranslateMetadataLegacy::runOnModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### false {#ae57a548989a5304d4541c26388cab8d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil translate DXIL Translate false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>

</div>
</div>

### metadata {#a36f3832d0c0d6fb4604dcf32295798d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil translate metadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>

</div>
</div>

### Metadata {#a26b689be9525270658579553e0adfec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil translate DXIL Translate Metadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp">DXILTranslateMetadata.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler/#a68786afa1abe6cfdf9895169bbf8b1a8">llvm::TimeTraceProfiler::begin</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
