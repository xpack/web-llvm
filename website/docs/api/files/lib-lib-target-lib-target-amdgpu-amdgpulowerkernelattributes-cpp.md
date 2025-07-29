---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AMDGPULowerKernelAttributes.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpu-h">AMDGPU.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">Utils/AMDGPUBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/constantfolding-h">llvm/Analysis/ConstantFolding.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "llvm/IR/IntrinsicsAMDGPU.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-">anonymous{AMDGPULowerKernelAttributes.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelattributes-cpp-/amdgpulowerkernelattributes">AMDGPULowerKernelAttributes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada9cd9202fbb1b38f39030725baddad6">annotateGridSizeLoadWithRangeMD</a> (LoadInst *Load, uint32_t MaxNumGroups)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec05cafc12b1852dbd16670773d4f00d">processUse</a> (CallInst *CI, bool IsV5OrAbove)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d23c6b45772676898bb7cd75ab8a558">INITIALIZE_PASS_BEGIN</a> (AMDGPULowerKernelAttributes, DEBUG_TYPE, "AMDGPU Kernel Attributes", false, false) INITIALIZE_PASS_END(AMDGPULowerKernelAttributes</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030569d5a541b6110f2ae1b6a3413a58">DEBUG_TYPE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">AMDGPU Kernel</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a7ac0d6f6157bfa62400fdc021157dc">Attributes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">AMDGPU Kernel</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a81930f79de7551a9c20f3beebb6ae4">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"amdgpu-lower-kernel-attributes"</td>
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

### annotateGridSizeLoadWithRangeMD() {#ada9cd9202fbb1b38f39030725baddad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void annotateGridSizeLoadWithRangeMD (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load, uint32_t MaxNumGroups)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp">AMDGPULowerKernelAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#ab6af8e6189a4d10f4a9c20daab0280b8">llvm::MDBuilder::createRange</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="#aec05cafc12b1852dbd16670773d4f00d">processUse</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a2d23c6b45772676898bb7cd75ab8a558}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (AMDGPULowerKernelAttributes, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "AMDGPU Kernel Attributes", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp">AMDGPULowerKernelAttributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>.</p>

</div>
</div>

### processUse() {#aec05cafc12b1852dbd16670773d4f00d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool processUse (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, bool IsV5OrAbove)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp">AMDGPULowerKernelAttributes.cpp</a>.</p>


