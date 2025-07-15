---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/profilesummaryinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ProfileSummaryInfo` Class Reference

<p>Analysis providing profile information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ProfileSummaryInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb05603aef033fa3fc732f6a894e5e0c">ProfileSummaryInfo</a> (const Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf06320b1c235da8418d00b9f98a9a71">ProfileSummaryInfo</a> (ProfileSummaryInfo &amp;&amp;Arg)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2600478d8188a85a14af8787024e1831">refresh</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If no summary is present, attempt to refresh. <a href="#a2600478d8188a85a14af8787024e1831">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d1c1af51bf81a6a9f8f5191b5e3cf2">hasProfileSummary</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if profile summary is available. <a href="#a11d1c1af51bf81a6a9f8f5191b5e3cf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42c9b372f129ae40b72b97ce6df45eed">hasSampleProfile</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if module <span class="doxyComputerOutput">M</span> has sample profile. <a href="#a42c9b372f129ae40b72b97ce6df45eed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21a2dd574b9729dcd05b46dae856ebc4">hasInstrumentationProfile</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if module <span class="doxyComputerOutput">M</span> has instrumentation profile. <a href="#a21a2dd574b9729dcd05b46dae856ebc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a077d500a5e9209486b76dd5da3e673c4">hasCSInstrumentationProfile</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if module <span class="doxyComputerOutput">M</span> has context sensitive instrumentation profile. <a href="#a077d500a5e9209486b76dd5da3e673c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5467cd3b1ab6bdcbebba1988f96108f">invalidate</a> (Module &amp;, const PreservedAnalyses &amp;, ModuleAnalysisManager::Invalidator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle the invalidation of this information. <a href="#af5467cd3b1ab6bdcbebba1988f96108f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e70e7a7b5e8ebe792ecaec8639d16e">getProfileCount</a> (const CallBase &amp;CallInst, BlockFrequencyInfo *BFI, bool AllowSynthetic=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the profile count for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a></span>. <a href="#a37e70e7a7b5e8ebe792ecaec8639d16e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9610274171a85158779e7ee6031d2376">hasPartialSampleProfile</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if module <span class="doxyComputerOutput">M</span> has partial-profile sample profile. <a href="#a9610274171a85158779e7ee6031d2376">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7a8ced5ff54962319d57208f5d4a57e">hasHugeWorkingSetSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the working set size of the code is considered huge. <a href="#ad7a8ced5ff54962319d57208f5d4a57e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d3f3ea07d22d6ada9863087570aaeb">hasLargeWorkingSetSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the working set size of the code is considered large. <a href="#a99d3f3ea07d22d6ada9863087570aaeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FuncT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a55d31db902636df919d451f2b5859f50">isFunctionEntryHot</a> (const FuncT *F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">F</span> has hot function entry. <a href="#a55d31db902636df919d451f2b5859f50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FuncT, typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a527a78e773ac22ca346a7b8ca9201e">isFunctionHotInCallGraph</a> (const FuncT *F, BFIT &amp;BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">F</span> contains hot code. <a href="#a8a527a78e773ac22ca346a7b8ca9201e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af813576f394d690d9d51ca46810eaf87">isFunctionEntryCold</a> (const Function *F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">F</span> has cold function entry. <a href="#af813576f394d690d9d51ca46810eaf87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FuncT, typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1cdf368dd1d358e55f871484b1fec5cc">isFunctionColdInCallGraph</a> (const FuncT *F, BFIT &amp;BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">F</span> contains only cold code. <a href="#a1cdf368dd1d358e55f871484b1fec5cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215c4f3e485345daeb8e9d68264f388a">isFunctionHotnessUnknown</a> (const Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the hotness of <span class="doxyComputerOutput">F</span> is unknown. <a href="#a215c4f3e485345daeb8e9d68264f388a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FuncT, typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6f820b8a83376970321b6e7211df6087">isFunctionHotInCallGraphNthPercentile</a> (int PercentileCutoff, const FuncT *F, BFIT &amp;BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">F</span> contains hot code with regard to a given hot percentile cutoff value. <a href="#a6f820b8a83376970321b6e7211df6087">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FuncT, typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3b3f19a7c246b09a46ab4dcf3b05e212">isFunctionColdInCallGraphNthPercentile</a> (int PercentileCutoff, const FuncT *F, BFIT &amp;BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">F</span> contains cold code with regard to a given cold percentile cutoff value. <a href="#a3b3f19a7c246b09a46ab4dcf3b05e212">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac46d4d55dd867977ba88d57a170e31de">isHotCount</a> (uint64_t C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if count <span class="doxyComputerOutput">C</span> is considered hot. <a href="#ac46d4d55dd867977ba88d57a170e31de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f58eb949321536363605ac9920a95cb">isColdCount</a> (uint64_t C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if count <span class="doxyComputerOutput">C</span> is considered cold. <a href="#a5f58eb949321536363605ac9920a95cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a829b6546f1d344de8cc5a6be1dd1e424">isHotCountNthPercentile</a> (int PercentileCutoff, uint64_t C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if count <span class="doxyComputerOutput">C</span> is considered hot with regard to a given hot percentile cutoff value. <a href="#a829b6546f1d344de8cc5a6be1dd1e424">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a731b588787c30ac1905c449402cc8b06">isColdCountNthPercentile</a> (int PercentileCutoff, uint64_t C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if count <span class="doxyComputerOutput">C</span> is considered cold with regard to a given cold percentile cutoff value. <a href="#a731b588787c30ac1905c449402cc8b06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BBType, typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abe32f174e5db14e8616ae5df650da111">isHotBlock</a> (const BBType *BB, BFIT *BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <span class="doxyComputerOutput">BB</span> is considered hot. <a href="#abe32f174e5db14e8616ae5df650da111">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BBType, typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a597b25ab8d0a79f855c6c66dc48cb803">isColdBlock</a> (const BBType *BB, BFIT *BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <span class="doxyComputerOutput">BB</span> is considered cold. <a href="#a597b25ab8d0a79f855c6c66dc48cb803">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8fbb537d20b4320256065afd39ef57f9">isColdBlock</a> (BlockFrequency BlockFreq, const BFIT *BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BBType, typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a199ef173a063b51608e3438d8ab325d9">isHotBlockNthPercentile</a> (int PercentileCutoff, const BBType *BB, BFIT *BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af4346625334107fbea42a8e1d607a20a">isHotBlockNthPercentile</a> (int PercentileCutoff, BlockFrequency BlockFreq, BFIT *BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BBType, typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada543df24b6c3fa80f90e0aab1bb68f2">isColdBlockNthPercentile</a> (int PercentileCutoff, const BBType *BB, BFIT *BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <span class="doxyComputerOutput">BB</span> is considered cold with regard to a given cold percentile cutoff value. <a href="#ada543df24b6c3fa80f90e0aab1bb68f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac125007461291d169ae8c200550184ec">isColdBlockNthPercentile</a> (int PercentileCutoff, BlockFrequency BlockFreq, BFIT *BFI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3d4f70baa23fdf679f700997951c6c1">isHotCallSite</a> (const CallBase &amp;CB, BlockFrequencyInfo *BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the call site <span class="doxyComputerOutput">CB</span> is considered hot. <a href="#ab3d4f70baa23fdf679f700997951c6c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa873cdb66e593236e466fd0d452a0a82">isColdCallSite</a> (const CallBase &amp;CB, BlockFrequencyInfo *BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if call site <span class="doxyComputerOutput">CB</span> is considered cold. <a href="#aa873cdb66e593236e466fd0d452a0a82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae48ebfb8f85e9b59325d20cdc9299f0e">getOrCompHotCountThreshold</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns HotCountThreshold if set. <a href="#ae48ebfb8f85e9b59325d20cdc9299f0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ecb24d8737d52d6d5875479dcd42e8">getOrCompColdCountThreshold</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns ColdCountThreshold if set. <a href="#a10ecb24d8737d52d6d5875479dcd42e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd23a0c84ddc290f08599b62968af701">getHotCountThreshold</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns HotCountThreshold if set. <a href="#abd23a0c84ddc290f08599b62968af701">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84cc40d61551557d978104f21e9860e8">getColdCountThreshold</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns ColdCountThreshold if set. <a href="#a84cc40d61551557d978104f21e9860e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53d4780188522be32b92c98a627bb2f7">computeThresholds</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the hot and cold thresholds. <a href="#a53d4780188522be32b92c98a627bb2f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0208b603366e75dbce0437f2fecdf200">computeThreshold</a> (int PercentileCutoff) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FuncT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae2ef603a305221099b5aa8e0439cddd9">getTotalCallCount</a> (const FuncT *F) const -&gt; std::optional&lt; uint64_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool isHot, typename FuncT, typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5532e16856c1aea4a8c53591b339ebbd">isFunctionHotOrColdInCallGraphNthPercentile</a> (int PercentileCutoff, const FuncT *F, BFIT &amp;FI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool isHot&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6830c0d08b5f5186332c233450aa881b">isHotOrColdCountNthPercentile</a> (int PercentileCutoff, uint64_t C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool isHot, typename BBType, typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad118ff50c3171f0b78ecbcc4ec53fff7">isHotOrColdBlockNthPercentile</a> (int PercentileCutoff, const BBType *BB, BFIT *BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool isHot, typename BFIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9d556c0455c0bf8cfd2416e85fd7b14e">isHotOrColdBlockNthPercentile</a> (int PercentileCutoff, BlockFrequency BlockFreq, BFIT *BFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FuncT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8ecd75303c926cfec1ba39a8f79059de">getEntryCount</a> (const FuncT *F) const -&gt; std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/function/profilecount">Function::ProfileCount</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77103e1c8645cacd6ce7c9828af48f3">getTotalCallCount</a> (const Function *F) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/function/profilecount">Function::ProfileCount</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e66c79782abf9fcbb6101bfd88a404c">getEntryCount</a> (const MachineFunction *F) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad806ee85f2240e31b178e82254973d44">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/profilesummary">ProfileSummary</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f8b3b3476be1c01ff36272bd2d8f25">Summary</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f752c103dba21c8f8ed60e62b4554be">HotCountThreshold</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43aa32ad45678fe9e06179eb1ee370ab">ColdCountThreshold</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a687179a0ec2745dc9b3d8b9a58812e4a">HasHugeWorkingSetSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e3d4a39e6c6bd346dda01faf527e795">HasLargeWorkingSetSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af29c30beb84c5d31eb8fc3ee17118627">ThresholdCache</a></td>
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

<p>Analysis providing profile information.</p>


<p>This is an immutable analysis pass that provides ability to query global (program-level) profile information. The main APIs are isHotCount and isColdCount that tells whether a given profile count is considered hot/cold based on the profile summary. This also provides convenience methods to check whether a function is hot or cold.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ProfileSummaryInfo() {#abb05603aef033fa3fc732f6a894e5e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ProfileSummaryInfo::ProfileSummaryInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>Reference <a href="#a2600478d8188a85a14af8787024e1831">refresh</a>.</p>


<p>Referenced by <a href="#aaf06320b1c235da8418d00b9f98a9a71">ProfileSummaryInfo</a>.</p>

</div>
</div>

### ProfileSummaryInfo() {#aaf06320b1c235da8418d00b9f98a9a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ProfileSummaryInfo::ProfileSummaryInfo (<a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> &amp;&amp; Arg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>Reference <a href="#abb05603aef033fa3fc732f6a894e5e0c">ProfileSummaryInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getColdCountThreshold() {#a84cc40d61551557d978104f21e9860e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ProfileSummaryInfo::getColdCountThreshold ()</td>
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

<p>Returns ColdCountThreshold if set.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### getHotCountThreshold() {#abd23a0c84ddc290f08599b62968af701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ProfileSummaryInfo::getHotCountThreshold ()</td>
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

<p>Returns HotCountThreshold if set.</p>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### getOrCompColdCountThreshold() {#a10ecb24d8737d52d6d5875479dcd42e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ProfileSummaryInfo::getOrCompColdCountThreshold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns ColdCountThreshold if set.</p>


<p>Recompute HotCountThreshold if not set.</p>


<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a78deffb09f38652d08cb57cce3119fc7">annotateAllFunctions</a>.</p>

</div>
</div>

### getOrCompHotCountThreshold() {#ae48ebfb8f85e9b59325d20cdc9299f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ProfileSummaryInfo::getOrCompHotCountThreshold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns HotCountThreshold if set.</p>


<p>Recompute HotCountThreshold if not set.</p>


<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a78deffb09f38652d08cb57cce3119fc7">annotateAllFunctions</a>.</p>

</div>
</div>

### getProfileCount() {#a37e70e7a7b5e8ebe792ecaec8639d16e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; ProfileSummaryInfo::getProfileCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CallInst, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, bool AllowSynthetic=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the profile count for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a></span>.</p>

<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="#a42c9b372f129ae40b72b97ce6df45eed">hasSampleProfile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>, <a href="#aa873cdb66e593236e466fd0d452a0a82">isColdCallSite</a>, <a href="#ab3d4f70baa23fdf679f700997951c6c1">isHotCallSite</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8385c2a142c1616d8d486bcb93213649">updateCallProfile</a>.</p>

</div>
</div>

### hasCSInstrumentationProfile() {#a077d500a5e9209486b76dd5da3e673c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::hasCSInstrumentationProfile ()</td>
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

<p>Returns true if module <span class="doxyComputerOutput">M</span> has context sensitive instrumentation profile.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>References <a href="#a11d1c1af51bf81a6a9f8f5191b5e3cf2">hasProfileSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#aa5aa682b3904e88749fa973b3da370c2a1342349bb5356c363f057ba5d8203516">llvm::ProfileSummary::PSK_CSInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#a0045721a7b443c9ed664f9e41abf5cad">isColdBlock</a>.</p>

</div>
</div>

### hasHugeWorkingSetSize() {#ad7a8ced5ff54962319d57208f5d4a57e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProfileSummaryInfo::hasHugeWorkingSetSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the working set size of the code is considered huge.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>

</div>
</div>

### hasInstrumentationProfile() {#a21a2dd574b9729dcd05b46dae856ebc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::hasInstrumentationProfile ()</td>
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

<p>Returns true if module <span class="doxyComputerOutput">M</span> has instrumentation profile.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>References <a href="#a11d1c1af51bf81a6a9f8f5191b5e3cf2">hasProfileSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#aa5aa682b3904e88749fa973b3da370c2a8c847a58db35295f26d16ccbfcac6e0c">llvm::ProfileSummary::PSK_Instr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#a0045721a7b443c9ed664f9e41abf5cad">isColdBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af0543650f6301aa9516ffd97d2540c90">llvm::isPGSOColdCodeOnly</a>.</p>

</div>
</div>

### hasLargeWorkingSetSize() {#a99d3f3ea07d22d6ada9863087570aaeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProfileSummaryInfo::hasLargeWorkingSetSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the working set size of the code is considered large.</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af0543650f6301aa9516ffd97d2540c90">llvm::isPGSOColdCodeOnly</a>.</p>

</div>
</div>

### hasPartialSampleProfile() {#a9610274171a85158779e7ee6031d2376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProfileSummaryInfo::hasPartialSampleProfile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if module <span class="doxyComputerOutput">M</span> has partial-profile sample profile.</p>

<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>References <a href="#a11d1c1af51bf81a6a9f8f5191b5e3cf2">hasProfileSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp/#abfe52f140629541dd4c5f79cde7e2bdd">PartialProfile</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#aa5aa682b3904e88749fa973b3da370c2a0c86eaeebf5b6120b601ecc93a1c2e3a">llvm::ProfileSummary::PSK_Sample</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>, <a href="#a215c4f3e485345daeb8e9d68264f388a">isFunctionHotnessUnknown</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af0543650f6301aa9516ffd97d2540c90">llvm::isPGSOColdCodeOnly</a>.</p>

</div>
</div>

### hasProfileSummary() {#a11d1c1af51bf81a6a9f8f5191b5e3cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::hasProfileSummary ()</td>
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

<p>Returns true if profile summary is available.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>Referenced by <a href="#a077d500a5e9209486b76dd5da3e673c4">hasCSInstrumentationProfile</a>, <a href="#a21a2dd574b9729dcd05b46dae856ebc4">hasInstrumentationProfile</a>, <a href="#a9610274171a85158779e7ee6031d2376">hasPartialSampleProfile</a>, <a href="#a42c9b372f129ae40b72b97ce6df45eed">hasSampleProfile</a>, <a href="#a1cdf368dd1d358e55f871484b1fec5cc">isFunctionColdInCallGraph</a>, <a href="#af813576f394d690d9d51ca46810eaf87">isFunctionEntryCold</a>, <a href="#a55d31db902636df919d451f2b5859f50">isFunctionEntryHot</a>, <a href="#a8a527a78e773ac22ca346a7b8ca9201e">isFunctionHotInCallGraph</a>, <a href="/web-llvm/docs/api/classes/anonymous-indirectcallpromotion-cpp-/indirectcallpromoter/#a1ee24b9cc3b8ee886c655caed7e6cb11">anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::processFunction</a>, <a href="#a2600478d8188a85a14af8787024e1831">refresh</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncombiningpass/#ab64b7e967adeebc9bacc8abd8ddce0c8">llvm::InstructionCombiningPass::runOnFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d7a1de02f328989c5b11130903ef323">llvm::shouldFuncOptimizeForSizeImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9da4ed3292eb88e8986b5399f103e7af">llvm::shouldOptimizeForSizeImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoforcefunctionattrs-cpp/#a644a080a4331977e6930434b8eedb1d5">shouldRunOnFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a00b3b7cedd83de61be0312c6535f3f37">unswitchLoop</a>.</p>

</div>
</div>

### hasSampleProfile() {#a42c9b372f129ae40b72b97ce6df45eed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::hasSampleProfile ()</td>
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

<p>Returns true if module <span class="doxyComputerOutput">M</span> has sample profile.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>References <a href="#a11d1c1af51bf81a6a9f8f5191b5e3cf2">hasProfileSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#aa5aa682b3904e88749fa973b3da370c2a0c86eaeebf5b6120b601ecc93a1c2e3a">llvm::ProfileSummary::PSK_Sample</a>.</p>


<p>Referenced by <a href="#a37e70e7a7b5e8ebe792ecaec8639d16e">getProfileCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#a0045721a7b443c9ed664f9e41abf5cad">isColdBlock</a>, <a href="#aa873cdb66e593236e466fd0d452a0a82">isColdCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0543650f6301aa9516ffd97d2540c90">llvm::isPGSOColdCodeOnly</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a9f05c8e7366bb0f541cdc6c03b929ddd">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d7a1de02f328989c5b11130903ef323">llvm::shouldFuncOptimizeForSizeImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9da4ed3292eb88e8986b5399f103e7af">llvm::shouldOptimizeForSizeImpl</a>.</p>

</div>
</div>

### invalidate() {#af5467cd3b1ab6bdcbebba1988f96108f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::invalidate (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp;, ModuleAnalysisManager::Invalidator &amp;)</td>
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

<p>Handle the invalidation of this information.</p>


<p>When used as a result of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryanalysis">ProfileSummaryAnalysis</a></span> this method will be called when the module this was computed for changes. Since profile summary is immutable after it is annotated on the module, we return false here.</p>


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### isColdBlock() {#a597b25ab8d0a79f855c6c66dc48cb803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BBType, typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isColdBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BBType * BB, BFIT * BFI)</td>
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

<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <span class="doxyComputerOutput">BB</span> is considered cold.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="#a5f58eb949321536363605ac9920a95cb">isColdCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-sizeopts-cpp-/basicblockbfiadapter/#ad1a2732fe432cfc0a46f6dcfbcc75572">anonymous{SizeOpts.cpp}::BasicBlockBFIAdapter::isColdBlock</a>, <a href="#a1cdf368dd1d358e55f871484b1fec5cc">isFunctionColdInCallGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9da4ed3292eb88e8986b5399f103e7af">llvm::shouldOptimizeForSizeImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a00b3b7cedd83de61be0312c6535f3f37">unswitchLoop</a>.</p>

</div>
</div>

### isColdBlock() {#a8fbb537d20b4320256065afd39ef57f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isColdBlock (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> BlockFreq, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BFIT * BFI)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="#a5f58eb949321536363605ac9920a95cb">isColdCount</a>.</p>

</div>
</div>

### isColdBlockNthPercentile() {#ada543df24b6c3fa80f90e0aab1bb68f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BBType, typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isColdBlockNthPercentile (int PercentileCutoff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BBType * BB, BFIT * BFI)</td>
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

<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <span class="doxyComputerOutput">BB</span> is considered cold with regard to a given cold percentile cutoff value.</p>


<p>PercentileCutoff is encoded as a 6 digit decimal fixed point number, where the first two digits are the whole part. E.g. 995000 for 99.5 percentile.</p>


<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#aa9a7a2d102bd9e5a4c6569f16de79b87">PercentileCutoff</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-sizeopts-cpp-/basicblockbfiadapter/#af9953c3033ee1f232e4ed04ea3dfb14d">anonymous{SizeOpts.cpp}::BasicBlockBFIAdapter::isColdBlockNthPercentile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9da4ed3292eb88e8986b5399f103e7af">llvm::shouldOptimizeForSizeImpl</a>.</p>

</div>
</div>

### isColdBlockNthPercentile() {#ac125007461291d169ae8c200550184ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isColdBlockNthPercentile (int PercentileCutoff, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> BlockFreq, BFIT * BFI)</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#aa9a7a2d102bd9e5a4c6569f16de79b87">PercentileCutoff</a>.</p>

</div>
</div>

### isColdCallSite() {#aa873cdb66e593236e466fd0d452a0a82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProfileSummaryInfo::isColdCallSite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if call site <span class="doxyComputerOutput">CB</span> is considered cold.</p>

<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#afac5b39bcbb90d660f83d9b4bd8c6d95">llvm::CallBase::getCaller</a>, <a href="#a37e70e7a7b5e8ebe792ecaec8639d16e">getProfileCount</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9084ce2576fad285c1c0dc1e165dd4b6">llvm::Function::hasProfileData</a>, <a href="#a42c9b372f129ae40b72b97ce6df45eed">hasSampleProfile</a> and <a href="#a5f58eb949321536363605ac9920a95cb">isColdCount</a>.</p>

</div>
</div>

### isColdCount() {#a5f58eb949321536363605ac9920a95cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProfileSummaryInfo::isColdCount (uint64_t C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if count <span class="doxyComputerOutput">C</span> is considered cold.</p>

<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sampleprofutil/#ab6789a9522443425d339fa34c25f89d5">llvm::sampleprofutil::callsiteIsHot</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a38dd3609a23a5d917457d18d88fceff3">getHotness</a>, <a href="#a8fbb537d20b4320256065afd39ef57f9">isColdBlock</a>, <a href="#a597b25ab8d0a79f855c6c66dc48cb803">isColdBlock</a>, <a href="#aa873cdb66e593236e466fd0d452a0a82">isColdCallSite</a>, <a href="#a1cdf368dd1d358e55f871484b1fec5cc">isFunctionColdInCallGraph</a> and <a href="#af813576f394d690d9d51ca46810eaf87">isFunctionEntryCold</a>.</p>

</div>
</div>

### isColdCountNthPercentile() {#a731b588787c30ac1905c449402cc8b06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProfileSummaryInfo::isColdCountNthPercentile (int PercentileCutoff, uint64_t C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if count <span class="doxyComputerOutput">C</span> is considered cold with regard to a given cold percentile cutoff value.</p>


<p>PercentileCutoff is encoded as a 6 digit decimal fixed point number, where the first two digits are the whole part. E.g. 995000 for 99.5 percentile.</p>


<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#aa9a7a2d102bd9e5a4c6569f16de79b87">PercentileCutoff</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#a0045721a7b443c9ed664f9e41abf5cad">isColdBlock</a>.</p>

</div>
</div>

### isFunctionColdInCallGraph() {#a1cdf368dd1d358e55f871484b1fec5cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FuncT, typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isFunctionColdInCallGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncT * F, BFIT &amp; BFI)</td>
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

<p>Returns true if <span class="doxyComputerOutput">F</span> contains only cold code.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a11d1c1af51bf81a6a9f8f5191b5e3cf2">hasProfileSummary</a>, <a href="#a597b25ab8d0a79f855c6c66dc48cb803">isColdBlock</a> and <a href="#a5f58eb949321536363605ac9920a95cb">isColdCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-sizeopts-cpp-/basicblockbfiadapter/#a539ba40f7b48ee0cae45f2c81c22dd87">anonymous{SizeOpts.cpp}::BasicBlockBFIAdapter::isFunctionColdInCallGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d7a1de02f328989c5b11130903ef323">llvm::shouldFuncOptimizeForSizeImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoforcefunctionattrs-cpp/#a644a080a4331977e6930434b8eedb1d5">shouldRunOnFunction</a>.</p>

</div>
</div>

### isFunctionColdInCallGraphNthPercentile() {#a3b3f19a7c246b09a46ab4dcf3b05e212}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FuncT, typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isFunctionColdInCallGraphNthPercentile (int PercentileCutoff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncT * F, BFIT &amp; BFI)</td>
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

<p>Returns true if <span class="doxyComputerOutput">F</span> contains cold code with regard to a given cold percentile cutoff value.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#aa9a7a2d102bd9e5a4c6569f16de79b87">PercentileCutoff</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-sizeopts-cpp-/basicblockbfiadapter/#a487adc559a3901b29829ef17418c46c1">anonymous{SizeOpts.cpp}::BasicBlockBFIAdapter::isFunctionColdInCallGraphNthPercentile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4d7a1de02f328989c5b11130903ef323">llvm::shouldFuncOptimizeForSizeImpl</a>.</p>

</div>
</div>

### isFunctionEntryCold() {#af813576f394d690d9d51ca46810eaf87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProfileSummaryInfo::isFunctionEntryCold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">F</span> has cold function entry.</p>


<p>Returns true if the function's entry is a cold.</p>


<p>If it returns false, it either means it is not cold or it is unknown whether it is cold or not (for example, no profile data is available).</p>


<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a11d1c1af51bf81a6a9f8f5191b5e3cf2">hasProfileSummary</a> and <a href="#a5f58eb949321536363605ac9920a95cb">isColdCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/profilesummaryprinterpass/#aff1db3108eff5862498fecfa0d419d72">llvm::ProfileSummaryPrinterPass::run</a>.</p>

</div>
</div>

### isFunctionEntryHot() {#a55d31db902636df919d451f2b5859f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FuncT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isFunctionEntryHot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncT * F)</td>
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

<p>Returns true if <span class="doxyComputerOutput">F</span> has hot function entry.</p>


<p>If it returns false, it either means it is not hot or it is unknown whether it is hot or not (for example, no profile data is available).</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a11d1c1af51bf81a6a9f8f5191b5e3cf2">hasProfileSummary</a> and <a href="#ac46d4d55dd867977ba88d57a170e31de">isHotCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/profilesummaryprinterpass/#aff1db3108eff5862498fecfa0d419d72">llvm::ProfileSummaryPrinterPass::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a7cf6fe605431375e61c307bb1ca5cf41">shouldApply</a>.</p>

</div>
</div>

### isFunctionHotInCallGraph() {#a8a527a78e773ac22ca346a7b8ca9201e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FuncT, typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isFunctionHotInCallGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncT * F, BFIT &amp; BFI)</td>
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

<p>Returns true if <span class="doxyComputerOutput">F</span> contains hot code.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a11d1c1af51bf81a6a9f8f5191b5e3cf2">hasProfileSummary</a>, <a href="#abe32f174e5db14e8616ae5df650da111">isHotBlock</a> and <a href="#ac46d4d55dd867977ba88d57a170e31de">isHotCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a9f05c8e7366bb0f541cdc6c03b929ddd">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::runOnMachineFunction</a>.</p>

</div>
</div>

### isFunctionHotInCallGraphNthPercentile() {#a6f820b8a83376970321b6e7211df6087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FuncT, typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isFunctionHotInCallGraphNthPercentile (int PercentileCutoff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncT * F, BFIT &amp; BFI)</td>
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

<p>Returns true if <span class="doxyComputerOutput">F</span> contains hot code with regard to a given hot percentile cutoff value.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#aa9a7a2d102bd9e5a4c6569f16de79b87">PercentileCutoff</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-sizeopts-cpp-/basicblockbfiadapter/#a5ceb0c8cea4ef385045be47988e7306b">anonymous{SizeOpts.cpp}::BasicBlockBFIAdapter::isFunctionHotInCallGraphNthPercentile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4d7a1de02f328989c5b11130903ef323">llvm::shouldFuncOptimizeForSizeImpl</a>.</p>

</div>
</div>

### isFunctionHotnessUnknown() {#a215c4f3e485345daeb8e9d68264f388a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProfileSummaryInfo::isFunctionHotnessUnknown (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the hotness of <span class="doxyComputerOutput">F</span> is unknown.</p>

<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a9610274171a85158779e7ee6031d2376">hasPartialSampleProfile</a>.</p>

</div>
</div>

### isHotBlock() {#abe32f174e5db14e8616ae5df650da111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BBType, typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isHotBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BBType * BB, BFIT * BFI)</td>
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

<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <span class="doxyComputerOutput">BB</span> is considered hot.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="#ac46d4d55dd867977ba88d57a170e31de">isHotCount</a>.</p>


<p>Referenced by <a href="#a8a527a78e773ac22ca346a7b8ca9201e">isFunctionHotInCallGraph</a>.</p>

</div>
</div>

### isHotBlockNthPercentile() {#a199ef173a063b51608e3438d8ab325d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BBType, typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isHotBlockNthPercentile (int PercentileCutoff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BBType * BB, BFIT * BFI)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#aa9a7a2d102bd9e5a4c6569f16de79b87">PercentileCutoff</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-sizeopts-cpp-/basicblockbfiadapter/#a4568820f0bb68e1a62ed75edb08f4a28">anonymous{SizeOpts.cpp}::BasicBlockBFIAdapter::isHotBlockNthPercentile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9da4ed3292eb88e8986b5399f103e7af">llvm::shouldOptimizeForSizeImpl</a>.</p>

</div>
</div>

### isHotBlockNthPercentile() {#af4346625334107fbea42a8e1d607a20a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isHotBlockNthPercentile (int PercentileCutoff, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> BlockFreq, BFIT * BFI)</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#aa9a7a2d102bd9e5a4c6569f16de79b87">PercentileCutoff</a>.</p>

</div>
</div>

### isHotCallSite() {#ab3d4f70baa23fdf679f700997951c6c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProfileSummaryInfo::isHotCallSite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the call site <span class="doxyComputerOutput">CB</span> is considered hot.</p>

<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a37e70e7a7b5e8ebe792ecaec8639d16e">getProfileCount</a> and <a href="#ac46d4d55dd867977ba88d57a170e31de">isHotCount</a>.</p>

</div>
</div>

### isHotCount() {#ac46d4d55dd867977ba88d57a170e31de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProfileSummaryInfo::isHotCount (uint64_t C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if count <span class="doxyComputerOutput">C</span> is considered hot.</p>

<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sampleprofutil/#ab6789a9522443425d339fa34c25f89d5">llvm::sampleprofutil::callsiteIsHot</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a38dd3609a23a5d917457d18d88fceff3">getHotness</a>, <a href="#a55d31db902636df919d451f2b5859f50">isFunctionEntryHot</a>, <a href="#a8a527a78e773ac22ca346a7b8ca9201e">isFunctionHotInCallGraph</a>, <a href="#abe32f174e5db14e8616ae5df650da111">isHotBlock</a>, <a href="#ab3d4f70baa23fdf679f700997951c6c1">isHotCallSite</a> and <a href="/web-llvm/docs/api/classes/anonymous-indirectcallpromotion-cpp-/indirectcallpromoter/#a1ee24b9cc3b8ee886c655caed7e6cb11">anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::processFunction</a>.</p>

</div>
</div>

### isHotCountNthPercentile() {#a829b6546f1d344de8cc5a6be1dd1e424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProfileSummaryInfo::isHotCountNthPercentile (int PercentileCutoff, uint64_t C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if count <span class="doxyComputerOutput">C</span> is considered hot with regard to a given hot percentile cutoff value.</p>


<p>PercentileCutoff is encoded as a 6 digit decimal fixed point number, where the first two digits are the whole part. E.g. 995000 for 99.5 percentile.</p>


<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#aa9a7a2d102bd9e5a4c6569f16de79b87">PercentileCutoff</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/lowerallowcheckpass-cpp/#aeab949c1d2a96004a9076b8b2176ca74">removeUbsanTraps</a>.</p>

</div>
</div>

### refresh() {#a2600478d8188a85a14af8787024e1831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ProfileSummaryInfo::refresh ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If no summary is present, attempt to refresh.</p>

<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#abd7d6edfeb702be2177e7e6bcb70aff7">llvm::ProfileSummary::getFromMD</a> and <a href="#a11d1c1af51bf81a6a9f8f5191b5e3cf2">hasProfileSummary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a78deffb09f38652d08cb57cce3119fc7">annotateAllFunctions</a> and <a href="#abb05603aef033fa3fc732f6a894e5e0c">ProfileSummaryInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeThreshold() {#a0208b603366e75dbce0437f2fecdf200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; ProfileSummaryInfo::computeThreshold (int PercentileCutoff)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>

</div>
</div>

### computeThresholds() {#a53d4780188522be32b92c98a627bb2f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ProfileSummaryInfo::computeThresholds ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the hot and cold thresholds.</p>

<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>

</div>
</div>

### getEntryCount() {#a8ecd75303c926cfec1ba39a8f79059de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FuncT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Function::ProfileCount &gt; llvm::ProfileSummaryInfo::getEntryCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncT * F)</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### getEntryCount() {#a9e66c79782abf9fcbb6101bfd88a404c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Function::ProfileCount &gt; llvm::ProfileSummaryInfo::getEntryCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### getTotalCallCount() {#ae2ef603a305221099b5aa8e0439cddd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FuncT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::ProfileSummaryInfo::getTotalCallCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncT * F)</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### getTotalCallCount() {#ae77103e1c8645cacd6ce7c9828af48f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::ProfileSummaryInfo::getTotalCallCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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



<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### isFunctionHotOrColdInCallGraphNthPercentile() {#a5532e16856c1aea4a8c53591b339ebbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool isHot, typename FuncT, typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isFunctionHotOrColdInCallGraphNthPercentile (int PercentileCutoff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncT * F, BFIT &amp; FI)</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### isHotOrColdBlockNthPercentile() {#ad118ff50c3171f0b78ecbcc4ec53fff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool isHot, typename BBType, typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isHotOrColdBlockNthPercentile (int PercentileCutoff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BBType * BB, BFIT * BFI)</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### isHotOrColdBlockNthPercentile() {#a9d556c0455c0bf8cfd2416e85fd7b14e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool isHot, typename BFIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfileSummaryInfo::isHotOrColdBlockNthPercentile (int PercentileCutoff, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> BlockFreq, BFIT * BFI)</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### isHotOrColdCountNthPercentile() {#a6830c0d08b5f5186332c233450aa881b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool isHot&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProfileSummaryInfo::isHotOrColdCountNthPercentile (int PercentileCutoff, uint64_t C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ColdCountThreshold {#a43aa32ad45678fe9e06179eb1ee370ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::ProfileSummaryInfo::ColdCountThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### HasHugeWorkingSetSize {#a687179a0ec2745dc9b3d8b9a58812e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::ProfileSummaryInfo::HasHugeWorkingSetSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### HasLargeWorkingSetSize {#a2e3d4a39e6c6bd346dda01faf527e795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::ProfileSummaryInfo::HasLargeWorkingSetSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### HotCountThreshold {#a0f752c103dba21c8f8ed60e62b4554be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::ProfileSummaryInfo::HotCountThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### M {#ad806ee85f2240e31b178e82254973d44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module* llvm::ProfileSummaryInfo::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### Summary {#a22f8b3b3476be1c01ff36272bd2d8f25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ProfileSummary&gt; llvm::ProfileSummaryInfo::Summary</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

### ThresholdCache {#af29c30beb84c5d31eb8fc3ee17118627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;int, uint64_t&gt; llvm::ProfileSummaryInfo::ThresholdCache</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">ProfileSummaryInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
