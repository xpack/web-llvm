---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/constantasmetadata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConstantAsMetadata` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ConstantAsMetadata { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valueasmetadata">ValueAsMetadata</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> wrapper in the <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> hierarchy. <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cbd9e338a58f62b38e2b820de8c1e6f">ValueAsMetadata</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05ee54a1cbe68b743401ed2adf040ec8">ConstantAsMetadata</a> (Constant *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f6d3f8f17df8159d8c77860070f41b0">getValue</a> () const</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata">ConstantAsMetadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c720c398a263087e00d7358b05636d5">get</a> (Constant *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata">ConstantAsMetadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d7c23440c7d6dd973cf951949abdd1">getIfExists</a> (Constant *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf7319ea74da6cc88920a880b418ff83">classof</a> (const Metadata *MD)</td>
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


<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<div class="doxySectionDef">

## Friends

### ValueAsMetadata {#a3cbd9e338a58f62b38e2b820de8c1e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata">ValueAsMetadata</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a3cbd9e338a58f62b38e2b820de8c1e6f">ValueAsMetadata</a>.</p>


<p>Referenced by <a href="#a3cbd9e338a58f62b38e2b820de8c1e6f">ValueAsMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ConstantAsMetadata() {#a05ee54a1cbe68b743401ed2adf040ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConstantAsMetadata::ConstantAsMetadata (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
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



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getValue() {#a7f6d3f8f17df8159d8c77860070f41b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::ConstantAsMetadata::getValue ()</td>
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



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#af7494dfd1267d5300f4896c01a28ab71">llvm::ValueAsMetadata::getValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/profilesummary-cpp/#a7a97b2924a1eec42ca579af0ce9de9e4">getSummaryFromMD</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-84210282e313a489b0d86e5b4c554c98/#a67a11cecaffabf1b23f3ec6101056c81">llvm::MDNodeKeyImpl&lt; DISubrange &gt;::isKeyOf</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp/#ac80b26881623b6763d92a8575169ab44">wrapConstantAsMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#adf7319ea74da6cc88920a880b418ff83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantAsMetadata::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a91c7b9c7cf6694f41b9030429b582d26">llvm::Metadata::getMetadataID</a>.</p>

</div>
</div>

### get() {#a4c720c398a263087e00d7358b05636d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantAsMetadata * llvm::ConstantAsMetadata::get (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a6fb0f82a4c2c30df40d31b67ef9f5999">llvm::ValueAsMetadata::getConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#ae1b043855cc598a229a8389f9a116f74">anonymous{NVPTXCtorDtorLowering.cpp}::addKernelMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a0b7601463f25d7904fa9d060ba629a5a">llvm::GlobalObject::addTypeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acd1fbb2df257f945afda92919be322f3">llvm::OpenMPIRBuilder::applySimd</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a9c260f0a51a4c6f936233261cda38455">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::assignLDSKernelIDToEachKernel</a>, <a href="/web-llvm/docs/api/structs/anonymous-crossdsocfi-cpp-/crossdsocfi/#ab29f15fad3f35ea8248e93e3dc805224">anonymous{CrossDSOCFI.cpp}::CrossDSOCFI::buildCFICheck</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a6aa0afd1200f5f282ca02a9ebcf87ca7">llvm::GlobalObject::copyMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp/#aa776b44397de40feb0455262dcd73f70">createAccessTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a0b8b82d8ef44a362f7be889d56121944">llvm::DIBuilder::createBitFieldMemberType</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a3c8d885c5746db440058fc8a285126b2">llvm::MDBuilder::createConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a2236a7be2d15db19f575591000670c9c">llvm::DIBuilder::createInheritance</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acc290ce16055813d4ee68af4c8023a09">llvm::OpenMPIRBuilder::createOffloadEntriesAndInfoMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#a58b3d504dac6f59b0c9bab0ca1084bf7">createRoundingModeDecoration</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#af3cdb326ec386f27b1260b06225ae385">createSaturatedConversionDecoration</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a6bfe058b12abe3443b07d4f4d55d863f">createStringMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#acd2295e6d5f183d1cad636c7a564660e">DisableAllLoopOptsOnLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae744a53dbb2720e5678fb879156761e9">llvm::embedBufferInModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a28b9ee98753ce0b4d46a48966e2b681f">emitDXILVersionTupleMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#aff40ddd6d0fc8a142d051bce619c2dee">emitShaderModelVersionMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a56e0b5e985245544c7a37011c9e19805">emitValidatorVersionMD</a>, <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a53468ec93dc5de2584b89a719ab34627">llvm::AAMDNodes::extendToTBAA</a>, <a href="/web-llvm/docs/api/classes/llvm/hlsl/frontendresource/#a762b4d0928e1709415ce366e88b2bc3a">llvm::hlsl::FrontendResource::FrontendResource</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a91844752a109d8486027ab038e8f1d36">getConstantOrNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a529578790bc8de8b220cef2ca6becef1">getEntryPropAsMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/profilesummary-cpp/#a11c2adb7d4fc89c31daa94b1f8ced5a2">getKeyFPValMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/profilesummary-cpp/#a95456b3a4f4b949345b6f7c3fac2d4c4">getKeyValMD</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a7fee7c9d5fe48b2dfbeefbd6ff1b0910">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getMDNodeForConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a45a64ff2883d51edeb926ee63a4f64ac">llvm::MDNode::getMostGenericNoaliasAddrspace</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aac6e3a0dec40a6721857cbbd4330039f">llvm::MDNode::getMostGenericRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a68d20206b060ac3ad19f416ed5a4899b">llvm::offloading::getOffloadingEntryInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#aaec462f93a64e27fa16d1416b1dbbb8b">llvm::DIBuilder::getOrCreateSubrange</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a0488e45d72dfdd3c9f1b7780fc812675">llvm::DIBuilder::getOrCreateSubrange</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a0ca82cda5ae3b31efcb01ef3f9c1b68b">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getOrderedIndirectLDSAccessingKernels</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a7ed0896d98a0b530d38c48bdd0985e00">getTagValueAsMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a7f7861a70cfa57999c2b47e570be2127">llvm::ValueAsMetadata::handleRAUW</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a1b8d4761888824dc65c66c5a0997abb9">anonymous{WholeProgramDevirt.cpp}::DevirtModule::importConstant</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluemetadata/#gab79cef5ec6dd638a424edf41f6caaed8">LLVMMDNodeInContext</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluemetadata/#gaa97820d45655d6345b92c0ac334d8b25">LLVMValueAsMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a5e5cf24df0a45159407988a98fe42700">lowerPtrAnnotation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a90003a10d0a38bad6982d3037ffaf2e1">parseAnnotation</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a0918b923129e62e296155d3054244389">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::recordLDSAbsoluteAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#aa2f5ef2d522fb80de283a23d5bed6d86">llvm::LoopVectorizeHints::setAlreadyVectorized</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a07dca79c487ad44ed9f03cfde69c7747">setAssignmentTrackingModuleFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#afc31bb8f3573226060a5c31480fa650e">llvm::GlobalObject::setVCallVisibilityMetadata</a>, <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a25af03cf36c07d235f487e525e5dcd07">llvm::AAMDNodes::shiftTBAAStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a5e2b7ac5f48193117a340aa15b085719">llvm::OpenMPIRBuilder::unrollLoopPartial</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a457f42a32df73079ac4526c572a2d7fd">updateNVPTXMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a40c011ab750e2b4ea0d6b8076345cb0c">llvm::UpgradeModuleFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7ee47904c2a7f2c3af3824c90b5a2ec">llvm::UpgradeTBAANode</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a3542900427118365bd67a1d1f4336a50">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/constantbuffer/#aa3e5db2b88327eea27f1cae82e7cfadf">llvm::dxil::ConstantBuffer::write</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcebase/extendedproperties/#a59fdcbcb099ce1f5d729fcefa7bb8206">llvm::dxil::ResourceBase::ExtendedProperties::write</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase/#aed1823c584ef7b7a15606d92eb4e2907">llvm::dxil::ResourceBase::write</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/uavresource/#a76bbe32350914cebb70fa8b6fe82d7eb">llvm::dxil::UAVResource::write</a>.</p>

</div>
</div>

### getIfExists() {#a99d7c23440c7d6dd973cf951949abdd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantAsMetadata * llvm::ConstantAsMetadata::getIfExists (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a67b0c8be13e6bd9b777c9c866f5773d9">llvm::ValueAsMetadata::getConstantIfExists</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
