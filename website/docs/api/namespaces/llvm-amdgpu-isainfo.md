---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpu/isainfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `IsaInfo` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPU::IsaInfo { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid">AMDGPUTargetID</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a130401d164d538061679e82aaa62716a">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TargetIDSetting { <a href="#ab6e8b39aa26af871d8ede5fa8c791ee6">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ab6e8b39aa26af871d8ede5fa8c791ee6">TargetIDSetting</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89316777d66cdd03ab0b656968165c68">getTargetIDSettingFromFeatureString</a> (StringRef FeatureString)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f21352639512a028b2297e3cba9094">getWavefrontSize</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a404dcfcc397b46c1658356bbae054f">getLocalMemorySize</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f199c1f3d13e403d252d9b028b4c7a0">getAddressableLocalMemorySize</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705a7512f5b23ec9b3bb19f032040285">getEUsPerCU</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d0c61cd3e4d53626ffdb34031766f08">getMaxWorkGroupsPerCU</a> (const MCSubtargetInfo *STI, unsigned FlatWorkGroupSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a0082c7f646f15a4a1a7fe1bad0ec89">getMinWavesPerEU</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41a62eaa48728ca1d52dda5d0a9b08c1">getMaxWavesPerEU</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a170ce837300501b1468ea55b3e5081a1">getWavesPerEUForWorkGroup</a> (const MCSubtargetInfo *STI, unsigned FlatWorkGroupSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dd1efaf10bea58df5259c9a0c223d9a">getMinFlatWorkGroupSize</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a329b5f490df50f14bf5c359c0a01e99a">getMaxFlatWorkGroupSize</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4827353185cf1cc7bff9e44e818aa3a9">getWavesPerWorkGroup</a> (const MCSubtargetInfo *STI, unsigned FlatWorkGroupSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa82573eec93913f61c5fe97062d60c7e">getSGPRAllocGranule</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f89565a53fec2d53160be82c292202e">getSGPREncodingGranule</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeb7e0bccf88c9d23d02454609eb431a">getTotalNumSGPRs</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7baaa91927748c04ac388e82788a973d">getAddressableNumSGPRs</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8712096d79b8b76954f261f06351c34f">getMinNumSGPRs</a> (const MCSubtargetInfo *STI, unsigned WavesPerEU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98803f3d3a9a7e50ad0f40bdf8cd8190">getMaxNumSGPRs</a> (const MCSubtargetInfo *STI, unsigned WavesPerEU, bool Addressable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f0de0c1180aa2d8965d9cdddfde84a5">getNumExtraSGPRs</a> (const MCSubtargetInfo *STI, bool VCCUsed, bool FlatScrUsed, bool XNACKUsed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae419e2ff2e3882dd0d8e99c97add6b1">getNumExtraSGPRs</a> (const MCSubtargetInfo *STI, bool VCCUsed, bool FlatScrUsed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad87400fe8a5fdbd4cc548ca537692aaa">getGranulatedNumRegisterBlocks</a> (unsigned NumRegs, unsigned Granule)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d8e5747c69e74d27f050f13c4809b3">getNumSGPRBlocks</a> (const MCSubtargetInfo *STI, unsigned NumSGPRs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae47a2723f63ec4e85b4228b56e5d759c">getVGPRAllocGranule</a> (const MCSubtargetInfo *STI, std::optional&lt; bool &gt; EnableWavefrontSize32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00ddec6f625f5fdc41b2ee64b272b5b9">getVGPREncodingGranule</a> (const MCSubtargetInfo *STI, std::optional&lt; bool &gt; EnableWavefrontSize32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14accda22ecd133d48fa434165e690a0">getTotalNumVGPRs</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9f9c85e1bb9bf3a6a57b779dc3e4870">getAddressableNumArchVGPRs</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a842a99d2928e264423f0ac73b0910ec9">getAddressableNumVGPRs</a> (const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab56dd7bdfea0401c802b4c94cb76ef1e">getNumWavesPerEUWithNumVGPRs</a> (const MCSubtargetInfo *STI, unsigned NumVGPRs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6c94e07c2a231199355945f7fb87646">getNumWavesPerEUWithNumVGPRs</a> (unsigned NumVGPRs, unsigned Granule, unsigned MaxWaves, unsigned TotalNumVGPRs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad60a1f0eb9449d779a645ab620c4c36b">getOccupancyWithNumSGPRs</a> (unsigned SGPRs, unsigned MaxWaves, AMDGPUSubtarget::Generation Gen)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd9b23b6adf6877d2baba38030b77c1">getMinNumVGPRs</a> (const MCSubtargetInfo *STI, unsigned WavesPerEU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac865befe5b2563e7df0c82f5ff5ba5f2">getMaxNumVGPRs</a> (const MCSubtargetInfo *STI, unsigned WavesPerEU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbef36ba440334c992cd0f6487143da0">getEncodedNumVGPRBlocks</a> (const MCSubtargetInfo *STI, unsigned NumVGPRs, std::optional&lt; bool &gt; EnableWavefrontSize32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5753775c61d36caa01bf828eb1ad7b6">getAllocatedNumVGPRBlocks</a> (const MCSubtargetInfo *STI, unsigned NumVGPRs, std::optional&lt; bool &gt; EnableWavefrontSize32)</td>
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

## Enumerations

### anonymous enum  {#a130401d164d538061679e82aaa62716a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">FIXED_NUM_SGPRS_FOR_INIT_BUG<a id="a130401d164d538061679e82aaa62716aa5b5c7c0eaf47f7ad83186812ec4198b3"></a></td>
<td class="doxyEnumItemDescription"> (= 96)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRAP_NUM_SGPRS<a id="a130401d164d538061679e82aaa62716aa29e2fa927ce0f8856b11d9a1c4926253"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>

</div>
</div>

### TargetIDSetting {#ab6e8b39aa26af871d8ede5fa8c791ee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::AMDGPU::IsaInfo::TargetIDSetting </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Unsupported<a id="ab6e8b39aa26af871d8ede5fa8c791ee6ab4080bdf74febf04d578ff105cce9d3f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Any<a id="ab6e8b39aa26af871d8ede5fa8c791ee6aed36a1ef76a59ee3f15180e0441188ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Off<a id="ab6e8b39aa26af871d8ede5fa8c791ee6ad15305d7a4e34e02489c74a5ef542f36"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">On<a id="ab6e8b39aa26af871d8ede5fa8c791ee6a521c36a31c2762741cf0f8890cbe05e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getAddressableLocalMemorySize() {#a6f199c1f3d13e403d252d9b028b4c7a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getAddressableLocalMemorySize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum addressable local memory size in bytes for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 958 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>


<p>Referenced by <a href="#a6a404dcfcc397b46c1658356bbae054f">getLocalMemorySize</a>.</p>

</div>
</div>

### getAddressableNumArchVGPRs() {#ae9f9c85e1bb9bf3a6a57b779dc3e4870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getAddressableNumArchVGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Addressable number of architectural VGPRs for a given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a1b1c07b42d5ebde1c910cfa0025d321d">llvm::GCNSubtarget::getAddressableNumArchVGPRs</a> and <a href="#a842a99d2928e264423f0ac73b0910ec9">getAddressableNumVGPRs</a>.</p>

</div>
</div>

### getAddressableNumSGPRs() {#a7baaa91927748c04ac388e82788a973d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getAddressableNumSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Addressable number of SGPRs for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a130401d164d538061679e82aaa62716aa5b5c7c0eaf47f7ad83186812ec4198b3">FIXED_NUM_SGPRS_FOR_INIT_BUG</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#ad9bf37eb3ab2ed467ed4489666c41d27">llvm::GCNSubtarget::getAddressableNumSGPRs</a>, <a href="#a98803f3d3a9a7e50ad0f40bdf8cd8190">getMaxNumSGPRs</a>, <a href="#a8712096d79b8b76954f261f06351c34f">getMinNumSGPRs</a> and <a href="#aa82573eec93913f61c5fe97062d60c7e">getSGPRAllocGranule</a>.</p>

</div>
</div>

### getAddressableNumVGPRs() {#a842a99d2928e264423f0ac73b0910ec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getAddressableNumVGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Addressable number of VGPRs for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#ae9f9c85e1bb9bf3a6a57b779dc3e4870">getAddressableNumArchVGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#ad0db0ce6c2a59c442c60951a063e49b6">llvm::GCNSubtarget::getAddressableNumVGPRs</a>, <a href="#ac865befe5b2563e7df0c82f5ff5ba5f2">getMaxNumVGPRs</a>, <a href="#a6fd9b23b6adf6877d2baba38030b77c1">getMinNumVGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ab57c0b13438062a884d3e620300fbc03">llvm::GCNSchedStrategy::initialize</a>.</p>

</div>
</div>

### getAllocatedNumVGPRBlocks() {#af5753775c61d36caa01bf828eb1ad7b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getAllocatedNumVGPRBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned NumVGPRs, std::optional&lt; bool &gt; EnableWavefrontSize32=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of VGPR blocks that need to be allocated for the given subtarget <span class="doxyComputerOutput">STI</span> when <span class="doxyComputerOutput">NumVGPRs</span> are used.</p></dd>
</dl>


<p>Definition at line 1271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#ad87400fe8a5fdbd4cc548ca537692aaa">getGranulatedNumRegisterBlocks</a> and <a href="#ae47a2723f63ec4e85b4228b56e5d759c">getVGPRAllocGranule</a>.</p>

</div>
</div>

### getEncodedNumVGPRBlocks() {#acbef36ba440334c992cd0f6487143da0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getEncodedNumVGPRBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned NumVGPRs, std::optional&lt; bool &gt; EnableWavefrontSize32=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of VGPR blocks needed for given subtarget <span class="doxyComputerOutput">STI</span> when <span class="doxyComputerOutput">NumVGPRs</span> are used. We actually return the number of blocks -1, since that's what we encode.</p></dd>
</dl>


<p>For subtargets which support it, <span class="doxyComputerOutput">EnableWavefrontSize32</span> should match the ENABLE_WAVEFRONT_SIZE32 kernel descriptor field.</p>


<p>Definition at line 1264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#ad87400fe8a5fdbd4cc548ca537692aaa">getGranulatedNumRegisterBlocks</a> and <a href="#a00ddec6f625f5fdc41b2ee64b272b5b9">getVGPREncodingGranule</a>.</p>

</div>
</div>

### getEUsPerCU() {#a705a7512f5b23ec9b3bb19f032040285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getEUsPerCU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of execution units per compute unit for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#acf1aa5ffc0b59dd205f5dc5142580771">llvm::GCNSubtarget::GCNSubtarget</a>, <a href="#a2d0c61cd3e4d53626ffdb34031766f08">getMaxWorkGroupsPerCU</a> and <a href="#a170ce837300501b1468ea55b3e5081a1">getWavesPerEUForWorkGroup</a>.</p>

</div>
</div>

### getGranulatedNumRegisterBlocks() {#ad87400fe8a5fdbd4cc548ca537692aaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getGranulatedNumRegisterBlocks (unsigned NumRegs, unsigned Granule)</td>
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



<p>Definition at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>.</p>


<p>Referenced by <a href="#af5753775c61d36caa01bf828eb1ad7b6">getAllocatedNumVGPRBlocks</a>, <a href="#acbef36ba440334c992cd0f6487143da0">getEncodedNumVGPRBlocks</a> and <a href="#a99d8e5747c69e74d27f050f13c4809b3">getNumSGPRBlocks</a>.</p>

</div>
</div>

### getLocalMemorySize() {#a6a404dcfcc397b46c1658356bbae054f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getLocalMemorySize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Local memory size in bytes for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a6f199c1f3d13e403d252d9b028b4c7a0">getAddressableLocalMemorySize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>

</div>
</div>

### getMaxFlatWorkGroupSize() {#a329b5f490df50f14bf5c359c0a01e99a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getMaxFlatWorkGroupSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum flat work group size for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1021 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#ab5784d58015d7b40f2750f80f4ef6aeb">llvm::GCNSubtarget::getMaxFlatWorkGroupSize</a> and <a href="/web-llvm/docs/api/classes/llvm/r600subtarget/#a4bd1b9c9defaf4ddc8be04127d044bb1">llvm::R600Subtarget::getMaxFlatWorkGroupSize</a>.</p>

</div>
</div>

### getMaxNumSGPRs() {#a98803f3d3a9a7e50ad0f40bdf8cd8190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getMaxNumSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned WavesPerEU, bool Addressable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum number of SGPRs that meets the given number of waves per execution unit requirement for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1080 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7baaa91927748c04ac388e82788a973d">getAddressableNumSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a>, <a href="#aa82573eec93913f61c5fe97062d60c7e">getSGPRAllocGranule</a>, <a href="#afeb7e0bccf88c9d23d02454609eb431a">getTotalNumSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>, <a href="#a130401d164d538061679e82aaa62716aa29e2fa927ce0f8856b11d9a1c4926253">TRAP_NUM_SGPRS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#acf6141c742569e20d289c523560f8b00">llvm::GCNSubtarget::getMaxNumSGPRs</a>.</p>

</div>
</div>

### getMaxNumVGPRs() {#ac865befe5b2563e7df0c82f5ff5ba5f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getMaxNumVGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned WavesPerEU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum number of VGPRs that meets given number of waves per execution unit requirement for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a842a99d2928e264423f0ac73b0910ec9">getAddressableNumVGPRs</a>, <a href="#a14accda22ecd133d48fa434165e690a0">getTotalNumVGPRs</a> and <a href="#ae47a2723f63ec4e85b4228b56e5d759c">getVGPRAllocGranule</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a4f492fa16404497b8f15ea82c4b0a725">llvm::GCNSubtarget::getMaxNumVGPRs</a>.</p>

</div>
</div>

### getMaxWavesPerEU() {#a41a62eaa48728ca1d52dda5d0a9b08c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getMaxWavesPerEU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum number of waves per execution unit for given subtarget <span class="doxyComputerOutput">STI</span> without any kind of limitation.</p></dd>
</dl>


<p>Definition at line 1002 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a98f3297011ab8da601c7cce576c3353f">llvm::AMDGPU::hasGFX10_3Insts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6927ea03a5a90995645230645e0fbd89">llvm::AMDGPU::isGFX90A</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a528b669c7627f74c541a4800020df024">llvm::AMDGPUMCExpr::createOccupancy</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#acf1aa5ffc0b59dd205f5dc5142580771">llvm::GCNSubtarget::GCNSubtarget</a>, <a href="#a2d0c61cd3e4d53626ffdb34031766f08">getMaxWorkGroupsPerCU</a>, <a href="#a8712096d79b8b76954f261f06351c34f">getMinNumSGPRs</a>, <a href="#a6fd9b23b6adf6877d2baba38030b77c1">getMinNumVGPRs</a>, <a href="#ab56dd7bdfea0401c802b4c94cb76ef1e">getNumWavesPerEUWithNumVGPRs</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>.</p>

</div>
</div>

### getMaxWorkGroupsPerCU() {#a2d0c61cd3e4d53626ffdb34031766f08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getMaxWorkGroupsPerCU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned FlatWorkGroupSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Maximum number of work groups per compute unit for given subtarget <span class="doxyComputerOutput">STI</span> and limited by given <span class="doxyComputerOutput">FlatWorkGroupSize</span>.</p></dd>
</dl>


<p>Definition at line 979 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">llvm::Triple::amdgcn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="#a705a7512f5b23ec9b3bb19f032040285">getEUsPerCU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="#a41a62eaa48728ca1d52dda5d0a9b08c1">getMaxWavesPerEU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a1ef6ef4ff039e873e9f66e21e3e55e26">llvm::MCSubtargetInfo::getTargetTriple</a>, <a href="#a4827353185cf1cc7bff9e44e818aa3a9">getWavesPerWorkGroup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a32e4f8d7e4a12870752efe1ff494c96d">llvm::GCNSubtarget::getMaxWorkGroupsPerCU</a> and <a href="/web-llvm/docs/api/classes/llvm/r600subtarget/#a2f461fa069bb14d4ef708893c54c29d6">llvm::R600Subtarget::getMaxWorkGroupsPerCU</a>.</p>

</div>
</div>

### getMinFlatWorkGroupSize() {#a8dd1efaf10bea58df5259c9a0c223d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getMinFlatWorkGroupSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Minimum flat work group size for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1017 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#aa214881f596f9adddeef9df6600df144">llvm::GCNSubtarget::getMinFlatWorkGroupSize</a> and <a href="/web-llvm/docs/api/classes/llvm/r600subtarget/#a270a8ab14876a126d43c7f7c6a91298e">llvm::R600Subtarget::getMinFlatWorkGroupSize</a>.</p>

</div>
</div>

### getMinNumSGPRs() {#a8712096d79b8b76954f261f06351c34f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getMinNumSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned WavesPerEU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Minimum number of SGPRs that meets the given number of waves per execution unit requirement for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7baaa91927748c04ac388e82788a973d">getAddressableNumSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a>, <a href="#a41a62eaa48728ca1d52dda5d0a9b08c1">getMaxWavesPerEU</a>, <a href="#aa82573eec93913f61c5fe97062d60c7e">getSGPRAllocGranule</a>, <a href="#afeb7e0bccf88c9d23d02454609eb431a">getTotalNumSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>, <a href="#a130401d164d538061679e82aaa62716aa29e2fa927ce0f8856b11d9a1c4926253">TRAP_NUM_SGPRS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a1c9934ccbee04b51f83a123e09ae9cf1">llvm::GCNSubtarget::getMinNumSGPRs</a>.</p>

</div>
</div>

### getMinNumVGPRs() {#a6fd9b23b6adf6877d2baba38030b77c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getMinNumVGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned WavesPerEU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Minimum number of VGPRs that meets given number of waves per execution unit requirement for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a842a99d2928e264423f0ac73b0910ec9">getAddressableNumVGPRs</a>, <a href="#a41a62eaa48728ca1d52dda5d0a9b08c1">getMaxWavesPerEU</a>, <a href="#a6fd9b23b6adf6877d2baba38030b77c1">getMinNumVGPRs</a>, <a href="#ab56dd7bdfea0401c802b4c94cb76ef1e">getNumWavesPerEUWithNumVGPRs</a>, <a href="#a14accda22ecd133d48fa434165e690a0">getTotalNumVGPRs</a> and <a href="#ae47a2723f63ec4e85b4228b56e5d759c">getVGPRAllocGranule</a>.</p>


<p>Referenced by <a href="#a6fd9b23b6adf6877d2baba38030b77c1">getMinNumVGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a61d8866021383c037a029d77a3497f23">llvm::GCNSubtarget::getMinNumVGPRs</a>.</p>

</div>
</div>

### getMinWavesPerEU() {#a9a0082c7f646f15a4a1a7fe1bad0ec89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getMinWavesPerEU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Minimum number of waves per execution unit for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 998 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a2ea42736115781162e371685322542f4">llvm::GCNSubtarget::getMinWavesPerEU</a> and <a href="/web-llvm/docs/api/classes/llvm/r600subtarget/#a8b4bad260e61c06d2c5a4d88c6b244de">llvm::R600Subtarget::getMinWavesPerEU</a>.</p>

</div>
</div>

### getNumExtraSGPRs() {#a4f0de0c1180aa2d8965d9cdddfde84a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getNumExtraSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, bool VCCUsed, bool FlatScrUsed, bool XNACKUsed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of extra SGPRs implicitly required by given subtarget <span class="doxyComputerOutput">STI</span> when the given special registers are used.</p></dd>
</dl>


<p>Definition at line 1097 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#aae419e2ff2e3882dd0d8e99c97add6b1">getNumExtraSGPRs</a>.</p>

</div>
</div>

### getNumExtraSGPRs() {#aae419e2ff2e3882dd0d8e99c97add6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getNumExtraSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, bool VCCUsed, bool FlatScrUsed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of extra SGPRs implicitly required by given subtarget <span class="doxyComputerOutput">STI</span> when the given special registers are used. XNACK is inferred from <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="#a4f0de0c1180aa2d8965d9cdddfde84a5">getNumExtraSGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>

</div>
</div>

### getNumSGPRBlocks() {#a99d8e5747c69e74d27f050f13c4809b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getNumSGPRBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned NumSGPRs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of SGPR blocks needed for given subtarget <span class="doxyComputerOutput">STI</span> when <span class="doxyComputerOutput">NumSGPRs</span> are used. <span class="doxyComputerOutput">NumSGPRs</span> should already include any special register counts.</p></dd>
</dl>


<p>Definition at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#ad87400fe8a5fdbd4cc548ca537692aaa">getGranulatedNumRegisterBlocks</a> and <a href="#a4f89565a53fec2d53160be82c292202e">getSGPREncodingGranule</a>.</p>

</div>
</div>

### getNumWavesPerEUWithNumVGPRs() {#ab56dd7bdfea0401c802b4c94cb76ef1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getNumWavesPerEUWithNumVGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned NumVGPRs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of waves reachable for a given <span class="doxyComputerOutput">NumVGPRs</span> usage for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a41a62eaa48728ca1d52dda5d0a9b08c1">getMaxWavesPerEU</a>, <a href="#ab56dd7bdfea0401c802b4c94cb76ef1e">getNumWavesPerEUWithNumVGPRs</a>, <a href="#a14accda22ecd133d48fa434165e690a0">getTotalNumVGPRs</a> and <a href="#ae47a2723f63ec4e85b4228b56e5d759c">getVGPRAllocGranule</a>.</p>


<p>Referenced by <a href="#a6fd9b23b6adf6877d2baba38030b77c1">getMinNumVGPRs</a>, <a href="#ab56dd7bdfea0401c802b4c94cb76ef1e">getNumWavesPerEUWithNumVGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#aa19ea7d1223b3dbc9f1c432059f8e040">llvm::GCNSubtarget::getOccupancyWithNumVGPRs</a>.</p>

</div>
</div>

### getNumWavesPerEUWithNumVGPRs() {#ac6c94e07c2a231199355945f7fb87646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getNumWavesPerEUWithNumVGPRs (unsigned NumVGPRs, unsigned Granule, unsigned MaxWaves, unsigned TotalNumVGPRs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of waves reachable for a given <span class="doxyComputerOutput">NumVGPRs</span> usage, <span class="doxyComputerOutput">Granule</span> size, <span class="doxyComputerOutput">MaxWaves</span> possible, and <span class="doxyComputerOutput">TotalNumVGPRs</span> available.</p></dd>
</dl>


<p>Definition at line 1195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>.</p>

</div>
</div>

### getOccupancyWithNumSGPRs() {#ad60a1f0eb9449d779a645ab620c4c36b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getOccupancyWithNumSGPRs (unsigned SGPRs, unsigned MaxWaves, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2">AMDGPUSubtarget::Generation</a> Gen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Occupancy for a given <span class="doxyComputerOutput">SGPRs</span> usage, <span class="doxyComputerOutput">MaxWaves</span> possible, and <span class="doxyComputerOutput">Gen</span>.</p></dd>
</dl>


<p>Definition at line 1204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#ab20982dc4ff887572a43754228a94fc0">llvm::GCNSubtarget::getOccupancyWithNumSGPRs</a>.</p>

</div>
</div>

### getSGPRAllocGranule() {#aa82573eec93913f61c5fe97062d60c7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getSGPRAllocGranule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>SGPR allocation granularity for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a7baaa91927748c04ac388e82788a973d">getAddressableNumSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#a98803f3d3a9a7e50ad0f40bdf8cd8190">getMaxNumSGPRs</a>, <a href="#a8712096d79b8b76954f261f06351c34f">getMinNumSGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a120ab447b09dc6bafd750961802ca264">llvm::GCNSubtarget::getSGPRAllocGranule</a>.</p>

</div>
</div>

### getSGPREncodingGranule() {#a4f89565a53fec2d53160be82c292202e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getSGPREncodingGranule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>SGPR encoding granularity for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1040 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1a717ebce0af699c0b264313d0cb21e2">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC1</a>, <a href="#a99d8e5747c69e74d27f050f13c4809b3">getNumSGPRBlocks</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a1cc464816b0b6f1497cbb07c51cb0a36">llvm::GCNSubtarget::getSGPREncodingGranule</a>.</p>

</div>
</div>

### getTargetIDSettingFromFeatureString() {#a89316777d66cdd03ab0b656968165c68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetIDSetting llvm::AMDGPU::IsaInfo::getTargetIDSettingFromFeatureString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FeatureString)</td>
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



<p>Definition at line 874 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ab6e8b39aa26af871d8ede5fa8c791ee6ad15305d7a4e34e02489c74a5ef542f36">Off</a> and <a href="#ab6e8b39aa26af871d8ede5fa8c791ee6a521c36a31c2762741cf0f8890cbe05e3">On</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid/#aab792d0c32d4c9a7998c0ba8885693ff">llvm::AMDGPU::IsaInfo::AMDGPUTargetID::setTargetIDFromTargetIDStream</a>.</p>

</div>
</div>

### getTotalNumSGPRs() {#afeb7e0bccf88c9d23d02454609eb431a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getTotalNumSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Total number of SGPRs for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1044 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#a98803f3d3a9a7e50ad0f40bdf8cd8190">getMaxNumSGPRs</a>, <a href="#a8712096d79b8b76954f261f06351c34f">getMinNumSGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a377dcbfe45feb26ed8654cfce84087af">llvm::GCNSubtarget::getTotalNumSGPRs</a>.</p>

</div>
</div>

### getTotalNumVGPRs() {#a14accda22ecd133d48fa434165e690a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getTotalNumVGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Total number of VGPRs for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 1169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a528b669c7627f74c541a4800020df024">llvm::AMDGPUMCExpr::createOccupancy</a>, <a href="#ac865befe5b2563e7df0c82f5ff5ba5f2">getMaxNumVGPRs</a>, <a href="#a6fd9b23b6adf6877d2baba38030b77c1">getMinNumVGPRs</a>, <a href="#ab56dd7bdfea0401c802b4c94cb76ef1e">getNumWavesPerEUWithNumVGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a2e649388bef9c44bc294dab940cd6b84">llvm::GCNSubtarget::getTotalNumVGPRs</a>.</p>

</div>
</div>

### getVGPRAllocGranule() {#ae47a2723f63ec4e85b4228b56e5d759c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getVGPRAllocGranule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, std::optional&lt; bool &gt; EnableWavefrontSize32=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>VGPR allocation granularity for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>For subtargets which support it, <span class="doxyComputerOutput">EnableWavefrontSize32</span> should match the ENABLE_WAVEFRONT_SIZE32 kernel descriptor field.</p>


<p>Definition at line 1139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a98f3297011ab8da601c7cce576c3353f">llvm::AMDGPU::hasGFX10_3Insts</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a528b669c7627f74c541a4800020df024">llvm::AMDGPUMCExpr::createOccupancy</a>, <a href="#af5753775c61d36caa01bf828eb1ad7b6">getAllocatedNumVGPRBlocks</a>, <a href="#ac865befe5b2563e7df0c82f5ff5ba5f2">getMaxNumVGPRs</a>, <a href="#a6fd9b23b6adf6877d2baba38030b77c1">getMinNumVGPRs</a>, <a href="#ab56dd7bdfea0401c802b4c94cb76ef1e">getNumWavesPerEUWithNumVGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a4d631f933bed8f5b71e58638f024b87c">llvm::GCNSubtarget::getVGPRAllocGranule</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ab57c0b13438062a884d3e620300fbc03">llvm::GCNSchedStrategy::initialize</a>.</p>

</div>
</div>

### getVGPREncodingGranule() {#a00ddec6f625f5fdc41b2ee64b272b5b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getVGPREncodingGranule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, std::optional&lt; bool &gt; EnableWavefrontSize32=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>VGPR encoding granularity for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>For subtargets which support it, <span class="doxyComputerOutput">EnableWavefrontSize32</span> should match the ENABLE_WAVEFRONT_SIZE32 kernel descriptor field.</p>


<p>Definition at line 1157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1a717ebce0af699c0b264313d0cb21e2">llvm::AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC1</a>, <a href="#acbef36ba440334c992cd0f6487143da0">getEncodedNumVGPRBlocks</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a5636afb498eec4770235c34d76f8e36f">llvm::GCNSubtarget::getVGPREncodingGranule</a>.</p>

</div>
</div>

### getWavefrontSize() {#a20f21352639512a028b2297e3cba9094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getWavefrontSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Wavefront size for given subtarget <span class="doxyComputerOutput">STI</span>.</p></dd>
</dl>


<p>Definition at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>


<p>Referenced by <a href="#a4827353185cf1cc7bff9e44e818aa3a9">getWavesPerWorkGroup</a>.</p>

</div>
</div>

### getWavesPerEUForWorkGroup() {#a170ce837300501b1468ea55b3e5081a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getWavesPerEUForWorkGroup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned FlatWorkGroupSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of waves per execution unit required to support the given <span class="doxyComputerOutput">FlatWorkGroupSize</span>.</p></dd>
</dl>


<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="#a705a7512f5b23ec9b3bb19f032040285">getEUsPerCU</a> and <a href="#a4827353185cf1cc7bff9e44e818aa3a9">getWavesPerWorkGroup</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#abd3d507136dc902e56d585a7dd9d729e">llvm::GCNSubtarget::getWavesPerEUForWorkGroup</a> and <a href="/web-llvm/docs/api/classes/llvm/r600subtarget/#a66c505753164d41926c03c0c785466ef">llvm::R600Subtarget::getWavesPerEUForWorkGroup</a>.</p>

</div>
</div>

### getWavesPerWorkGroup() {#a4827353185cf1cc7bff9e44e818aa3a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::IsaInfo::getWavesPerWorkGroup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, unsigned FlatWorkGroupSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of waves per work group for given subtarget <span class="doxyComputerOutput">STI</span> and <span class="doxyComputerOutput">FlatWorkGroupSize</span>.</p></dd>
</dl>


<p>Definition at line 1026 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a> and <a href="#a20f21352639512a028b2297e3cba9094">getWavefrontSize</a>.</p>


<p>Referenced by <a href="#a2d0c61cd3e4d53626ffdb34031766f08">getMaxWorkGroupsPerCU</a> and <a href="#a170ce837300501b1468ea55b3e5081a1">getWavesPerEUForWorkGroup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
