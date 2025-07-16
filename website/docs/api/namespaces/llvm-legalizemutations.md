---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/legalizemutations
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `LegalizeMutations` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::LegalizeMutations { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd331b959990c033f8d612adf7701b05">changeTo</a> (unsigned TypeIdx, LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select this specific type for the given type index. <a href="#acd331b959990c033f8d612adf7701b05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f155bcbef18e4b9207aee2cbb112298">changeTo</a> (unsigned TypeIdx, unsigned FromTypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep the same type as the given type index. <a href="#a6f155bcbef18e4b9207aee2cbb112298">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4505920e551500fa2dff08f5d99f50">changeElementTo</a> (unsigned TypeIdx, unsigned FromTypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep the same scalar or element type as the given type index. <a href="#aae4505920e551500fa2dff08f5d99f50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91e3c7e954902215b9f7b5fe585f38bd">changeElementTo</a> (unsigned TypeIdx, LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep the same scalar or element type as the given type. <a href="#a91e3c7e954902215b9f7b5fe585f38bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ac1646365dca61b7727ec5291144c38">changeElementCountTo</a> (unsigned TypeIdx, unsigned FromTypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep the same scalar or element type as <span class="doxyComputerOutput">TypeIdx</span>, but take the number of elements from <span class="doxyComputerOutput">FromTypeIdx</span>. <a href="#a0ac1646365dca61b7727ec5291144c38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fff4e593b92ebdfd3e0e394d52fa817">changeElementCountTo</a> (unsigned TypeIdx, LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep the same scalar or element type as <span class="doxyComputerOutput">TypeIdx</span>, but take the number of elements from <span class="doxyComputerOutput">Ty</span>. <a href="#a4fff4e593b92ebdfd3e0e394d52fa817">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1ee247ef88b451470210e27a2eefb44">changeElementSizeTo</a> (unsigned TypeIdx, unsigned FromTypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the scalar size or element size to have the same scalar size as type index <span class="doxyComputerOutput">FromIndex</span>. <a href="#af1ee247ef88b451470210e27a2eefb44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac48512a9f1e26744de1b6940b4adb68f">widenScalarOrEltToNextPow2</a> (unsigned TypeIdx, unsigned Min=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Widen the scalar type or vector element type for the given type index to the next power of 2. <a href="#ac48512a9f1e26744de1b6940b4adb68f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb23d5b2ee365353f048abead51934e2">widenScalarOrEltToNextMultipleOf</a> (unsigned TypeIdx, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Widen the scalar type or vector element type for the given type index to next multiple of <span class="doxyComputerOutput">Size</span>. <a href="#adb23d5b2ee365353f048abead51934e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a039bb9a10ad812f936f4325facc13ab3">moreElementsToNextPow2</a> (unsigned TypeIdx, unsigned Min=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add more elements to the type for the given type index to the next power of. <a href="#a039bb9a10ad812f936f4325facc13ab3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5574ba0db2a42fa195db009f06f1d731">scalarize</a> (unsigned TypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Break up the vector type for the given type index into the element type. <a href="#a5574ba0db2a42fa195db009f06f1d731">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### changeElementCountTo() {#a0ac1646365dca61b7727ec5291144c38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation llvm::LegalizeMutations::changeElementCountTo (unsigned TypeIdx, unsigned FromTypeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep the same scalar or element type as <span class="doxyComputerOutput">TypeIdx</span>, but take the number of elements from <span class="doxyComputerOutput">FromTypeIdx</span>.</p>

<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizemutations-cpp">LegalizeMutations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#adabd45e67a1847750a117317b5ef8f9f">llvm::LLT::changeElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>.</p>

</div>
</div>

### changeElementCountTo() {#a4fff4e593b92ebdfd3e0e394d52fa817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation llvm::LegalizeMutations::changeElementCountTo (unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep the same scalar or element type as <span class="doxyComputerOutput">TypeIdx</span>, but take the number of elements from <span class="doxyComputerOutput">Ty</span>.</p>

<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizemutations-cpp">LegalizeMutations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#adabd45e67a1847750a117317b5ef8f9f">llvm::LLT::changeElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>.</p>

</div>
</div>

### changeElementSizeTo() {#af1ee247ef88b451470210e27a2eefb44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation llvm::LegalizeMutations::changeElementSizeTo (unsigned TypeIdx, unsigned FromTypeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the scalar size or element size to have the same scalar size as type index <span class="doxyComputerOutput">FromIndex</span>.</p>


<p>Unlike changeElementTo, this discards pointer types and only changes the size.</p>


<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizemutations-cpp">LegalizeMutations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a4f404daab6050b7a8e95bb247d4aefb2">llvm::LLT::changeElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a0d8b8e18977cd5ba53ec89aa06bd7506">llvm::LegalizeRuleSet::maxScalarSameAs</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a8abe7c10c8bfc8f9c308c89adc98330c">llvm::LegalizeRuleSet::minScalarSameAs</a>.</p>

</div>
</div>

### changeElementTo() {#aae4505920e551500fa2dff08f5d99f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation llvm::LegalizeMutations::changeElementTo (unsigned TypeIdx, unsigned FromTypeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep the same scalar or element type as the given type index.</p>

<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizemutations-cpp">LegalizeMutations.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/llt/#a4f404daab6050b7a8e95bb247d4aefb2">llvm::LLT::changeElementType</a>.</p>

</div>
</div>

### changeElementTo() {#a91e3c7e954902215b9f7b5fe585f38bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation llvm::LegalizeMutations::changeElementTo (unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep the same scalar or element type as the given type.</p>

<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizemutations-cpp">LegalizeMutations.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/llt/#a4f404daab6050b7a8e95bb247d4aefb2">llvm::LLT::changeElementType</a>.</p>

</div>
</div>

### changeTo() {#acd331b959990c033f8d612adf7701b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation llvm::LegalizeMutations::changeTo (unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Select this specific type for the given type index.</p>

<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizemutations-cpp">LegalizeMutations.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>.</p>

</div>
</div>

### changeTo() {#a6f155bcbef18e4b9207aee2cbb112298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation llvm::LegalizeMutations::changeTo (unsigned TypeIdx, unsigned FromTypeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep the same type as the given type index.</p>

<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizemutations-cpp">LegalizeMutations.cpp</a>.</p>

</div>
</div>

### moreElementsToNextPow2() {#a039bb9a10ad812f936f4325facc13ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation llvm::LegalizeMutations::moreElementsToNextPow2 (unsigned TypeIdx, unsigned Min=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add more elements to the type for the given type index to the next power of.</p>


<ol class="doxyList" type="1">
</ol>

<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizemutations-cpp">LegalizeMutations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a058782b98991f0719657d9008d3df41b">llvm::Log2_32_Ceil</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a592ea5db9394c272d8354d931134f16c">llvm::LegalizeRuleSet::moreElementsToNextPow2</a>.</p>

</div>
</div>

### scalarize() {#a5574ba0db2a42fa195db009f06f1d731}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation llvm::LegalizeMutations::scalarize (unsigned TypeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Break up the vector type for the given type index into the element type.</p>

<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizemutations-cpp">LegalizeMutations.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#adf80c6b70ec078f749c51a5e64b4393d">llvm::LegalizeRuleSet::scalarize</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a7369e2b43abeda933406d7b9ed83500c">llvm::LegalizeRuleSet::scalarizeIf</a>.</p>

</div>
</div>

### widenScalarOrEltToNextMultipleOf() {#adb23d5b2ee365353f048abead51934e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation llvm::LegalizeMutations::widenScalarOrEltToNextMultipleOf (unsigned TypeIdx, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Widen the scalar type or vector element type for the given type index to next multiple of <span class="doxyComputerOutput">Size</span>.</p>

<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizemutations-cpp">LegalizeMutations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#afde49505d22ecf8f8b01f47f6eaa0299">llvm::LegalizeRuleSet::widenScalarToNextMultipleOf</a>.</p>

</div>
</div>

### widenScalarOrEltToNextPow2() {#ac48512a9f1e26744de1b6940b4adb68f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation llvm::LegalizeMutations::widenScalarOrEltToNextPow2 (unsigned TypeIdx, unsigned Min=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Widen the scalar type or vector element type for the given type index to the next power of 2.</p>

<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizemutations-cpp">LegalizeMutations.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a058782b98991f0719657d9008d3df41b">llvm::Log2_32_Ceil</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af52cd47605369d735f4d6e6b24faf003">llvm::LegalizeRuleSet::widenScalarOrEltToNextPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a173a5c5c1e9992339faedc21b5954918">llvm::LegalizeRuleSet::widenScalarOrEltToNextPow2OrMinSize</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#adef498f01eb5d7c19ac40cd3b302d09e">llvm::LegalizeRuleSet::widenScalarToNextPow2</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizemutations-cpp">LegalizeMutations.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
