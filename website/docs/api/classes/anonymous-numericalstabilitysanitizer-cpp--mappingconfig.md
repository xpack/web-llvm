---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-numericalstabilitysanitizer-cpp-/mappingconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MappingConfig` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{NumericalStabilitySanitizer.cpp}::MappingConfig { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0390e397c6571aacfc202d553a8d661b">MappingConfig</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-numericalstabilitysanitizer-cpp-/shadowtypeconfig">ShadowTypeConfig</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae379af4e58fe7f76d962fa0019d5fbff">byValueType</a> (FTValueType VT) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b25ffb1d9184be4a8694b940d27562">getExtendedFPType</a> (Type *FT) const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfc55e518e8c103baf93963c444a6845">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-numericalstabilitysanitizer-cpp-/shadowtypeconfig">ShadowTypeConfig</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a7b6da0e0a806f039e94d7ec92b3388">Configs</a>[FTValueType::kNumValueTypes]</td>
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


<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp">NumericalStabilitySanitizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MappingConfig() {#a0390e397c6571aacfc202d553a8d661b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{NumericalStabilitySanitizer.cpp}::MappingConfig::MappingConfig (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp">NumericalStabilitySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#acc1f3b8c2af5318b8a4a1d89ee219136">ClShadowMapping</a>, <a href="/web-llvm/docs/api/classes/anonymous-numericalstabilitysanitizer-cpp-/shadowtypeconfig/#aee2e32619e6554dd6dccb0644f88cdb1">anonymous{NumericalStabilitySanitizer.cpp}::ShadowTypeConfig::fromNsanTypeId</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#aa1ed4204e508210aa61a3e82681a1208ad6001cc8749d6ced672212513067b74c">anonymous{NumericalStabilitySanitizer.cpp}::kDouble</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#aa1ed4204e508210aa61a3e82681a1208a861d8316f95a4cbb457a4926556e712f">anonymous{NumericalStabilitySanitizer.cpp}::kFloat</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#aa1ed4204e508210aa61a3e82681a1208a74f7617bb2664d74125a68649be682d1">anonymous{NumericalStabilitySanitizer.cpp}::kLongDouble</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#aa1ed4204e508210aa61a3e82681a1208a663b459584ea0c76e94427e345b99ed0">anonymous{NumericalStabilitySanitizer.cpp}::kNumValueTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#aa205f978477e17b9978a3518f23e4110">kShadowScale</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#a1f97ca5ebffacffa92c87ce782a56708">anonymous{NumericalStabilitySanitizer.cpp}::typeFromFTValueType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### byValueType() {#ae379af4e58fe7f76d962fa0019d5fbff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ShadowTypeConfig &amp; anonymous{NumericalStabilitySanitizer.cpp}::MappingConfig::byValueType (<a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#aa1ed4204e508210aa61a3e82681a1208">FTValueType</a> VT)</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp">NumericalStabilitySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#aa1ed4204e508210aa61a3e82681a1208a663b459584ea0c76e94427e345b99ed0">anonymous{NumericalStabilitySanitizer.cpp}::kNumValueTypes</a>.</p>

</div>
</div>

### getExtendedFPType() {#aa4b25ffb1d9184be4a8694b940d27562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{NumericalStabilitySanitizer.cpp}::MappingConfig::getExtendedFPType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * FT)</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp">NumericalStabilitySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-numericalstabilitysanitizer-cpp-/#aa1e8b1f5460f1a0df33e86adb69e934c">anonymous{NumericalStabilitySanitizer.cpp}::ftValueTypeFromType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="#aa4b25ffb1d9184be4a8694b940d27562">getExtendedFPType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>.</p>


<p>Referenced by <a href="#aa4b25ffb1d9184be4a8694b940d27562">getExtendedFPType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Configs {#a6a7b6da0e0a806f039e94d7ec92b3388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ShadowTypeConfig&gt; anonymous{NumericalStabilitySanitizer.cpp}::MappingConfig::Configs[FTValueType::kNumValueTypes]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp">NumericalStabilitySanitizer.cpp</a>.</p>

</div>
</div>

### Context {#adfc55e518e8c103baf93963c444a6845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; anonymous{NumericalStabilitySanitizer.cpp}::MappingConfig::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp">NumericalStabilitySanitizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp">NumericalStabilitySanitizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