<p>References <a href="#ada9cd9202fbb1b38f39030725baddad6">annotateGridSizeLoadWithRangeMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45c454aff5d0478a70219bb15d369b3">llvm::ConstantFoldIntegerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae254bedbb0fc90b423b5072a97ef3efd">llvm::AMDGPU::getIntegerVecAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ac5d9eb48038aa973017317279eadf5">llvm::GetPointerBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#af445065482fe4ec1995fb5ad2986b48ea48f2b7dc8c27fc49568d9a634fce124c">anonymous{AMDGPULowerKernelAttributes.cpp}::GRID_SIZE_X</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#af445065482fe4ec1995fb5ad2986b48eabab0e2301d5826c28d78bfa7760796f6">anonymous{AMDGPULowerKernelAttributes.cpp}::GRID_SIZE_Y</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#af445065482fe4ec1995fb5ad2986b48ea1ea8d13231aaf2f47426d98e6db17321">anonymous{AMDGPULowerKernelAttributes.cpp}::GRID_SIZE_Z</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#ae65db8fb30d545b846afe720bc1dcd9bacc7438cd63022de438a96822be793983">anonymous{AMDGPULowerKernelAttributes.cpp}::HIDDEN_BLOCK_COUNT_X</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#ae65db8fb30d545b846afe720bc1dcd9bae319b2f467b2ce736c795b2ace3d126f">anonymous{AMDGPULowerKernelAttributes.cpp}::HIDDEN_BLOCK_COUNT_Y</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#ae65db8fb30d545b846afe720bc1dcd9ba1a930fa809a646dcaad33a6a91b26b86">anonymous{AMDGPULowerKernelAttributes.cpp}::HIDDEN_BLOCK_COUNT_Z</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#ae65db8fb30d545b846afe720bc1dcd9badea09ba09d91c85ca362087393e4b8fd">anonymous{AMDGPULowerKernelAttributes.cpp}::HIDDEN_GROUP_SIZE_X</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#ae65db8fb30d545b846afe720bc1dcd9baf5e564c25639ead86aba226347136041">anonymous{AMDGPULowerKernelAttributes.cpp}::HIDDEN_GROUP_SIZE_Y</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#ae65db8fb30d545b846afe720bc1dcd9ba59b88527f863a49db296c65d4d0dfd86">anonymous{AMDGPULowerKernelAttributes.cpp}::HIDDEN_GROUP_SIZE_Z</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#ae65db8fb30d545b846afe720bc1dcd9ba31e088641f60fbf2c764c57aae43bf3c">anonymous{AMDGPULowerKernelAttributes.cpp}::HIDDEN_REMAINDER_X</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#ae65db8fb30d545b846afe720bc1dcd9ba5b1ad5d4228b81d5b1fa3d23eb62c2a6">anonymous{AMDGPULowerKernelAttributes.cpp}::HIDDEN_REMAINDER_Y</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#ae65db8fb30d545b846afe720bc1dcd9ba326729f29d6b5999f8393ff767020cd7">anonymous{AMDGPULowerKernelAttributes.cpp}::HIDDEN_REMAINDER_Z</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a532515120d78196926b68c48460087ab">llvm::PatternMatch::m_Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6924ab881778c340b66e1e693154b1a8">llvm::PatternMatch::m_SpecificICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af627036178ac57e62dd894233ce10fcb">llvm::PatternMatch::m_UMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea1c692ed4bf463fb08fca4d8cb8201ac0">llvm::UMin</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#af445065482fe4ec1995fb5ad2986b48ea3fc0d24956fed035916c3731b0a97b3f">anonymous{AMDGPULowerKernelAttributes.cpp}::WORKGROUP_SIZE_X</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#af445065482fe4ec1995fb5ad2986b48ea7c79e4df993a0a2393ca9304182c1454">anonymous{AMDGPULowerKernelAttributes.cpp}::WORKGROUP_SIZE_Y</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#af445065482fe4ec1995fb5ad2986b48eaacdd008a0965560c2fd4c292f92b02e1">anonymous{AMDGPULowerKernelAttributes.cpp}::WORKGROUP_SIZE_Z</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/amdgpulowerkernelattributespass/#af67c40d9973225a0cdd48e2c13ffe9d2">llvm::AMDGPULowerKernelAttributesPass::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelattributes-cpp-/amdgpulowerkernelattributes/#aaf10937fb0ffaa2b0bfa200597266f2e">anonymous{AMDGPULowerKernelAttributes.cpp}::AMDGPULowerKernelAttributes::runOnModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Attributes {#a5a7ac0d6f6157bfa62400fdc021157dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPU Kernel Attributes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp">AMDGPULowerKernelAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#aba8001b30fa09b1b983c01fb4f4f76f5">llvm::ModuleSummaryIndex::exportToDot</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#ad4f1deb260cb6fd64575135be5a3d25f">llvm::object::ELFObjectFile&lt; ELF32LE &gt;::getBuildAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#a45bee296a39304fe664ab2bf354381e7">llvm::object::ELFObjectFileBase::getBuildAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a8e11393a870b05fc975c383371854ed5">ParseLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#aee16ef63867cb58a1e046d39fb99e49f">parseMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopefunction/#a8d492d01226a0de47e0dd7e6bad87913">llvm::logicalview::LVScopeFunction::printExtra</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol/#a0a847dd121f1930bac3312cbbba6589d">llvm::logicalview::LVSymbol::printExtra</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypeimport/#a824dec74651c02827e4f7bb06a02f390">llvm::logicalview::LVTypeImport::printExtra</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9b9e845ee3096f8360407bfa4f0f3d1a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#aedba1742067f82fe193a19daf690cd06">llvm::object::ELFObjectFileBase::setARMSubArch</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#a030569d5a541b6110f2ae1b6a3413a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_TYPE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp">AMDGPULowerKernelAttributes.cpp</a>.</p>

</div>
</div>

### false {#a1a81930f79de7551a9c20f3beebb6ae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPU Kernel false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp">AMDGPULowerKernelAttributes.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"amdgpu-lower-kernel-attributes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp">AMDGPULowerKernelAttributes.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
